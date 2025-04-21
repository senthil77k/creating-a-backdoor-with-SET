# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212223220103
Name: SENTHIL KUMARAN C
```
## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![Screenshot 2025-04-21 105239](https://github.com/user-attachments/assets/66ea94cb-7b4a-44d4-9977-4ad62cd34745)



sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-04-21 110931](https://github.com/user-attachments/assets/fd85557e-a5fb-4380-b65e-e089cc7929ee)




The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/0813516c-1a21-48ab-940b-1496b0b60737)





The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/015c4b2d-e1f9-44e4-8a69-6196b2d670fc)





It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/aa271541-d765-469f-b98d-4e4b6a134197)



It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/7b9312fb-74b9-433c-9744-7aee5dc05965)





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/d4bfe216-cd6a-4d22-b5e7-c1748f9e3636)





In windows IE, on giving the url http://192.168.1.4, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/user-attachments/assets/dbad4d06-9ca3-4b72-b030-9c37c3f0f59f)



SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/d4e10845-1a69-41f3-92a5-0bd2d2870b42)




SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/eb860581-4b9f-4923-b762-13423fb56ee0)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
