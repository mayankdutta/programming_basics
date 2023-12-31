SRS design documents, source code, testing reports etc. These artifacts need to be accessed and modified by multiple team, how to do it? **software configuration management**

### configuration

**configuration** a configuration is the functional and physical characteristics of a hardware or software set forth in technical documentation or achieved in a product. 
#### configuration management 
1. **configuration identification** identifies the configuration items & labels each item with unique identifiers.
2. **change management** tracking and controlling the changes during development. 
3. **configuration status accounting** status and various information about configuration item 
4. **configuration audits** responsible for reviewing the items against various specifications for assessing its quality and correctness. 

*configuration management* is the process of coordinating the software development by tracking, modifying & controlling changes to the software. 


### software configuration  
#### why software config management is important. 
- Software config is important because new versions of software systems are created as they get changed for different OS 
- diff. functionalities that aren't present in the previous version might be needed. 
- config management is responsible for managing & controlling the costs & efforts involved in making changes to a system. 


#### software config management (SCM)
SCM defines. 
- the types of documents to be managed & a document naming scheme
- who takes responsibility for the CM procedures and creation of *baselines*. 
- policies for change control and version management. 
- the CM records which must be maintained. 

A **baseline** is a formally reviewed and approved document by the management that can be used as the basis for further development. 

SCM specifies the tools which should be used to assist the CM process and any limitations on their use. 

#### effectiveness of SCM
SCM is said to be effective
- when every work product can be accounted for
- when every work product or change made to it can be tracked and controlled.

#### Configuration item (CI). 
A configuration item is an aggregation of the hardware, software or both, that is designated for configuration management and treated as single entity in CM process. 

Document naming scheme must be defined so that related documents might have related names

A *Hierarchical scheme* with multilevel names is the one that is used more frequently to control and manage the CI. 
#### types of configuration objects
to manage SCI(software configuration Item) they must be separately named & organised using Object Oriented approach. 
- **base object** 
	- a base object is the *unit of text* that has been created by a software engineer during analysis, code, design or test
	- *ex.*
		- section of a requirement specification. 
		- a source listing for a component. 
		- a suite of test cases that are used to exercise code. 
- **aggregate object**
	- collection of base objects & other aggregate objects. 
	- *ex.*
		- design specification is an aggregate object which comprises Data design, Architectural design, module design, interface design. 


#### relationship b/w configuration objects
- curved arrow indicates a *compositional relation*. 
- double-headed straight arrow indicates an *interrelationship*
- ![[attachments/Pasted image 20230922163048.png]]
- Design specification is an *aggregate object* which comprises data design, architectural design, module design, interface design, data model & component
- and have compositional relation with the design specification & are thus indicated by *curved arrow*. 
- *double headed arrow* between source code, component test specification and design specification.
- Specifies the interrelationships if a change were made to the source. 

### Baseline 
specification or product that has been formally reviewed and agreed upon, that thereafter serves as the basis for further development, and that can be changed only through formal change control procedures. 
### Evolution graph
describes the change history of an object. 


### configuration repository
all the CI(configuration items) are stored 
centralized repository 


### checkin & checkout
configuration items available in the configuration management system will be in read only be default.

**checkin** is an operation used to make a developer's object version available to other users.
**checkout** process that creates a new version of an object from an existing version stored in the database. 

developers check out objects so they can work on them. 


### change management 
change management is the process during which the changes of a system are implemented in a controlled manner by following a predefined framework/model with some reasonable modifications. 

#### Activities in change management 
- filtering changes. 
- managing changes and the change process. 
- reviewing and closing of requests for change (RFCs).
- management reporting & providing management information. 



### synchronization control 
- so that change should not overwrite. 
- sync. control is mechanism of configuration management. 
- It ensures parallel changes performed by two different people don't overwrite by two different people done't overwrite one another. 
- the user can obtain a lock on the object in the database. 
	- This will disable other users for accessing or updating that object until the currently checked out  version has been replaced. 
	- thereby releasing the lock. 


### change control board (CCB)
- client may come up with changes 
- changes cannot be directly reported to concernd person in the developement team. 
- Its impact will be in all phases. 
- All changes sent through the Change control board CCB or the software change control board SCCB. 
- it is a committee that accepts the change requests, analyzes 
- takes decision whether or not the proposed to a software project should be implemented. 
- If accepted the code will be given to the dev to make the relevant changes. 

#### phases of CCB
- evaluation 
- resolution 
- verification. 
- when a change is made it is then evaluated by CCB. they analyze the impact of change and cost. 


### version management 
- to tackle the frequent changes 
- version control mechanism can be used to maintain multiple versions of a software project or files or documents. 
- it allow user
	- to lock file so they can only edited by one person. (*forcing serialized change to any given file*)
	- track changes to file
	- to instant recall of any work from any point in time. 
- maintain instant audit rail on each & every file. 


#### adv
- automatic backup is the main advantage 
- can be rolled back to previous versions
- comparison b/w two files is possible.
- 




## [[test configuration]]