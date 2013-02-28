README
This document details the implementation of a SQL interface for handling micro-
controllers. It uses the database open source SQLite which is made ??entirely in C 
that can be compiled for different platforms such as Linux, Windows, Solaris, 

Android and others. 
SQLite is designed to work with virtual tables is a communication interface for 
database with other data sources such as file structures or any XML file 
interpreter. For our project the data source is the micro-controller. This table is 
communicated by a serial port to the card via arduino mega Firmata generic protocol 
which is supported by a variety of micro-controllers.

 
Messages are sent in both directions to update the status of the table and the 
ports of the microprocessor.