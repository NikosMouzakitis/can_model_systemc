# can_model_systemc
can_model_systemc
![img](https://github.com/NikosMouzakitis/can_model_systemc/blob/main/img/a.png)


In this code is implemented a basic simulation of a Controller Area Network (CAN) bus system using SystemC. 
It models three CAN nodes (can_node) that compete for access to the shared bus (can_bus). 

Each node requests access to transmit data, and the bus arbiter grants access based on their ID. 

If a collision is detected (when multiple nodes request access simultaneously), 
the bus resolves it by selecting the node with the lowest ID. 
The nodes transmit messages (with unique IDs and data payloads) to the bus, which broadcasts the messages to all nodes.
