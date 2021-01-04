This is a multi-process and multi-threaded web server.

Works in the Linux environment.

"http-server.c" is the C source file for the Web Server. 
"index.html" is the default page of the server.
This server supports html,htm,png,jpg,jpeg,ico,gif,pdf  
"testd" is the directory. Files insides the directory are also accessible by the server.

Server is listening to the port 8080 

Compile using "gcc -pthread http-server.c -o httpserver" and run.
 
Then open the port 8080 with the browser. (http://localhost:8080)
