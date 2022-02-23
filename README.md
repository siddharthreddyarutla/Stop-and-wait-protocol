# Stop-and-wait-protocol
The stop and wait protocol is a flow control protocol where flow control is one of the services of the data link layer. It is a data-link layer protocol which is used for transmitting the data over the noiseless channels.

# Detail

> The frame is sent one-by-one to the Receiver(Server) from the Sender(Client) side.<br>
> Acknowledgment is sent from Server to the Client.<br>
> The next frame is sent after receiving the acknowledgment from the server-side.<br>
>This technique/method is known to be STOP-and-WAIT Protocol.

# Stop-and-wait ARQ: 

1. Stop and Wait Protocol also referred to as alternating bit protocol, is a method in telecommunications to send information between two connected devices.<br>
2. It ensures that information is not lost due to dropped packets and that packets are received in the correct order. It is the simplest automatic repeat-request (ARQ) mechanism.<br>
3. A stop-and-wait ARQ sender sends one frame at a time; it is a special case of the general sliding window protocol with transmitting and receiving window sizes equal to one and greater than one respectively. <br>
4. After sending each frame, the sender doesn't send any further frames until it receives an acknowledgment (ACK) signal. <br>
5. After receiving a valid frame, the receiver sends an ACK. If the ACK does not reach the sender before a certain time, known as the timeout, the sender sends the same frame again. <br>
6. The timeout countdown is reset after each frame transmission.<br>
7. The above behavior is a basic example of Stop-and-Wait. <br>
8. However, real-life implementations vary to address certain issues of design.<br>
