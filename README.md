# BB84-Protocol-Qkd-Simulation
### BB84, version 1(Without Noise)
* Generate raw key 
* Sift the key 
* Reduce Eve’s information on the new key (privacy amplification)
* Implement Eavesdropper attack
### TO DO LIST :
* Authenticate the messages on the classical channel
* Simulate noisy qubits and implement error correctiong codes
* Develop a new socket communication class 

###  Simulaqron 
SimulaQron is an application level simulator for a quantum internet that allows you to program your own quantum internet applications. Explore how to realize software for a quantum internet connecting local quantum processors by quantum communication, and develop your own libraries and software engineering concepts suitable for a quantum internet.
http://www.simulaqron.org/
![](https://d3i71xaburhd42.cloudfront.net/59a22ddee5a38458cbbf624091629ab3467954d3/4-Figure2-1.png)
### How to use ?
###### For linux :

* run.sh :Execute Alice and Bob without Eavesdropping , generate 1 bit key ----> `sh run.sh`
* run+Eve.sh : Execute Eve (Man in the middle attack) ------> `sh run+Eve.sh`
* n_run.sh : run the program n times (n=10) in order to obtain n_bit key -----> `bash n_run.sh`
