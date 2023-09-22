#### black box testing
- functionality of software is tested without knowledge of internal implementation of code. 
- also known as specification based testing. 
- tester will know the expected output and input. 
- **techniques for generating TC in black box**
	- *equivalence class partitioning* 
		- choose 3 values as test data one above range, one below range, one in the range.
	- *boundary value analysis* 
		- test cases are designed to find errors at boundary value. 
		- test cases will be exactly the lower limit, upper limit, a value just below lower limit & value just above upper limit. 
	- *cause effect analysis & graphing* 
		- helps in identifying the causes and their effect associated with a particular problem or situation.
		- A cause is an input condition or an equivalence class of input condition. 
		- Effect is an output condition or a system transformation. 
		- suitable for application in which combinations of input conditions are few.
	- *error guessing* 
		- ad hoc approach guided by intuition & experience. 
		- consider a program is written into a file, following TCes can be derived. 
			- having an empty file. 
			- not at all having a file. 
			- having a file with read permission. 

#### white box testing
- also called glass box testing, structural testing or clear box testing. 
- use to check internal logic of code. 
- tester should have thorough knowledge of programming, language. 
- **[[Basis path testing]]**

![[attachments/Pasted image 20230918174832.png]]