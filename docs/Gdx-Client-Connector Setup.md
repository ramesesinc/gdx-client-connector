# GDX-CLIENT-CONNECTOR

## Installation and Configuration

1. Browse to the folder your SERVERS are installed, e.g., c:\SERVERS

2. Open Git Bash on the SERVERS folder. Enter the command to clone the 
   gdx-client-connector repository

   $ git clone https://github.com/ramesesinc/gdx-client-connector.git 

3. After successfully cloning the repository, configure gdx-client:

    3.1    Browse to "gdx-client-connector" folder.

    3.2.   Unzip "custom-template.tar.gz" file. 
           When using WinRAR, be sure to select the "Extract Here" option.

    3.3.   Edit "bin/env.conf" file and set the following:

            * Replace channel value of "00000" with the LGU index number

                channel=00000   

            * Replace app_server_ip value of "192.168.1.25" with the IP address of the server

                app_server_ip=192.168.1.25

    3.4.    Save the changes.

4.  Create Shortcut
    
    4.1 Right-click "bin/run.bat", select Send to Desktop (Create Shortcut) option.
        Rename the shortcut to START-GDX.bat

    4.2 Right-click "bin/shutdown.bat", select Send to Desktop (Create Shortcut) option.
        Rename the shortcut to STOP-GDX.bat

5. Double click START-GDX shortcut to run the server.
   Verify that there are no errors in the server console.



