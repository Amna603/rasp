# Raspberry code


![image](https://user-images.githubusercontent.com/60341858/166672193-b5ecf6ab-4041-4c86-a371-efe8a0f13f94.png)


This is the code implemented in the Raspberry board.

We are connected to the Arduino board by serial connection on port 9600 and by socket 8669. 

The decrypt function will decode the string payloads received and use the data to implement in a [x,y] vector. 
This vector will be used in a while loop to send command data to the motors.  
