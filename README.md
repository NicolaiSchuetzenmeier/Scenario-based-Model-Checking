# Scenario-Based Model Checking of Declarative Process Models
> Modeling processes with declarative process models, i.e. sets of constraints which have to be satisfied throughout the whole 
process execution, allows for a great degree of flexibility in process execution. However, having a process specified by means 
of symbolic, textual or formally constraints comes along with the problem that it is often hard for humans to understand complicated 
interactions of constraints and overlook the entire process model without unintentional neglecting of important process details. 
Caused by these reasons, standard questions regarding process models, e.g. "Can a running process instance still be completed successfully?",
can often only be answered with great computational and temporal effort or even not at all. In this paper we present an efficient 
scenario-based approach for declarative process models, which supports process modelers in checking process models for important and common 
scenarios, which regularly occur when modeling declarative processes. We implement our approach and show that the solutions for the scenarios
can be computed within milliseconds even for real-life event logs. Furthermore, a user study conducted demonstrates that the error rate in 
understanding declarative process models is enormously reduced by using our implementation. 

*Excerpt from the paper "Scenario-Based Model Checking of Declarative Process Models"*

## Folder Description of uploaded files:
- "Process models" contains for each BPIC event log used in the paper:
    ```
    - Declare model (*.txt) 
    - corresponding process automaton (*.json) 
    ```
 - "User study" contains:
    ```
    - sets of tasks (*.pdf) including solutions
    - data collection of the participants (Data collection participants.csv):            
    ```
 - Description of all attributes in "Data collection participants.csv):
    ```
    - Nummer: ID for participant
    - Alter: age (Integer)
    - Geschlecht: gender (possible entries: 'm', 'w', 'd')    
    - Abschluss: diploma (String)
    - Ausbildung: education (String)
    - Beruf: profession (String)
    - Feld: field (String)
    - Berufserfahrung: work experience (in years) (Integer)
    - Vorkenntnisse: prior knowledge in BPM (possible entries: 'ja', 'nein')
    - lesen: experience in reading process models (possible entries: 'ja', 'nein')
    - erstellen: experience in creating process models (possible entries: 'ja', 'nein')  
    - dekl. lesen: experience in reading declarative process models (possible entries: 'ja', 'nein')
    - dekl. erstellen: experience in creating declarative process models (possible entries: 'ja', 'nein')  
    - Erfahrung PM: experience in process management (in years - Integer)
    - Erfahrung dekl.: experience in declarative process management (in years - Integer)
    - Start: participant started study with ('m') or without ('o') tool
    - Beginn: participant started study with task set 1 ('1') or task set 2 ('2')
    - Reihenfolge 1: order of tasks of task set 1 (possible entries '123','132','213','231','312','321')
    - Reihenfolge 2: order of tasks of task set 2 (possible entries '123','132','213','231','312','321')
    - 1.1a Zeit: time spent for sub-task 1a of task set 1 (in seconds - Integer)
    - 1.1a Bewertung: gained points for task 1a (Integer between 0 and 5)
    - 1.2a Zeit: time spent for sub-task 2a of task set 1 (in seconds - Integer)
    - 1.2a Bewertung: gained points for sub-task 2a of task set 1(Integer between 0 and 2)
    - 1.2b Zeit: time spent for sub-task 2b of task set 1 (in seconds - Integer)
    - 1.2b Bewertung: gained points for sub-task 2b of task set 1 ('0' or '2')
    - 1.3a Zeit: time spent for sub-task 3a of task set 1 (in seconds - Integer)
    - 1.3a Bewertung: gained points for sub-task 3a of task set 1(Integer between 0 and 8)
    - 1.3b Zeit: time spent for sub-task 3b of task set 1 (in seconds - Integer)
    - 1.3b Bewertung: gained points for sub-task 3b of task set 1 (Integer between 0 and 4)
    - 1.3c Zeit: time spent for sub-task 3c of task set 1 (in seconds - Integer)
    - 1.3c Bewertung: gained points for sub-task 3c of task set 1 (Integer between 0 and 2)
    - 2.1a Zeit: time spent for sub-task 1a of task set 2 (in seconds - Integer)
    - 2.1a Bewertung: gained points for sub-task 1a of task set 2 (Integer between 0 and 4)
    - 2.2a Zeit: time spent for sub-task 2a of task set 2 (in seconds - Integer)
    - 2.2a Bewertung: gained points for sub-task 2a of task set 2 (Integer between 0 and 2)
    - 2.2b Zeit: time spent for sub-task 2b of task set 2 (in seconds - Integer)
    - 2.2b Bewertung: gained points for sub-task 2b of task set 2 ('0' or '2')
    - 2.3a Zeit: time spent for sub-task 3a of task set 2 (in seconds - Integer)
    - 2.3a Bewertung: gained points for sub-task 3a of task set 2 (Integer between 0 and 7)
    - 2.3b Zeit: time spent for sub-task 3b of task set 2 (in seconds - Integer)
    - 2.3b Bewertung: gained points for sub-task 3b of task set 2(Integer between 0 and 6)
    - 2.3c Zeit: time spent for sub-task 3c of task set 2 (in seconds - Integer)
    - 2.3c Bewertung: gained points for sub-task 3c of task set 2(Integer between 0 and 2)
    - 1. Fehlerbeschreibung: description of errors for task set 1 (String)
    - 2. Fehlerbeschreibung: description of errors for task set 2 (String)
    - Angabenzettel verwendet: indicates whether participant used sheet with rules while working with tool (possible entries: 'ja', 'nein')
    - Anstrengung ohne: mental effort for task set without tool (Integer between 0 and 220)
    - Anstrengung mit: mental effort for task set with tool (Integer between 0 and 220)
    ```
## Citation
If you use the tool or the data in your paper, please cite the following paper:
```
@article{schuetzenmeier-2022-scenariobased,
    title = "Scenario-Based Model Checking of Declarative Process Models",
    author = "Sch\"{u}tzenmeier, Nicolai and K\"{a}ppel, Martin and 
        Fichtner, Myriel and Jablonski, Stefan",
    year = "2023"
}
```

## Contact
- [nicolai.schuetzenmeier@uni-bayreuth.de](mailto:nicolai.schuetzenmeier@uni-bayreuth.de)
- [martin.kaeppel@uni-bayreuth.de](mailto:martin.kaeppel@uni-bayreuth.de)
- [myriel.fichtner@uni-bayreuth.de](mailto:myriel.fichtner@uni-bayreuth.de)
- [stefan.jablonski@uni-bayreuth.de](mailto:stefan.jablonski@uni-bayreuth.de)
