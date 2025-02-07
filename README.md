# Meshtastic IOT Network

Meshtastic is an open source firmware for microcontrollers that uses the LORAwan protocol to create private mesh networks.
the goal with this project is to use meshtastic to create a private network for IOT purposes. 



## base station
as most of these nodes that are going to connect to the network are low power,it is a good idea to have a very good, high power, infastructure to reach all the potential nodes in the area. 
### Design
initially i decided to go with a RAK 4631 per the recomendations of more experienced community menbers. however this is not the ideal solution going forward and i do intend to replace it. 
A RAK 4631 uses a nordic nRF52840 which is a very efficent chip and the circuit board impliments battery as well as solar capabilities which is ideal for remote installations however, it prioritises efficency so this is not a good system to make an infastructure node with. it is still better than no infastructure node so it will be used untill it is upgraded with one that has higher transmission power.  


//how do i add images?

#### test
