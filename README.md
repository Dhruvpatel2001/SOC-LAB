# SOC-LAB

This project is currently under development, and this README contains the progress of my SOC lab 

## Starting Point 

Started with the creation of a Windows 11 Virtual Machine where I would download Sysmon

Figure1:Virtual Machine creation and setup.
<img width="1299" height="793" alt="image" src="https://github.com/user-attachments/assets/585ae3be-a5ea-40f4-a13c-a120d1cfe4b2" />

## Sysmon Installation 

After installing Sysmon, I  checked if it is running on the system. There are many ways to check it; I used the Services console to check whether it is running or not, as shown in Figure2.

Figure2:Checking status of Sysmon
<img width="2758" height="1510" alt="image" src="https://github.com/user-attachments/assets/79ad8c1a-cbaa-438d-87a5-84e17e8e0c05" />

## Wazuh Server setup and configuration 
In Progresses

Problem faced for this phase: the issue was that the Server(Ubuntu)and the Windows machine are on a VM, so each of them runs on an isolated network, and they are not able to connect to each other.
To solve the issue, what I did was add port forwarding to the Ubuntu server and then tried to SSH into the server, but this did not work.
The other option I tried was to create a network of my own and add the two machines to the network so they could communicate with each other, and this option worked, and I was able to connect to the server via SSH. 

More information and updates on the project will come soon!!!!
