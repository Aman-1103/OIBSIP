<heading> OIBSIP
---
## TASK 2 · Basic Firewall Configuration with UFW

---
### 1. OBJECTIVE:
The main objective of UFW (Uncomplicated Firewall) in Linux is to provide simple and effective network security. It controls incoming and outgoing traffic, allows or blocks specific ports and services, prevents unauthorized access, and helps protect the system from potential network threats. UFW also simplifies firewall management by providing easy-to-use commands for configuring security rules. Overall, it helps users maintain a safer and more controlled Linux environment.

---
### 2. TOOLS AND ENVIROMENT :

| Command | Purpose |
|---------|---------|
| **Operating System**| Kali Linux (virtualbox) |
| **Tools Used**  | UFW- Uncomplicated Firewall(v0.36.2) |
| **Interface** | Terminal(Zsh Shell) |
|**Focus Area**| Enabling the Firewall and configuring allow/deny rules|

---
### 3.Step-by-Step Procedure :-


**Step 1:Installing of UFW:**

Run the `sudo apt install ufw -y ` to install the ufw on your Kali Linux machine .


<img width="800" height="600" alt="Screenshot_2026-08-15_00_41_52" src="https://github.com/user-attachments/assets/302156f1-cd38-4009-a879-8055323ecb17" />


**Step 2: Enabling UFW:**

To turn on the Uncomplicated Firewall (UFW) in Linux, run the command `sudo ufw enable`


<img width="800" height="414" alt="image" src="https://github.com/user-attachments/assets/34b2801b-92fd-4bc1-8ca6-29e1fd2d856c" />

<br>

**Step 3: Configure the rule of ssh and http:**


First, open the Linux terminal and ensure that UFW is enabled. Use the command `sudo ufw allow ssh` to allow incoming SSH connections. Next, use `sudo ufw deny http` to block incoming HTTP traffic on port 80. Finally, run `sudo ufw status` to check the firewall status and verify the configured rules. This procedure demonstrates how UFW can be used to control network traffic by allowing required services and blocking unwanted connections, thereby improving the security of the Linux system.



<img width="800" height="600" alt="Screenshot_2026-08-15_00_45_49" src="https://github.com/user-attachments/assets/9effef52-675e-45b4-9f47-e4a1e383b606" />

---
### what a firewall does, what each rule achieves, and why these specific rules were chosen?


A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined rules. In UFW, the rule `sudo ufw allow ssh` permits SSH connections, allowing secure remote administration of the Linux system. The rule `sudo ufw deny http` blocks incoming HTTP traffic on port 80, preventing unauthorized access to web services. Finally, `sudo ufw status` displays the firewall’s current status and configured rules. These specific rules were chosen to demonstrate both allowing and blocking network services. SSH is allowed because it is commonly required for remote management, while HTTP is denied to reduce unnecessary exposure of web services and improve system security.

---

### Conclusion

This UFW project provided practical knowledge of Linux firewall configuration and network security. I learned how to install and enable UFW, allow SSH connections, deny HTTP traffic, and check firewall status using basic commands. I also understood how firewall rules control incoming network traffic and help prevent unauthorized access. The project improved my understanding of network security, port management, and Linux administration. Overall, I gained hands-on experience in configuring a firewall and learned how simple UFW rules can be used to protect a Linux system.


