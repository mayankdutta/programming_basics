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
	- *alpha testing  :* done by the client in dev's environment.
	- *beta testing :* done by client in real world environment.


### types of testing techniques. 
#### static testing

code & associated documents are observed & tested manually.
execution of code is not performed, only sanity of the code is checked. 

- **review :** product is re-examined & re-evaluated for possible corrections. 
- **walkthrough :** done on deployed code by *author*, author gives sample data, code results get recorded. 
- **inspection :** done bye *quality improvement team*. step by step reading of the product, each step has criterias. 

![[attachments/Pasted image 20230918031525.png]]

during planning people ar eidentified and the roles are assigned to each of the identified person identifyng the entry and exit criteria. 
during initiating the document to be reviewed is distributed nad the objectvives are explained
verifying the entry criteria self preparation. 
individual work is done by each of the participants on their won, marking the questions and the comments recording the results, rework the effect of fixing. & if any follow up.
##### members of static testing 
- **author :** writer of the document under review. 
- **moderator :** one who leads the review process. 
- **reader :** who presents the document. 
- **recorder/scribe :** records each defect found & any suggestions or feedback given in the meeting. 
- **inspector :** responsible for inspecting document.

##### types of reviews 
- **informal review**  peer programmer or tech lead will review the code. 
- **walkthrough** led by author, again informal meeting. author reads the document and his team mates comes up with suggestions or defects. 
- **technical review** team of experts examine technical quality of the artifact & identifies the discrepancies from specs and standards. 
- **inspection** led by trained moderator who is not the author, most formal & driven by rules. makes use of entry & exit criteria. Inspection report is prepared & shared with the author
#### dynamic testing
- **black box testing**
	- functionality of software is tested without knowledge of internal implementation of code. 
	- tester will know the expected output and input. 
	- also known as specification based testing. 
	- **techniques for generating TC in black box**
		- *equivalence class partitioning* 
			- choose 3 values as test data one above range, one below range, one in the range.
		- *boundary value analysis* 
			- test cases are designed to find errors at boundary value. 
			- test cases will be exactly the lower limit, upper limit, a value just below lower limit & value just above upper limit. 
		- *cause effect analysis* 
			- helps in identifying the causes and their effect associated with a particular problem or situation.
			- A cause is an input condition or an equivalence class of input condition. 
			- Effect is an output condition or a system transformation. 
			- suitable for application in which combinations of input conditions are few.
		- *error guessing* 
			- ad hoc approach guided by intuition & experience. 
			- consider a program is written into a file, following TCes can be derivd. 
				- having an empty file. 
				- not at all having a file. 
				- having a file with read permission. 
- **white box testing**
	- also called glass box testing, structural testing or clear box testing. 
	- use to check internal logic of code. 
	- tester should have thorough knowledge of programming, language. 
	- **[[Basis path testing]]**

![[attachments/Pasted image 20230918174832.png]]

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