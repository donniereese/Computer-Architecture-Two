# Assignment Answers:

1. 12672ms?  that seems long, though. (1024kb / 4kb) * ((90 + 9) / 2) == blocks * average_seek_time

2. A TCP/IP Packet is the chunk that makes up almost all, if not all of the data on the internet.  It is trasmited on the transportation layer and is transmited from host to host, allowing connectivity. Due to the way packets are structured and the systems in place by the communication layer packets can be lost and resent without any interruption to the underlying application layer.
   The packet header is 32 bits long, or 8 bytes.
   Headers contain the source port, destination port, length and checksums.  They also contain sequence numbers, aknowledgement numbers, data offset and padding to keep the header the right size.
   It can contain varius flags that set data such as: reset the connection request, aknowledgment request, congestion info and urgent pointer info.  It can contain options such as: window size, max. segment size, timestamp, ect.
   Any data can come after the header as long as it fits in the packet size, including other connection information for the reciever.  The packet doens't care whats in it.

3. The TCP/IP uses checksums, correct header information and listed packet sizes to verify the packet was complete.  The reciever and the sender can communicate requests to resent packets in case packets are lost or incomplete.

4. TCP provides communication between two computers, controlling the size and rate of the flow of data.  It is the between application and the IP protocol.  The IP protocol's main concern is to route packets from one host to another host based on their IP address in the interconnected system.  It's the mail carrier that routes mail between cities based on the address and the mail sorting system at either end is like the TCP that decodes the bits of mail (packets) and makes sure they get to the recipient of the parcel.

5. In a graphics card, it's basically a computer.  However, it's performance is better because it is designed specifically for the task of processing the specific information that is used on a graphics cards.  It has many more processors with special instruction sets to handle shaders and algorithms to handle the special math required.  It has faster memory, attributed to the specially designed system and closeness and special design of the board.  IT also has special power requirements that are handled less generically as a normal cpu.  It also only processes these one tasks, not every other task that might be asked of it.  The limiting performance factors of a modern CPU would be how general purpose they have to be.  They also tackle much more varied information on a system and may be doing different tasks that have nothing to do with one another.  Also, a normal CPU has to cope with the modularness of a modern system.


