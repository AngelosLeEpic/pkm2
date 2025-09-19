
- server and client agree on a window size less than or equal to half the [[sequence number]]
- The server sends all frames in the window

![[Pasted image 20250919141158.png]]
- If the client receives all frames, ACK
- If the cleint is missing a frame, it sends a NAK (Not Acknowledged) with the number of the first missing frame
- The server continues slides the window either to the NAKed frame or simply slides it to the next set of frames
#academic #comp_net #flowControl 