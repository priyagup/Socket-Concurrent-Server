# Socket-Concurrent-Server
Author: Priya Gupta
Socket Assignment 2 Fall 2018
L20444930

Step 1: Extract the folder and copied all the file to different system. 
		Make sure wordfile.txt should be present in the directory where the client is running because it is taking random words from that file.

Step 2: run server on pc1 with command : python server.py 5777
Note : There are two arguments ip and post, ports can be any but run everytime with different port becuase we might get already used port.


Step 3: run client on pc2 with command : python client.py *arg1* *arg2*
arg1 is ip of server where the server is running 
arg2 is port of server where the server is running 

eg: python client.py 127.0.0.1 5222

Note:  Input file that created one line at a time with the random word picked from wordfile and stored on client.inputdat file.

      
