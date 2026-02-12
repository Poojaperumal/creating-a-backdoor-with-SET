# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

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
## OUTPUT



<img width="715" height="829" alt="image" src="https://github.com/user-attachments/assets/7eab76ba-c48e-4b19-80cf-6cf97bbcfe64" />




The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT






It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT


<img width="470" height="275" alt="image" src="https://github.com/user-attachments/assets/c98311a8-de98-49f8-a410-f8c4ec23c4d2" />





The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT


<img width="478" height="206" alt="image" src="https://github.com/user-attachments/assets/2ec2570f-8a0b-4b85-b8fb-5dbba8645131" />





<img width="431" height="144" alt="Screenshot 2026-02-12 140018" src="https://github.com/user-attachments/assets/07c6c30b-a18f-46fd-b449-bb6df8923eca" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT



<img width="663" height="345" alt="image" src="https://github.com/user-attachments/assets/166e2a97-b164-45d8-b0ed-2cbcbd9a1af0" />




It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="656" height="420" alt="image" src="https://github.com/user-attachments/assets/18da0810-8a46-44b3-a13a-654a828df910" />


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT




<img width="950" height="185" alt="Screenshot 2026-02-12 140359" src="https://github.com/user-attachments/assets/36ff730c-e845-499b-986c-ab72048fdc3c" />





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT


<img width="913" height="773" alt="325067549-7696ff89-b165-428e-92dc-051eda894e1d" src="https://github.com/user-attachments/assets/9e929a8e-9b75-42dd-83ec-401651504290" />



SET logs the information regarding the Google credentials:
## OUTPUT


<img width="1697" height="743" alt="325067567-82d08f2c-fcb4-4547-980d-d378a94a802c" src="https://github.com/user-attachments/assets/0dd10bad-25a1-4c7b-8b63-bec3101358f5" />



SET logs the information in the xml file under /root/.set directory

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
