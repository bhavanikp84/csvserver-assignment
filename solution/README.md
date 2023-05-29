
docker run -d infracloudio/csvserver:latest

docke logs [containerid]

docker run -d -p 9393:9300 -e CSVSERVER_BORDER=Orange -v C:\Users\Bhavani_Vemuri\source\csvserver-assignment\solution\inputfile:/csvserver/inputdata infracloudio/csvserver:latest

docker exec -it [containerid] bash

netstat -tulpn