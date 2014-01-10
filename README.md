M7011E_Dynamic_web_system
=========================

School project for the course M7011E at Luleå technical University, Sweden.

#Requirements
	MongoDB
	Nodejs
	npm

#Nodejs module dependencies

	express

	fs

	ejs

	passport

	passport-google

	mongoose

	crypto

#Installing node modules
```console
npm install *module*
```

#Other files required
```console
workspace/dbsalt.dontsave
workspace/sessionsalt.dontsave
```
These need to look like: 
```json
{ "secret" : "supersecretsalt"}
```
Where `"supersecretsalt"` can be a string of your choice

#Running the application
in the console, go to the place where the application has been downloaded to and run
```console
nodejs workspace/base.js
```
'nodejs' can be changed if node is bound to another command