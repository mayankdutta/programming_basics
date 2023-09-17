- process of executing program with the intention of finding gaps and errors in the software. 
- process of detecting the differences between existing & required conditions & to evaluate features of the software. 
- used to find the presence of defects, but never their absence. 


Testers are the one who certifies the software product. 

### testing life cycle 
identifies the testing life cycle identifies what test activities. 
phases are 
- test plan 
- test design 
- test execution 
- report to dev
- verify 
- close 


### testing documentation 
tells how test should be performed. 
involves 
- resource allocation
- creation of test env. 
- test schedule 
- test functionality in test design.

![[attachments/Pasted image 20230918020047.png]]

Test scenarios. test cases, test data, test scripts are prepared. 
Test execution involves executing the test scripts and finding bugs. 
Bugs reported to dev, then regression testing is performed when its done the defect closed. 


#### levels of testing 
- unit
- integration
- system
- acceptance

#### unit
- individual components of software are tested to ensure that it works as expected. 
- done by dev 
- cost of fixing a defect detected during unit testing is lesser in comparison with higher levels. 


#### integration
- individual modules that are unit tested are then integrated to perform integration testing 
- done to reveal interface errors between modules. 
- components can be integrated in iterative way(one by one, *better*) or all at once(*big bang*).
- can be done by dev or tester. 


##### top down integration testing 
- testing is conducted from main module to sub-module. 
- first top level modules are tested and then the lower level units are tested. 
- if lower level modules are not ready, a dummy module(*stub*) is used instead. 


##### bottom up integration testing
- testing conducted from sub-module to main module.
- if top module is not ready then dummy module(*driver*) is used.

#### system testing 
- performed on complete integrated system from end to end perspective. 
- conducted by testers to find if any diff between implementation & specification.
- **unbiased system testing** involves testing both functional & non-functional requirements. 
- **functional testing** verifies that each function of the application works as per the requirement specification. 
- **non-functional testing** checks the performance, accessibility, reliability & other requirements as specified in document. 

#### performance testing
- **stress tests :** 
	- evaluates the system when stressed to its limits. 
	- aim is to test the system with the max to ensure it doesn't crash. 
- **regression tests :** 
	- required when system being tested is replacing an existing system.
	- replacement because of defect fixing & rectifying the defect. 
	- or enhancement of original system. 
- **usability tests :** 
	- testing characteristics related to user friendliness. 
	- done by user perspective. 
	- easy to understandable and use. 
- **Acceptance testing :**
	- done by client to check if system is meeting the specific requirements. 
	- confirm if system is as per user's requirement & certify it is acceptable for delivery to the customer. 

##### alpha testing (accptance testing)
- done by the client in dev's environment 