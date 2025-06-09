VMWare Workstation Pro Install: Process may be a little difficult, so I've provided a video with instructions. </br> https://www.youtube.com/watch?v=agw2i6QddvE&t=26s&ab_channel=Memory

Ubuntu Live Server Install (Attacker): </br> https://ubuntu.com/download/server

Windows 10 Machine Install (Victim): Ensure you download the ISO file. </br> https://www.microsoft.com/en-us/software-download/windows10

Remove security defense from the Windows VM (Victim Machine):

Turning off Virus and Threat Protection
1. Press Windows Key + S and type Windows Security, then press Enter.
   
2. In the Windows Security window, click "Virus & threat protection" from the left menu.
   
3. Scroll down and click "Manage settings" under the Virus & threat protection settings section. </br>

![image](https://github.com/user-attachments/assets/02070e26-8035-4d20-b403-ac7ed8ff89b7)
4. Toggle the switch under "Real-time protection, Cloud-delivered protection, Automatic sample submission, and Tamper Protection" to Off. </br>

5. Toggle the switch under "Tamper Protection" to Off. </br>

6. You may be prompted by User Account Control (UAC)—click Yes to confirm.


-Group Policy Editor
-Disabling Power Configurations
-Safe Boot
-Registry Editing

Installing Sysmon on Windows VM

Installing LimaCharlie agent on Windows VM

Creating an organization on LimaCharlie
