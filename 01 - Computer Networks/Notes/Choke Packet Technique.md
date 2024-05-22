It is a technique :-
- which is **applicable** to **both** ==virtual networks== as well as ==datagram subnets==.
- A **choke packet** is a *packet sent by* a *node* to the *source* to *inform it* of *congestion*.
- Each router monitors its resources and the utilization at each of its output lines.
- Whenever the resource utilization exceeds the threshold value which is set by the administrator,
	- the router directly sends a choke packet to the source giving it a feedback to reduce the traffic.
	- The intermediate nodes through which the packets has travelled are not warned about congestion.

![[Pasted image 20231121044622.png]]
