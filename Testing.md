- process of executing program with the intention of finding gaps and errors in the software. 
- process of detecting the differences between existing & required conditions & to evaluate features of the software. 
- used to find the presence of defects, but never their absence. 

Testers are the one who certifies the software product. 

### testing life cycle 
identifies the testing life cycle identifies what test activities. 
phases are 
- test plan 
- test design: test scripts are designed. 
- test execution: 
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
- [[unit]]
- [[integration]]
- [[system testing]]
- [[acceptance]]

### types of testing techniques. 
- ##### [[static testing]]
- ##### [[dynamic testing]]
- 
![[attachments/Pasted image 20230919031525.png]]



| static testing                                                                                                        | dynamic testing                                  |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| innvolves manula exmination of the work product to uncover erors                                                      | involves executing the code to check for errors. |
| can be done in all phases of the software, errors identified during this testing are easy to fix hence less expensive |                                                  |


#### when to stop testing
- when time allocated for testing has expired.
- run our of the resources like time, cost, manpower, tools. 
- rate of bug finding is minimum.
- deadline or the test deadline is met. 


### Debugging
- done by dev with the intention of analysing and removing the bug.
- steps 
	- find defect in the code. 
	- identify the root cause of the problem. 
	- identify exact place in the code that is the cause of the problem.
	- fix the detect. 
	- recheck to ensure that the defect fixed is working as expected. 