##  Voting App Kubernetes

This is a simple distributed application running across multiple Docker containers.

A front-end web app in Python which lets you vote between two options
A Redis which collects new votes
A .NET worker which consumes votes and stores them in…
A Postgres database backed by a Docker volume
A Node.js web app which shows the results of the voting in real time.


The voting application only accepts one vote per client browser. It does not register additional votes if a vote has already been submitted from a client.


