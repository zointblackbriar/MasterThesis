# MasterThesis
The Master Thesis, Research Paper, Literature Review and Thesis Presentation

# Abstract

Industry 4.0 has changed demands in terms of smart factories that promote practices in manufacturing. In this context, 
smart factories have been created connected streaming data from production systems, which is hard to interpret even by experts. 
Moreover, various smart factories and conneted devices have developed a communication environment between devices and a production system 
so that a standardized communication shaped to solve the interoperability issue.

The OPC Unified Architecture works according to the server-client principle through which a server usually represents one or more 
machines with static and dynamic data models. Hence, this information model is not standardized,; the internal structure can be changed
individually for each server implementation. As a result, querying hierarchical structure of data or continuous data requires knowledge
of the internal structure of manufacturing devices.

The service set of the OPC UA allows loading, querying, and editing the data model, but relationships between nodes cannot be interpreted.
This lack of semantic is recognized as one of the current challenges in "OPC Unified Architecture Pioneer of 3th Industrial (R) Evolution".

The goal of this thesis is to create a web-bsed application which is capable of loading, browsing and editing internal structures with 
regard to OPC UA Protocol to interpret relationship between nodes and to implement a semantic question answering connected to a semantic data platform
(eniLINK) and the Dynamic Server. By doing so, this work provides an implementation to a human operator or experts using the system with limited
knowledge of the innter OPC UA data model. In terms of semantic question answering, main keywords which reside in Enilink Platform might
be known to exploit semantic question answering, e.g. "linkedfactory" or "fofab". In order to connect with the linked data, a semantic question
answering system performs on a different layer of the web application and comparing it to other solutions currently exist in the market. A
semantic question answering provides information for an end-user, a human operator or an expert with natural questions converting into SPARQL in order
to use linked data source of Fraunhofer IWU.

In the practical part of this thesis assessed the state-of-the-art toolkits and frameworks that are planning to use for implementation. To
provide best integration of the question answering and OPC UA web service, front-end and back-end technologies have been assessed with
regard to the interoperability, scalability, loosely-coupling and synchronous/asynchronous development. The semantic question answering
system is integrated into main web server software that can use linked data sources created by servers using OPC UA Protocol or streaming
data source created by Fraunhofer IWU.


