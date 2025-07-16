# Downloading and Setting up Linux on my PC
### Installing Oracle virtual box
I installed Oracle VirtualBox and the Ubuntu ISO file from their respective websites.
1. <img width="1099" height="953" alt="download  linux" src="https://github.com/user-attachments/assets/95d750fa-9a7e-4978-b536-7b540504578b" />
2. <img width="621" height="41" alt="ubuntun file" src="https://github.com/user-attachments/assets/4476b3f6-0ebb-446a-a6d6-041beba8351e" />


## Creating the VM


### Setting up VirtualBox
Afterwards I began creating the VM, selecting the desired settings to ensure that there is no issue with running the programs, then running the machine followed by mounting the ISO file into the Oracle VirtualBox, running the Ubuntu OS to show on the VM.

1. <img width="1572" height="849" alt="start 1" src="https://github.com/user-attachments/assets/62d3ac81-0395-4310-903c-a091942db0cf" />

2. <img width="760" height="543" alt="Settings for VM" src="https://github.com/user-attachments/assets/aab326d9-fcc0-4ee5-bb5c-be2244ae8c97" />

3. <img width="751" height="535" alt="setting up pt 2" src="https://github.com/user-attachments/assets/c175b3c8-70cb-47cf-b410-40fc86d3e97a" />


4. <img width="267" height="127" alt="VM created" src="https://github.com/user-attachments/assets/c567581a-01dd-43d0-aeeb-3f0b281ced7d" />

5. <img width="705" height="446" alt="install ubuntu" src="https://github.com/user-attachments/assets/1731abc1-93d1-4c08-b214-2cf63d83eed2" />

### Trying out commands
I played around with the different commands such as 'ps -e', 'nano', 'gedit' to name a few.

1. <img width="1291" height="895" alt="cont 3" src="https://github.com/user-attachments/assets/9d37aabc-f0c6-4fc6-9b80-f0d44f61b0fd" />

2. <img width="1397" height="901" alt="cont 4" src="https://github.com/user-attachments/assets/a3f4c21f-46e7-4a5d-bd48-3960fc60132c" />

3. <img width="1249" height="866" alt="cont 5" src="https://github.com/user-attachments/assets/bbe285d7-258e-42aa-9453-aa6789ab2b20" />


## Setting up Linux services 

Firstly, I checked for new packages using 'sudo apt update' and downloaded the Apache web server.

1. <img width="1270" height="860" alt="cont 6" src="https://github.com/user-attachments/assets/9e89110c-c37a-4813-9eb5-a2308a753549" />

2. <img width="1271" height="862" alt="cont 7" src="https://github.com/user-attachments/assets/e09fbcd0-ee79-4681-bc80-32078a148080" />

Secondly, I downloaded the 'nmap' service and SSH.

1. <img width="1265" height="865" alt="cont 8" src="https://github.com/user-attachments/assets/53259345-b011-4ad4-a7ec-0d799b345f86" />

2. <img width="1266" height="864" alt="cont 9" src="https://github.com/user-attachments/assets/c6ed8922-27b7-409b-ac44-9f91e449fc1e" />

### Testing out the services

#### Using nmap and ip a

1. <img width="1207" height="820" alt="cont 15" src="https://github.com/user-attachments/assets/d401ce5b-345f-48c1-bcbd-45b6074a55b4" />

2. <img width="1193" height="534" alt="cont 14" src="https://github.com/user-attachments/assets/61bb7d0b-3ca3-4724-b1c0-3955ddb827ca" />

### Setting up firewall

Using the command 'sudo ufw enable', the firewall for my VM was enabled and prevented my other VMs from scanning it with namp. I then allowed port 80 on the main VM and tried scanning again.

1. <img width="2297" height="865" alt="Screenshot 2025-06-29 091146" src="https://github.com/user-attachments/assets/9cd9bc44-f8bc-478e-a109-4c708b4f0137" />

### SSH into neigbouring VM

With the IP address of my second VM changed to a different one to ensure that the connection would work as it would not work on the same IP address. Afterwards, I added a user to the main VM and using the username and password of the user, I SSH'd into it from the second VM.

1. <img width="1118" height="839" alt="added user called cat" src="https://github.com/user-attachments/assets/8a6cb763-4c6f-46d3-86a4-1e4326ff1503" />

2. <img width="1019" height="931" alt="logged in and left" src="https://github.com/user-attachments/assets/695a1cde-9295-4f7e-908b-e25b13170d6e" />

## Setting up Linux permissions

### Creating users and setting their permissions

I created three users, and gave them each different permissions based of the lab requirements.

1. <img width="877" height="283" alt="image" src="https://github.com/user-attachments/assets/8b4a5a82-1635-4549-884e-aa34b82270ad" />

User alice had the permissions to read, write and execute. User bob could only read and execute while user mallory could do nothing.


User alice
1. <img width="803" height="352" alt="image" src="https://github.com/user-attachments/assets/1cf23e85-00f4-4931-873a-4b001e5f1bd3" />

User bob
1. <img width="975" height="535" alt="image" src="https://github.com/user-attachments/assets/1d6f4833-7d16-4e7d-b22b-a1acfdb06016" />

2. <img width="975" height="539" alt="image" src="https://github.com/user-attachments/assets/b3da66d6-3d5a-4c9a-a1cc-352f8b42d348" />

User mallory
1. <img width="963" height="167" alt="image" src="https://github.com/user-attachments/assets/17d530a7-6955-444a-b747-5d1c8433c628" />











