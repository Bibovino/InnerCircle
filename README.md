# InnerCircle
Coffee Request Interface for shared coworking space, cube farms or general offices.

The InnerCircle can consist of multiple nodes and a base, which are connected over WiFi. The base acts as a Hotspot, enabling the nodes in range to connect, send and receive requests. Each node can display the status of up to 12 selected nodes in the same network. The nodes are selected in a webinterface and allow the configuration of each node. A user can send requests for coffee-breaks or spontaneuos meetings by selecting a led on the circular PCB. The request is displayed on the corresponding node, if the involved user has the requesting user in his inner circle.

The node consists of a PCB, a small microcontroller and a GPIO-Multiplexer. On the board are multiple RGB-Leds, which are Daidychained into a circle. The input for each LED is registered by a voltage drop over selected traces on the pcb.
