"# Learning-Switch" 

Implemention of the core functionalities of an Ethernet learning switch using the Switchyard framework. An Ethernet switch is a layer 2 device that uses packet switching to receive, process and forward frames to other devices (end hosts, other switches) in the network. A switch has a set of interfaces (ports) through which it sends/receives Ethernet frames. When Ethernet frames arrive on any port, the switch process the header of the frame to obtain information about the destination host. If the switch knows that the host is reachable through one of its ports, it sends out the frame from the appropriate output port. If it does not know where the host is, it floods the frame out of all ports except the input port.

myswitch_to.py: Your learning switch with timeout based entry removal
myswitch_lru.py: Your learning switch with LRU based entry removal
myswitch_traffic.py: Your learning switch with traffic volume based entry removal
