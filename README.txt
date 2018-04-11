Follow the following instructions to run the web service:

1. C:\node>npm install -g express-generator     // here node is the root folder where you install the zip file //
2. C:\node\nodetest2>npm install
3. C:\node\nodetest2>npm start
4. // In new command prompt window // "C:\Program Files\MongoDB\Server\3.2\bin\mongod.exe" --dbpath c:\node\nodetest2\data\
   // I have a 32-bit machine, please change the MongoDB version as per your machine; latest is 3.6 //
5. // In new command prompt //  "C:\Program Files\MongoDB\Server\3.2\bin\mongo.exe" and close it
6. // Ctrl-C to kill command prompt in step 3 at  C:\node\nodetest2\ and again start using // >npm start
7. Go to http://localhost:3000/  to see the web service running with a basic UI

The web service will let you add, delete users and also see their specific details.
If a user is already present with the same username then it will give you an error.