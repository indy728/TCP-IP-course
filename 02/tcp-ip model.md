# The TCP/IP model
## Origins of the TCP/IP Model
- 1989: RFC1122 was published
- RFC1122 is a request for comment that specified an architectural model for communications between internet hosts
- Layers were only referred to by name, no numbering
## Link Layer / Network Access Layer
- Physical connection
- Handles error correction and control on the physical medium
- Specifies how messages are translated onto the physical medium
## Internet Layer
- IP, ICMP intended for this layer
- Robustness Principle applies here
- Rubustness Principle: "Be liberal in what you accept an conservative in what you send"
- Specifies processing rules to ensure datagrams end up where they are supposed to 
## Transport Layer
- TCP and UDP are Transport Layer protocols
- handle end-to-end delivery
- UDP doesn't care whether packets of data arrive or not
- TCP handles connection-oriented comms
- TCP guarantees delivery and makes sure there is an entity at the other end to receive packets
## Application Layer
- All application functionality
- Session management
- Presentation
- API's