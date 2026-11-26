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

<img width="697" height="842" alt="image" src="https://github.com/user-attachments/assets/94caa0aa-4333-467e-8a71-a61e745e7f12" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="376" height="270" alt="image" src="https://github.com/user-attachments/assets/30f545b5-29c0-4db7-9e11-ddede0019578" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT


<img width="367" height="325" alt="image" src="https://github.com/user-attachments/assets/aafd164b-559a-42d5-8d7a-84be08afbb51" />

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="365" height="217" alt="image" src="https://github.com/user-attachments/assets/353e53c8-491d-47f7-b84e-1c8a97329d37" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="760" height="552" alt="image" src="https://github.com/user-attachments/assets/5851b55e-dde5-486e-a09c-c5e0b7bb2990" />



It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="697" height="480" alt="image" src="https://github.com/user-attachments/assets/a07c7b47-ebad-4c84-9dc5-8911167ef2fc" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT



<img width="1155" height="196" alt="image" src="https://github.com/user-attachments/assets/a65d8d93-4c1f-4b25-8613-f7687c5050e7" />

In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="997" height="770" alt="image" src="https://github.com/user-attachments/assets/5769092f-ea76-4fff-85e7-4a2dc4a0d294" />

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1268" height="572" alt="image" src="https://github.com/user-attachments/assets/7ba6d4a7-7a3d-403f-a4ef-f261b8169b4e" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT



<img width="1323" height="806" alt="image" src="https://github.com/user-attachments/assets/2979cda5-0bc0-48c5-a08f-cb8dd2395de1" />









## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
