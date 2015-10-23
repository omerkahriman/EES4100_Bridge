# EES4100_Bridge
This project has been developed as part of the assessment for an undergraduate course in Victoria University.

This Application connects to a ModBus server and the reads
the registers. It also connects to a BACnet client where it reads
the client requests and if the request matches the device ID and
the instance number then it will remove the ModBus data from the
head of the linked list and reply to the client with the data.
