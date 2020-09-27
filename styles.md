# Grant Zeigler - Architectural styles

### Monolithic Application
With this one, the application performs every step necessary, and does not rely on any other application to do any work.
The purpose of this is to make a program that is requried to not have any dependencies, such as a finance program that does every step of the process.
One constraint of this is that it is not modular. There are no connectors, since it is all in one. The only component is the single main part of the program, which has no dependencies.

### Rule-Based System
This type of system uses data from a user as well as a shared database to do stuff. One example is a program that helps doctors decide on treatment based on the symptoms that they provide.

Components:

* Rule Base - specific type of knowledge base
* Inference Engine - gives an output based on the input data and the rule base
* Working Memory
* User Interface

  
Wikipedia contributors, "Monolithic application," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Monolithic_application&oldid=978920400 (accessed September 27, 2020).

Wikipedia contributors, "Rule-based system," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Rule-based_system&oldid=977232707 (accessed September 27, 2020). 
