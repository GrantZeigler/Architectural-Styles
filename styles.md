# Grant Zeigler - Architectural styles

### Monolithic Application
With this one, the application performs every step necessary, and does not rely on any other application to do any work.
The purpose of this is to make a program that is requried to not have any dependencies, such as a finance program that does every step of the process.
One constraint of this is that it is not modular. There are no connectors, since it is all in one. The only component is the single main part of the program, which has no dependencies.

![](https://yuml.me/6edcfad3.jpg)

### Rule-Based System
This type of system uses data from a user as well as a shared database to do stuff. One example is a program that helps doctors decide on treatment based on the symptoms that they provide.

Components:
* Rule Base - specific type of knowledge base
* Inference Engine - gives an output based on the input data and the rule base
* Working Memory
* User Interface

Conectors:
* Connection between user input and the program
* Connection between rule base, inference engine, and user's input

Constraints:
* The rule base may not have enough data to make a good decision

![](https://yuml.me/13bcc337.jpg)


### Object Request Broker
This type of system acts as a middle man between two computers. This allows program calls to be made between two systems over a network.

Components:
* Connections between the two
* Working Memory
* Interface Description Language - describes the data that is being transfered in its own language

Connectors:
* Connection to the computer that is calling a function
* Connection to the computer that has the function  

Constraints:
* Only can be used to connect machines over a network

![](https://yuml.me/d3f4e0c0.jpg)

### Event-Driven Architecture
This type of system revolves around "events", which happen whenever some sort of data's state is changed. The system deals with production, detection, consumption of, and reaction to events. Events do not travel, they just happen and have to be detected by the program.

Components:
* Events
* Data that events can happen to 
* Event detector
* Event processor
* Data updater

Connectors:
* Connection between database detector
* Connection between processor, updater, and database

Constraints:
* Can only do operations when events happen

![](https://yuml.me/b0646122.jpg)

## Citations: 
  
Wikipedia contributors, "Monolithic application," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Monolithic_application&oldid=978920400 (accessed September 27, 2020).

Wikipedia contributors, "Rule-based system," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Rule-based_system&oldid=977232707 (accessed September 27, 2020). 

Wikipedia contributors, "Object request broker," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Object_request_broker&oldid=964664449 (accessed September 27, 2020). 

Wikipedia contributors, "Event-driven architecture," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Event-driven_architecture&oldid=968864303 (accessed September 27, 2020). 
