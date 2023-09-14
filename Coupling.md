
- degree of interaction between two modules. 
- **tightly coupled ->** depend on each other greatly. 
- **Loosely coupled ->** have some dependency, but have weak interconnections. 

![[attachments/Pasted image 20230914023807.png]]

#### Content coupling
- one component modifies an internal data item in another component.
- one component branches into the middle of another component. 
- **to reduce** hide the data so that it can be accessed only by calling the method that can access or modify the data. 
- ![[attachments/Pasted image 20230914024033.png]]

#### Common coupling
two modules have write access to the same *global data*. 
#### Control coupling
- one module passes an element of control to the other. 
- it is impossible for the widget module to function without some direction from controlling module. 
- ![[attachments/Pasted image 20230914024259.png]]
- Only when controlled module get some directions from the controlled module, it performs the operations.
- In above example on passing error flag, it displays the error. 

#### Stamp coupling
Data structure is passed as parameter, but the called module operates on only some of the passed components. 

![[attachments/Pasted image 20230914024408.png]]

#### Data coupling
Every argument is either a simple argument of a data structure in which all elements are used by the called module. 

![[attachments/Pasted image 20230914024450.png]]

here the called module use all the parameters to produce the output. 

