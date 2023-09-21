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