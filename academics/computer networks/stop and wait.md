- a [[flow control]] method to physically transmit [[frame]]s of data from one machine to another,
- implements a [[sliding window protocol]] with a window size of 1

- sender sends a frame and awaits an acknowledgement (ACK) from the receiver
- the time between sending a frame and it being received is a Transmission Delay (TD)
-  RTT = 2 * TD
- Time Out is 2 * RTT
- Time to live 2 * TD


#academic #comp_net 