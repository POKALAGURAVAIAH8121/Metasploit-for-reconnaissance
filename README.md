# Ex-05_Metasploit_for_ressiance
Metasploit for reconnaissance in pentesting
# Aim :
To get introduced to Metasploit Framework and to perform reconnaissance in pentesting.

# Design Steps: 
1. Install kali linux either in partition or virtual box or in live mode.
2. Investigate on the various categories of tools as follows.
3. Open terminal and try execute kali linux commands.

# Execution Steps and it's Output:
## Step1: Identify the Attacker's IP Address
Determine the IP address of the attacker's system.

<img width="476" alt="image" src="https://github.com/user-attachments/assets/7c0f7081-c928-4614-9e47-9bf4321d6c38" />

## Step2:Launch the Metasploit Console
Invoke the msfconsole

<img width="473" alt="image" src="https://github.com/user-attachments/assets/7b40ab0a-ed4e-4457-abcb-64cb5c281261" />

## Step3:Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.exe 

<img width="472" alt="image" src="https://github.com/user-attachments/assets/b0a27d36-ccfb-4f79-a9a5-33a8355c30ba" />

## Step4: SetUp an HTTP Server
Once the payload file is created, navigate to the hime directory.Right-click and select "open terminal here"

<img width="472" alt="image" src="https://github.com/user-attachments/assets/5569aea4-2d03-44a9-b084-9f90a1808841" />


Run the Python command to establish an HTTP server  for file distribution.

<img width="472" alt="image" src="https://github.com/user-attachments/assets/cafd9380-110f-4b95-9bbb-529260847e34" />

## Step5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server. Once the victim downloads and executes the file,the exploit is triggered.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/afb0348b-b97b-4cfb-afbd-46c8ef0f42ca" />

## Step6: Establish a Connection
On Kali linux, reopen the terminal and invoke "msfconsole".Follow the necessary steps to establish a connection with the victim's device.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/123debe7-9cd0-4ccd-897c-e064ed3cfa7d" />

## Step7:List Commands
Use the help command to list available operations.

<img width="473" alt="image" src="https://github.com/user-attachments/assets/6e31ca21-f0f7-4ab9-b4ab-887d5a77dae0" />





## Step8:
For example,the "webcam_stream" command captures the victim's webcam and saves it in the attacker's home directory.

<img width="473" alt="image" src="https://github.com/user-attachments/assets/6b3b0f75-9bb0-4c96-9211-3a2bd6bae4cf" />



## Step9:Terminate the Connection
After completing the intended operations, close the session securly.
## Result: 
The Metasploit framework for reconnaissance is examined successfully.











