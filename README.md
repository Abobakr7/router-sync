## Synchronization
It is required to simulate a limited number of devices connected to a router's Wi-Fi using Java threading and semaphore. Routers can be designed to limit the number of open connections.
For example, aa router may wish to have only N connections at any point in time. As soon as N connections are made, the Router will not accept other incoming connections until an existing
connection is released.

#### Following rules should be applied
- The Wi-Fi number of connected devices is initially empty.
- If a client is logged in (print a message that the client is logged in) and if it can be served (means that it can reach the internet) then the client should perform online activity (these actions will be represented by printed messages)
- If a client arrives and all connections are occupied, it must wait until one of the currently available client finish his service and leave.
- After a client finishes his service, he leave and one the waiting client (if exist) will connect to the internet.

#### input example
`=` represents the program output
=What is the maximum number of connections the router can accepts?
2
=How many number of devices wish to connect?
4
C1 mobile
C2 tablet
C3 pc
C4 laptop

** This project was part of an assignment for college course on Operating Systems
