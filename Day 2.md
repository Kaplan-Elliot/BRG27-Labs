# Setting up a VM using a cloud service

## Obatining the cloud service

### Creating an account

I created an account with my chosen cloud provider, which is Microsoft Azure.

1. <img width="1142" height="856" alt="created azure acc" src="https://github.com/user-attachments/assets/b6c6de61-7575-4a9d-984c-e5f0713116be" />

### Creating the VM

Following the instructions given, I created a VM with the default settings and added the ports to the security group. 

1. <img width="1472" height="1073" alt="Cretae A VM" src="https://github.com/user-attachments/assets/7d78df48-3a8f-4d02-b504-aaa92cea03ef" />

2. <img width="1565" height="567" alt="vm set up" src="https://github.com/user-attachments/assets/454a5d33-8d4e-4c86-8fba-b2aa3c5d3cbf" />

3. <img width="1516" height="542" alt="security grp" src="https://github.com/user-attachments/assets/42e40e1d-24f7-449d-8cc6-9080a28bbd15" />

I then downloaded the private key to my local VM and performed a SSH connection to the cloud VM from it.

1. <img width="788" height="665" alt="connection vm main" src="https://github.com/user-attachments/assets/e649d27b-3bab-40a1-979b-2f765c5ba239" />

From there I added Apache web server to my cloud VM.

1. <img width="1270" height="708" alt="installing apache2 onto the vm" src="https://github.com/user-attachments/assets/05efbb85-e2c6-4c3c-840f-f4e8ec167411" />

2. <img width="1071" height="1004" alt="apache2 on the vm" src="https://github.com/user-attachments/assets/5c0455a5-512d-4607-8835-b3a2cfc4aafb" />


## Bash Scripting

### File navigation and management

To start, I created a directory for a text file and wrote into it.

1. <img width="881" height="466" alt="image" src="https://github.com/user-attachments/assets/497c3d7b-931b-437b-8370-9c1cccb6d7bc" />

This was to understand the basics of Bash scripting and the commands that would be used for it.


### Bash scripting, loops and conditions

The next part was to create a shell for the script with the following lines inside, "#!/bin/bash" and "echo "Hello, World!""

1. <img width="892" height="586" alt="image" src="https://github.com/user-attachments/assets/f96afb80-1a66-4d01-b541-6f49ada794b9" />

After that was to try out the loop fucntion. This function would count for 5 seconds and aftewards ask for a number between one to ten. When the number is typed in a response would be given.

1. <img width="726" height="531" alt="image" src="https://github.com/user-attachments/assets/f48b3574-14f8-4201-a0b4-b0acb82bbc84" />


2. <img width="726" height="483" alt="image" src="https://github.com/user-attachments/assets/ecdb4470-8954-441c-9007-530552691d12" />

The next step was to create a simple script that autonmates monitoring system resources and CPU usage.

1. <img width="815" height="638" alt="image" src="https://github.com/user-attachments/assets/31e41573-c097-4141-9f05-a38bcab6d260" />

2. <img width="808" height="598" alt="image" src="https://github.com/user-attachments/assets/b2e3c35f-8005-4e3f-9482-6d90757c1060" />

3. <img width="952" height="616" alt="image" src="https://github.com/user-attachments/assets/9da91351-d805-4e88-8983-e866324dc9cb" />
