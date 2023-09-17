
#### SRS concentrates on 
- Once requirements are gathered & analyzed, they can be specified in the document. 
- *SRS main aim* of this document is to systematically organize the gathered requirements in a formal specific. 
- SRS only contains what needs to be done, doesn't involve the implementation details. 
- The answer to how to implement will be provided in the **Design Phase**.

#### SRS document is useful in various contexts
- SRS will be reviewed and signed off by the stakeholder and feedback will be given. 
- It should be in easily readable by the people with little or no technical knowledge. 
- it serves as a reference document definition for implementation. 
- statement of user needs.
- it is a contract between the development team and the customer. 

#### Properties of a good SRS 
- concise, easy to change.
- specify what to do (not how to do). 
- consistent (no two require should conflict). 
- traceable (trace which part of specification/designs corresponds to)
- verifiable. (iff there exists a finite process with which we can ensure that product meets the requirement). 
- *example :* system should be user friendly isn't verifiable because it is impossible to define the terms *good*, *well* or *usually*.

#### SRS document normally contains 3 important parts

- **Functional requirements**: specifies the input, the task and the output.
- **non-Functional requirement**: specifies the overall quality attributes & constraints to be imposed on the system
- **Constraints to the system**:  constraints describes any issues that may limit the options available to the developers for ex. regulatory, policies, hardware limitation, interfaces to the other applications. 
##### functional requirement
- describes set of high level requirements identified as customer requirements. 
- each high level requirement will take some data as input from user.
- process the input data & finally provide an output. 
- *example* a system must send an email whenever an order is placed. 

#### Example
> For a matrimonial website list down the functional requirement.
- Register user, 
- match horoscope
- update user details
- members online 
- search by mother tongue 

> non-functional requirement 
- maintainability. 
- portability 
- usability 
- reliability 
- robustness. 

#### constraints
a constraint describe things that the system should or should not do.
- standard compliance. 
- how quickly system can produce results so that it does not overload the other system to which it supplies data.
- hardware to be used.
- OS
- DBMS to be used. 
- capabilities of IO devices. 
- Data representation. 

#### organisation of SRS document
- introduction
- functional requirements. 
- nonfunctional requirements 
	- external interface requirements 
	- performance requirements
- constraints
