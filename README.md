# TeamSpeak3 server on Docker

Ubuntu 14.04 with TS3 Server.

https://hub.docker.com/r/neptooo/ts3/

## Create container

`docker run --name TS3 -d -p 9987:9987/udp -p 30033:30033 -p 10011:10011 -v {FOLDER}:/teamspeak3 neptooo/ts3:latest` 
