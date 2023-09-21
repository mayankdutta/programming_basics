#### Analysis 
- *analyst* is responsible for defining the requirements of the system without bothering about how these requirements will be built. 
- goal is to define requirement of the system. 
- SRS(*software requirement specification*) is the document prepare **after** the analysis phase. 

##### SRS
all possible *requirements* of the system to be developed are *captured & documented* in a document called SRS during design system design is prepared based on the SRS system. 

##### Activities in analysis phase. 
- business requirement is gathered & analysed by PMs and various stakeholders. 
	- how the system will be used. 
	- what input has to be given. 
	- what are the outputs. 
- preparation of SRS 
#### Design 
- Design focuses on identifying the architectures, screens, components and module interdependency. 
- software designs = 
  *transforming the customer requirements* -> *set of documents suitable for implementing in a programming language.*
- process of defining the architecture, interface, component & other characteristics of a system. 
- various designs artefacts can be there, such as 
	- functional hierarchy
	- diagrams
	-  screen layout diagrams
	- normalised tables
	- pseudocode. 

##### Levels of design 
- decompose the entire project into units/modules & identify the system architecture, data structure & processing logic. 
- DD (design document) = HLD + LLD
- **HLD :** focuses on 
	- what modules are required, 
	- what each module perform, 
	- how these modules communicate with each other. 
- **LLD :**  focuses on
	- writing a detailed algorithm
	- module design & data design 

#### Construction (code + unit testing) 
- modular & subsystem programming.
- unit testing to ensure functional requirements. 
- 

#### Testing 
- Testing is the process of executing the program with the intent of finding errors. 
- levels of testing
	- **Unit :** done by dev, individual module tested for functionality. 
	- **Integration :** to check the interface error b/w the integrated components.
	- **System :** whole system is check.
	- **Acceptance :** done by end-user for system acceptance. 

- software testing includes. 
	- *verification*  software meets its technical specification. ensures that we are doing the product right? 
	- *validation* software meets its customer/business requirements. ensures that we re doing the right product. 
	- *Defect* variance b/w expected & actual *result*.

#### Maintenance 
- Any change that is made to the software after it is deployed is known as its maintenance. 
- changes like enhancements, up-gradations.
