# Demo guide

## Dispatch a drone to deliver a packet
colonies function submit --spec deliver_process.json 
colonies function exec --func deliver --args "lulea" --targettype drone 

## Instructions
cd server
./start_server.sh
http://localhost:1111/drone/drone.html
http://approver:1111/approver/approver.html
