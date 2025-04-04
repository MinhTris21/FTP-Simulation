![Screenshot 2025-03-06 080117](https://github.com/user-attachments/assets/e8fd404a-1bcc-48e5-8fb2-4b5c8804a493)TEAM 7 - SIMULATING FTP (FILE TRANSFER PROTOCOL) USING TCP SOCKET ON Windows Subsystem for Linux (WSL)

Open 2 WSL command promt to simulating Server and Client

`git clone https://github.com/MinhTris21/FTP-Simulation`
                
                RUNNING SERVER SIDE
                $cd FTP-Simulation
                $cd FTP-Server
                $chmod +x ftpserver
                $./ftpserver
                RUNNING CLIENT SIDE
                $cd FTP-Simulation
                $cd FTP-Client
                $chmod +x ftpclient              
                $./ftpclient 127.0.0.1
COMMAND EXAMPLES
1. USER ABCDEF	
2. PASS 123456
3. MKD /home/minhtris/FTP-Simulation/FTP-Client/DAYLACLIENT - CREATE THE FOLDER IF NOT EXIST
4. CWD /home/minhtris/FTP-Simulation/FTP-Client - CHANGE THE CURRENT WORKING PATH TO /home/minhtris/FTP-Simulation/FTP-Client
5. RMD /home/minhtris/FTP-Simulation/FTP-Client/DAYLACLIENT - DELETE THE FOLDER IF IT EXISTS
6. PWD - RETURN THE CURRENT WORKING PATH
7. RETR test.txt - SEND test.txt FROM THE SERVER TO CLIENT
8. STOR test.txt - STORE THE INFORMATION OF test.txt ON SERVER TERMINAL
9. LIST - LIST ALL FILES EXIST IN THE CURRENT WORKING PATH
10. ABOR - LOG OUT THE CURRENT WORKING SESSION
11. QUIT - CLOSE THE CONNECTION


