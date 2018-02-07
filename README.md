# StageLoca

This is a repository collecting my reports and other data about my work during my internship at IMT Atlantique for the [discovery initiative](https://beyondtheclouds.github.io/).


The internship is about making a middleware for a NewSQL database that will consider the locality of the client application.


Abstract:
A NewSQL database enables the scaling of an application as it also preserves the ACID properties required for the proper realisation of a transaction. To make this possible, the NewSQL database distributes its informations evenly across its nodes. It then uses a consensus algorithm to make the requests while keeping coherent transactions on the nodes. The goal of this internship is to change the way CockroachDB, a NewSQL database, distribute its entries. The main idea is to focus more on the closest node than at the whole system when doing requests.
