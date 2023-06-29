# Networking

Networking is the process through which computers exchange information globally. It follows a layered architecture known as the Open Systems Interconnection (OSI) model, which consists of seven layers.

At the lowest layer, we have physical hardware such as fiber optic cables that transmit data in the form of light signals between two points. These light signals propagate all the way up to the **application layer (layer 7)**, where they are transformed into pixels on a screen or vibrations from a speaker, directly perceived by the end user. This communication is achieved using protocols like the Hypertext Transfer Protocol (HTTP), which is just one example among many others at the application layer (Layer 7).

![OSI](https://github.com/hemanthravishankar/Learning/blob/f8b1f57c35c5522d5bf26d1ed0b4e232e6550da5/Screenshot%202023-06-29%20at%209.00.39%20AM.png)

Now, let's delve into the layers in reverse order to understand their functions in more detail. **Layer 6 is the presentation layer**, responsible for translating data streams from computers, like a JPEG image, into a standardized format usable by the application layer. It ensures compatibility and proper interpretation of data.

Beneath the presentation layer is the **session layer (Layer 5)** , which manages connections between two computers. It handles crucial tasks such as user authentication and authorization, controlling access to data on servers. Instances of unauthorized access, like when an unknown person joins a Zoom call and shares unsolicited content, can exploit vulnerabilities at this layer.

Moving further down the stack, we encounter the **transport layer (Layer 4)**, where the Transmission Control Protocol (TCP) plays a fundamental role. TCP facilitates the reliable transfer of data streams between computers. It segments data into smaller units, known as packets, and ensures they are correctly ordered when transmitted over the network.

The **network layer (Layer 3)** is where the Internet Protocol (IP) operates. Each computer connected to a network possesses a unique IP address that identifies it. Whenever information is sent across the network, it is encapsulated in an IP packet that contains the source and destination IP addresses. Routers and gateways, operating at this layer, facilitate the routing of packets between different networks.

Below the network layer, we have the **data link layer (Layer 2)**, responsible for connecting physical nodes within a network. Protocols such as Ethernet and Wi-Fi operate at this layer, enabling the transmission of data between nodes.

Finally, we reach the **physical layer (Layer 1)**, consisting of the actual physical infrastructure like cables and connectors. It provides the means for transmitting data in the form of electrical or light signals.

This intricate layering and interplay of protocols and technologies enable the seamless sharing of over 2.5 quintillion bytes of data across the world every single day.

[Short video on Networking](https://youtu.be/keeqnciDVOo)
