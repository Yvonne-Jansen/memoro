# memoro
A node.js server to collect MQTT messages and write them to an Influx database

## Requirements
- [Node.js](https://nodejs.org/en/download/)
- [InfluxDB installation](https://portal.influxdata.com/downloads/)
- MQTT broker installation, e.g., [Mosquitto](https://mosquitto.org/download/)

## Config
Edit the server.js file to indicate the IP address of your MQTT broker and your InfluxDB. The lines to edit are marked with an arrow -->

## Running the server
Start the server by running
```
node server.js 
```
Adding a number as argument to the call with use that number as the port to which the server listens, e.g., add 80 for a server to respond to port 80.
```
node server.js 80
```