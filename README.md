This Aplication consists of two parts:
FIRST - an adaptive interface, that collects and validates users data via inputs and creates a formData object. API sends object to
SECOND part - local DB server, that can be downloaded (JSON server DB). Unpack the server and start it on your computer through "node server" command in your cmd.
The server collects data from API into DB JSON file, and sends the subscribers array to API. 

Good luck ;D

For this project I've used:
- ANGULAR as a frontend framework (page routing, reactive forms, deafult and custom validators, http client...)
- NODE js
- Express as a server framework (cors, lowDB)
