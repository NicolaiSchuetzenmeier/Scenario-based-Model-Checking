# Scenario-based Model Checking of Declarative Process Models
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

*Excerpt from the paper "Scenario-based Model Checking of Declarative Process Models" (currently under review)*

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
    -    
    ```
## Citation
If you use the tool or the data in your paper, please cite the following paper:
```
@article{schuetzenmeier-2022-scenariobased,
    title = "Scenario-based model checking of Declarative Process Models",
    author = "Sch\"{u}tzenmeier, Nicolai and K\"{a}ppel, Martin and 
        Fichtner, Myriel and Jablonski, Stefan",
    year = "Currently under review",
    publisher = "Springer"
}
```

## Contact
- [nicolai.schuetzenmeier@uni-bayreuth.de](mailto:nicolai.schuetzenmeier@uni-bayreuth.de)
- [martin.kaeppel@uni-bayreuth.de](mailto:martin.kaeppel@uni-bayreuth.de)
- [myriel.fichtner@uni-bayreuth.de](mailto:myriel.fichtner@uni-bayreuth.de)
- [stefan.jablonski@uni-bayreuth.de](mailto:stefan.jablonski@uni-bayreuth.de)
