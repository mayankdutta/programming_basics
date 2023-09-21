- makes software reliable and extendable. 
- refers to dependence within & among the same module's internal elements. (e.g., data, functions, internal modules)
- internal glue that keeps all things together. 
- Greater the cohesion, the better is the program design. 
- ![[attachments/Pasted image 20230914024904.png]]


#### Co-incidental Cohesion (lowest cohesion)
module performs multiple, completely unrelated actions. 
that contains instructions,
have no relationship with one another. 

![[attachments/Pasted image 20230914034230.png]]

above operations are unrelated to each other. 
#### Logical Cohesion
- elements perform similar tasks & the activities to be executed are chosen from outside the module. 
- operations are related but the functions are significantly different. 
- refers to dependence within & among the same module's internal elements. (e.g., data, functions, internal modules)
- reading data from database.
- logic same, functoinality different 
- file network, db is differetn. 
- Greater the cohesion, the better is the program design. 
- ![[attachments/Pasted image 20230914024904.png]]


#### Co-incidental 
module performs multiple, completely unrelated actions. 

![[attachments/Pasted image 20230914034230.png]]

above operations are unrelated to each other. 
#### Logical Cohesion
- elements perform similar tasks & the activities to be executed are chosen from *outside the module*. 
- operations are related but the functions are significantly different. 
- ![[attachments/Pasted image 20230914025135.png]]

#### Temporal Cohesion
- module's data & function are related because they are used at the same time in an execution. 
- elements are grouped by when they are processed. 
- ![[attachments/Pasted image 20230914025317.png]]

#### Procedural Cohesion
- similar to temporal & functions pertain to some related action or purpose. 
- ![[attachments/Pasted image 20230914025501.png]]

#### Communicational Cohesion
- module which has activities executed sequentially and *work on same data*. 
- boundaries input, output is defined. 
- 
- ![[attachments/Pasted image 20230914025547.png]]

#### Sequential Cohesion
- elements are involved in activities such that output data from one activity *becomes input to next activity*. 
- 
- ![[attachments/Pasted image 20230914025716.png]]

#### Functional Cohesion (best cohesion)
- module performs exactly one action. 
- highly recommended form of cohesion. 
- all activities are functionally related. 
- hash include statement, holds, & independent. 
- ![[attachments/Pasted image 20230914025806.png]]
