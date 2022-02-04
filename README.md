# fastrestapi

Small protoboard with a REST API based on JSON-Server

## starting

Visualize how easy it is to mount a REST service with node's JSON-Server module. The idea was born when reading the following article:

* <https://medium.com/edgar-talledos/crea-un-api-rest-en-menos-de-30-segundos-con-json-server-406ffd08151d.>

### Code

Applying step by step what is proposed in this tutorial:  

* <https://zetcode.com/javascript/jsonserver/>  

#### How to do it?

In a new forlder, open the VSC and install the JSON Server module for Node.

If you do everything from scratch, the following ordered instructions as shown, are important for it to work!_ 

```text
npm init -y
npm i -g json-server
```

Now we install the AXIOS module. An http client that processes promises in requests to the server.

```text
npm install axios
```

The file package.json have the configuration for used this module.
The file users.json, have data for the practices. Note what the file name of data it’s same what in the command start server it’s put how a parameter.
Para ponerlo en marcha, desde la terminal de VSC escriba: 
To start it, from the VSC terminal, type:

```text
json-server --watch users.json
```

If everything is working fine, the terminal window will show a message with the URL address of this service, what are you waiting for our navigation... The port can by change, depending on the ports in use at your host.

* <http://localhost:3000/users>

* <http://localhost:3000/users/3>
