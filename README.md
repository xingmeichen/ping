# ping
Learn about Netty and try to implement something

## About how to run echo demo
1. go to ping directory, and execute command  
   mvn clean package  
   Then there should be server and client jar package in their respective target directories

2. open a terminal window, go to server directory, and execute command  
   mvn exec:java -Dexec.args="9001"  
   9001 represent port   
   Then the server is started, it can receive message now.
   
3. open another terminal window, go to client directory, and execute command   
   mvn exec:java -Dexec.args="localhost 9001"  
   localhost: host   
   9001: port   
   Then the client will send a message to the server once, and then it closes.
   
## TODO
