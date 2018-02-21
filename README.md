# camel
Experimenting with Apache Camel

Camel is an implementation of the Mediator pattern (encapsulating logic for how components interact) supporting many kinds of communication protocols.
Internally it implements all of the Enterprise Integration Patterns.

Key components of Camel and Enterprise Integration Patterns:

Message - metadata and payload
Exchange - incoming and outgoing
Endpoint - a way to connect to a messaging channel
Channel - how applications communicate with each other - often implemented through a message queue
Pipes and Filters - a way to separate concerns when components interact with each other - core to camel and implementation of routing rules.

