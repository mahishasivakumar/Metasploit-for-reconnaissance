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
![Screenshot 2025-04-20 180657](https://github.com/user-attachments/assets/3cc0ca51-27ad-4f8d-a4d5-b8850a9e78c5)



### Step 2: Launch the Metasploit Console
Invoke the msfconsole.
![Screenshot 2025-04-20 180711](https://github.com/user-attachments/assets/b62b247e-5947-473f-8998-e165a4a374f6)

To view available commands, enter "?".
![Screenshot 2025-04-20 180729](https://github.com/user-attachments/assets/b37e28e1-4329-4798-baa1-183b431f6667)

### Step 3: Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.
![Screenshot 2025-04-20 180740](https://github.com/user-attachments/assets/1c2f2c6f-c0a2-4809-9431-1a8ed35a6777)


### Step 4: Set Up an HTTP Server
Once the payload file is created, navigate to the home directory. Right-click and select "Open Terminal Here."
![Screenshot 2025-04-20 180752](https://github.com/user-attachments/assets/ade33e0b-e0f8-44d8-94be-10fc158594d6)

Run the Python command to establish an HTTP server for file distribution.
![Screenshot 2025-04-20 180801](https://github.com/user-attachments/assets/d8d29079-66ba-4133-ad91-85fde6825af4)


### Step 5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.
Once the victim downloads and executes the file, the exploit is triggered.
#### VICTIM DEVICE:
![Screenshot 2025-04-20 180810](https://github.com/user-attachments/assets/af068e91-1f8d-46da-a39d-301bbb26ad63)
![Screenshot 2025-04-20 180818](https://github.com/user-attachments/assets/430cbc1d-8f21-49ff-973c-da636cc66781)


### Step 6: Establish a Connection
On Kali Linux, reopen the terminal and invoke msfconsole.
Follow the necessary steps to establish a connection with the victim’s device.

![Screenshot 2025-04-20 180840](https://github.com/user-attachments/assets/1a57d5cb-4aa4-4ea1-8737-b5194d25963e)

Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step 7: Execute Commands on the Victim’s Device
Use the help command to list available operations.
![Screenshot 2025-04-20 180854](https://github.com/user-attachments/assets/d71861bd-2744-4b46-9349-46203cd92bb3)


### Step 8: Terminate the Connection
For example, the screenshot command captures the victim’s screen and saves it in the attacker's home directory.
![Screenshot 2025-04-20 180905](https://github.com/user-attachments/assets/547719b5-98a6-4971-8a55-c7d522571f31)

![Screenshot 2025-04-20 180913](https://github.com/user-attachments/assets/0027d562-d99b-4223-9b48-d25ad5a327e3)

### Step 9: Terminate the connection
After completing intended operations, close the session securely.



## RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
