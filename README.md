# Cloud user account password sniffing and Sessions hijacking on Owncloud

# Projrect Summary 
This project demonstrates two common vulnerabilities in ownCloud :
 1. Cloud User Password Sniffing – 
This demonstration shows how an attacker can intercept and capture a user's credentials as they are transmitted over the network. The focus is on illustrating the risks of insecure communication channels and the importance of encryption.

2. Session Hijacking –
In this practical, by performing a Man-in-the-Middle (MITM) attack and stealing the user's session cookies. A session hijacking vulnerability in the cloud web interface can allow an attacker to steal cookies and gain unauthorized access to the admin account.
# Project  1. Cloud User Password Sniffing :- 


## Step 1:
Reconnaissance – Identifying the victim’s IP address through network scanning techniques to target the correct system for the demonstration.

Setting up Parrot OS and Wireshark – Configuring Parrot OS as the penetration testing platform and utilizing Wireshark to monitor and capture network traffic, including potential spoofing attempts.

![Screenshot 2025-03-17 171308](https://github.com/user-attachments/assets/709fe027-1731-4eeb-be54-806ba970d7f5)


Using Wiresharks HTTP POST Filter I configure Wireshark to filter and monitor HTTP POST traffic, allowing me to analyze communications between the victim and the server.

![Screenshot 2025-03-17 173440](https://github.com/user-attachments/assets/1124e1ba-3551-4880-8265-3b294d278ca1)

Here we Got User and password.

![Screenshot 2025-03-17 173520](https://github.com/user-attachments/assets/5ac4f90c-75eb-4a14-898b-f00c7eef2d65)



# Project 2. Sessions Hijacking :-

In this practical, by performing a Man-in-the-Middle (MITM) attack and stealing the user's session cookies. A session hijacking vulnerability in the cloud web interface can allow an attacker to steal cookies and gain unauthorized access to the admin account.

## Step 1:
Once I obtain the cookie and session ID, I log into my account and replace the session ID and cookie I stole from the victim. After changing the session and cookie, I gain unauthorized access to the victim's account.

 

![Screenshot 2025-03-17 173703](https://github.com/user-attachments/assets/e2f8efc0-ae24-4565-83fb-9f633828a6ab)


![Screenshot 2025-03-17 173908](https://github.com/user-attachments/assets/94709a5f-7e31-4c22-8525-4de8dc7520ec)

Now, I have successfully gained access and am logged into the victim's account.

![1](https://github.com/user-attachments/assets/afbbf470-03c1-47e9-9b5f-667c44d718de)



