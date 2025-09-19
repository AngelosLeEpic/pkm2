- A method of transmitting frames much like [[stop and wait]] ARQ.
- The server (sender) selects a window size W, when describing a Go Back N protocol, if we say for example GB6, this means "Go Back N=6"
- The server sends N frames one after another and expects Acknowledgments for each
	![[Pasted image 20250919140757.png]]
- When the client receives a frame, it keeps it, but when it looses one, it ignores all following frames until the missing frame is resend.
- The server waits for acknowledgments on all previous frames before sending out the next window of frames

#academic #comp_net #flowControl