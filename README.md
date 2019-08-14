# Resource Scheduling in a Hospital Emergency Department

## Project Goals
An emergency department (ED) relies heavily on diverse types of resources such as humans and hospital resources (e.g., staff and beds). The use of these resources is constrained in a variety of ways such as start time and length of shifts, labor laws, exceptional arrangements and other constraints. In addition, resource scheduling in an ED becomes even more complicated when considering multiple and often conflicting goals and constraints. The complex nature of resource scheduling in an ED poses significant challenges in analyzing important characteristics such as safety, correctness, performance and efficiency in patient care. This project aims to address these challenges by separating resource concerns from others such as activity coordination and artifacts of patient care in an ED. This separation of resource concerns facilitates managing complexities inherent in an ED. Focusing on resource concerns, we are developing novel modelling and analysis techniques to improve the quality of resource scheduling in an ED.

## Approaches
### Rocess Modeling
Precise and detailed process descriptions are specified using the Little-JIL language.
 
### Resource Modeling
Precise resource descriptions such as resource requests, attributes, schedules and policies are specified separately from the process model. 
 
### Resource-Aware Discrete-Event Simulation
This simulation supports flexible change in resource-related decisions such as staffing, nurse-to-patient ratios and other decisions.
 
### Integer Linear Programming (ILP)
The ILP optimizes staffing by considering shift constraints such as start time and shift length.

## Results
"Staffing policies that allow shifts of different lengths and overlapped shifts can reduce costs which still achieving staff utilization levels."
 
"Staffing policies that allow for longer shift length result in fewer handoffs."
 
"Staffing without overlap creates lower LoS than staffing with overlap."
 
"Overlapped staffing shows higher utilization than non-overlapped staffing."
 
"Aiming only to minimize the patients' average LoS may result in high variability in the staff (e.g., nurse) utilization and in the LoS itself across patients."
 
"While increasing resources (e.g., beds and x-ray rooms) reduces LoS, different staffing patterns result in different resource bottlenecks."

## Publications
**[Discrete-Event Simulation and Integer Linear Programming for Constraint-Aware Resource Scheduling](http://people.cs.umass.edu/brun/pubs/pubs/Shin17tsmc.pdf)**,
Seung Yeob Shin, Yuriy Brun, Hari Balasubramanian, Philip L. Henneman, and Leon J. Osterweil, IEEE Transactions on Systems, Man, and Cybernetics: Systems, 2017 

**Specification And Analysis Of Resource Utilization Policies For Human-Intensive Systems**,
Seung Yeob Shin, PhD dissertation, College of Information and Computer Sciences, University of Massachusetts, Amherst, MA 01003, September 2016.

**[Specification and Analysis of Human-Intensive System Resource-Utilization Policies](http://people.cs.umass.edu/brun/pubs/pubs/Shin16SEHS.pdf)**,
Seung Yeob Shin, Yuriy Brun, and Leon J. Osterweil, in Proceedings of the 8th International Workshop on Software Engineering in Healthcare Systems (SEHS), Austin, TX, USA, May 14-15, 2016
 
**[Using Computer Simulation to Study Nurse-to-Patient Ratios in an Emergency Department](http://people.cs.umass.edu/brun/pubs/pubs/Henneman15jona.pdf)**,
Philip L. Henneman, Seung Yeob Shin, Yuriy Brun, Hari Balasubramanian, Fidela Blank, and Leon J. Osterweil, The Journal of Nursing Administration (JONA), Vol. 45, Issue 11, November 2015, pp. 551-556
 
**[Resource Specification for Prototyping Human-Intensive Systems](http://people.cs.umass.edu/brun/pubs/pubs/Shin15fase.pdf)**,
Seung Yeob Shin, Yuriy Brun, Leon J. Osterweil, Hari Balasubramanian, and Philip L. Henneman, in Proceedings of the 18th International Conference on Fundamental Approaches to Software Engineering (FASE), 2015, pp. 332-346.
 
**Discrete-Event Simulation and Integer Linear Programming for Constraint-Aware Resource Scheduling**,
Seung Yeob Shin, Hari Balasubramanian, Yuriy Brun, Philip L. Henneman, and Leon J. Osterweil, University of Massachusetts, Amherst, School of Computer Science, Technical Report, UM-CS-2014-009, 2014
 
**[Resource Scheduling through Resource-Aware Simulation of Emergency Departments](http://people.cs.umass.edu/brun/pubs/pubs/Shin13SEHC.pdf)**,
Seung Yeob Shin, Hari Balasubramanian, Yuriy Brun, Philip L. Henneman and Leon J. Osterweil, Workshop on Software Engineering in Health Care (SEHC13), San Francisco, CA, USA, May 20-21, 2013

## Downloads
Visual-JIL for Eclipse: ([link](http://laser.cs.umass.edu/release/)) - Visual-JIL is an Eclipse-based development environment for Little-JIL.
 
ED Models and Simulator: ([link](./Download))

## Contributors
**College of Information and Computer Sciences, University of Massachusetts, Amherst, MA**

Seung Yeob Shin ([email](mailto:shin@cs.umass.edu), [website](http://people.cs.umass.edu/~shin/))

Leon J. Osterweil ([email](mailto:ljo@cs.umass.edu), [website](http://laser.cs.umass.edu/people/ljo.html))

Yuriy Brun ([email](mailto:brun@cs.umass.edu), [website](http://people.cs.umass.edu/~brun/))
 
**Mechanical and Industrial Engineering, University of Massachusetts, Amherst, MA**

Hari Balasubramanian ([email](mailto:hbalasub@admin.umass.edu), [website](http://people.umass.edu/hbalasub/))
 
**Emergency Medicine at the University of Massachusetts School of Medicine, Amherst, MA**

Philip L. Henneman ([email](mailto:Philip.Henneman@baystatehealth.org), [website](http://baystatehealth.org/AcademicAffairs/Main+Nav/Departments/Emergency+Medicine/Faculty/ci.Henneman.Print))
