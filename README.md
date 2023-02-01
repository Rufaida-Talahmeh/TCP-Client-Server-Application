CLIENT
gcc Client.c -o client

./client [ServerIP] [PortNum] input.txt [SleepTime-in-ms]
----------------------------------------------------------

SERVER
gcc Server.c -o server

./server [PortNum]
