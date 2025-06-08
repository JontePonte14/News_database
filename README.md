To install write in the command prompt when in the src directionary.
   ```bash
   make all
   ```
To move the executables to the bin folder, write another command in the same directionary. (This also creates a bin folder if it doesn't exist).
   ```bash
   make install
   ```
Start the server first and input the a valid ports (for example 12345), then start the client and input localhost and the same valid port number as the server. Note this should be done in two seperate terminal windows
i.e 
   ```bash
   ./myServer 12345 #Start the server first the first terminal window
   ```
   ```bash
   ./myClient localhost 12345 #Start the client the second terminal window
   ```

The index for the memory database is 1 and for the on-disk 2. These are the index used when doing the command "CHANGE_DATABASE".
