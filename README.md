# EX 5: METASPLOIT FOR RECONNAISSANCE
## Metasploit
Metasploit for reconnaissance in pentesting
```
Register Number: 212222040095
Name: Mahisha S
```

## AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

### EXECUTION STEPS AND ITS OUTPUT:
### Step 1: Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.
![Screenshot 2025-04-23 180046](https://github.com/user-attachments/assets/91914541-a505-4d69-8c11-84bdf5afe225)




### Step 2: Launch the Metasploit Console
Invoke the msfconsole.
![Screenshot 2025-04-23 180141](https://github.com/user-attachments/assets/20e42f09-5186-4a83-a652-b41949816c55)


To view available commands, enter "?".
![Screenshot 2025-04-23 180210](https://github.com/user-attachments/assets/4abd5ea2-24ca-43db-aafa-2026c0730e36)


### Step 3: Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.
![Screenshot 2025-04-23 180641](https://github.com/user-attachments/assets/73c9b3ab-cd74-4f2d-b96b-fea10cf226b5)



### Step 4: Set Up an HTTP Server
Once the payload file is created, navigate to the home directory. Right-click and select "Open Terminal Here."
![Screenshot 2025-04-23 180706](https://github.com/user-attachments/assets/ea612a62-07c8-4ab9-a36b-62c6d560fe13)


Run the Python command to establish an HTTP server for file distribution.
![Screenshot 2025-04-23 180813](https://github.com/user-attachments/assets/acdd015a-c895-404a-81ed-b42834674a9f)



### Step 5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.
Once the victim downloads and executes the file, the exploit is triggered.
#### VICTIM DEVICE:
![Screenshot 2025-04-23 181424](https://github.com/user-attachments/assets/3a8c125d-5a8d-41c4-a5bd-e8456ef873b6)

![Screenshot 2025-04-23 181449](https://github.com/user-attachments/assets/9929b876-f091-4152-8e35-ead5a6939dc7)



### Step 6: Establish a Connection
On Kali Linux, reopen the terminal and invoke msfconsole.
Follow the necessary steps to establish a connection with the victim’s device.

![Screenshot 2025-04-23 182853](https://github.com/user-attachments/assets/dcf9c2e4-8bf3-4ea1-b23c-287b5beaa6ea)


Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step 7: Execute Commands on the Victim’s Device
Use the help command to list available operations.
![Screenshot 2025-04-23 182919](https://github.com/user-attachments/assets/ef7f07cf-b80e-4a3b-ae68-6e29512b3f81)



### Step 8: Terminate the Connection
For example, the screenshot command captures the victim’s screen and saves it in the attacker's home directory.
![image](https://github.com/user-attachments/assets/5dd5faf8-b4bb-472b-9d96-748d2023b771)


![Screenshot 2025-04-23 182919](https://github.com/user-attachments/assets/065c49d8-ae40-4266-a086-df8cd23cf92b)


### Step 9: Terminate the connection
After completing intended operations, close the session securely.



## RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
