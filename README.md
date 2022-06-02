# mongo_cluster
The project presents a script that allows you to configure MongoDB replica set using Docker.
***
To run the script, use the command:
```
sudo ./dbstart.sh
```
To connect to the MongoDB terminal, use the command:
```
sudo docker exec -it mongo1 mongo
```
***
## Notes
* MongoDB version: 4.4
* Container mongo1 runs on port 27021
* Container mongo2 runs on port 27022
* Container mongo3 runs on port 27023
