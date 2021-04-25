In this zip/folder you should see 9 files:
-Readme.txt
-DV-Functions.c
-neighbors1.txt
-neighbors2.txt
-neighbors3.txt
-neighbors4.txt
-neighbors5.txt
-vectors.txt
-makefile
-DV-functions(a unix executable)

The server will utilize multiple instances using the distance vector algorithm to find the quickest and most efficient way from point to point located within the vectors.txt file.  You can jump around what ever neighbors file table you would like since this project's whole premise is based off of that using the distance vector algorithm.

To compile the server first you will need to compile the program.  
Next, you will want to cd into those directory where DV-Functions.c is located.

Enter the following to compile the code:
gcc -o DV-Functions DV-Functions.c

Next in the terminal, once both have been compiled and there are no errors you will want to run the server in the same directories, using the following command 
Server:./DV-Functions

After running the server, you will want to make your commands:  

There are 3 commands in this project:
1)print --> This will print the current table with the all the vectors

2)refresh--> This will refresh and send changes to neighboring table. This will act as a failsafe to make sure the correct information is sent to each of the neighbors table

3)update--> This will update the cost of the fromNode and toNode and makes sure that the fromNode is the current node until it is transferred to the toNode.

The commands are case sensitive please follow them verbatim as listed in the Readme.txt

HAPPY Vectoring! 