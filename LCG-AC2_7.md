<b> How an actor may carry out a cyber-attack </b>

Cyber-attacks can be carried out through a variety of methods and tactics, depending on the attacker's goals, resources, and the vulnerabilities they are exploiting. Here’s an overview of how an actor may carry out a cyber-attack, including the steps they might take and common techniques used:

<b> 1. Reconnaissance </b>
  * **Purpose:** To gather information about the target, including system details, network architecture, personnel, and potential vulnerabilities.
  * **Techniques:**
    * **Open Source Intelligence (OSINT):** Collecting data from public sources like social media, websites, and forums.
    * **Network Scanning:** Using tools to map out the network, discover live hosts, and identify open ports and services.
    * **Social Engineering:** Phishing for information from employees or using pretexting to obtain details.

<b> 2. Scanning and Enumeration </b>
  * **Purpose:** To identify active systems, open ports, and services running on the target network.
  * **Techniques:**
    * **Port Scanning:** Using tools like Nmap to detect open ports and running services.
    * **Vulnerability Scanning:** Using tools like Nessus to find known vulnerabilities in the target systems.
    * **Banner Grabbing:** Collecting information from service banners to identify software versions and potential vulnerabilities.

<b> 3. Exploitation </b>
  * **Purpose:** To take advantage of identified vulnerabilities to gain unauthorized access or control over the target system.
  * **Techniques:**
    * **Exploiting Vulnerabilities:** Using known exploits or zero-day vulnerabilities to gain access. Examples include buffer overflow attacks or SQL injection.
    * **Phishing and Social Engineering:** Sending malicious emails or messages to trick users into revealing credentials or installing malware.
    * **Brute Force Attacks:** Using automated tools to guess passwords or encryption keys.

<b> 4. Installation </b>
  * **Purpose:** To establish a foothold within the target system or network.
  * **Techniques:**
    * **Malware Deployment:** Installing malicious software such as backdoors, trojans, or rootkits to maintain access.
    * **Web Shells:** Uploading scripts to web servers to gain persistent access.
    * **Privilege Escalation:** Exploiting weaknesses to gain higher-level access, such as administrator or root privileges.

<b> 5. Command and Control (C2) </b>
  * **Purpose:** To remotely control and communicate with compromised systems.
  * **Techniques:**
    * **C2 Channels:** Using channels such as HTTP, DNS, or custom protocols to issue commands and exfiltrate data.
    * **Remote Access Tools:** Utilizing tools or malware to remotely control compromised systems.
    * **Data Exfiltration:** Extracting data through secure channels or encrypted connections to avoid detection.

<b> 6. Action on Objectives </b>
  * **Purpose: To achieve the attacker's ultimate goals, whether it’s stealing data, causing disruption, or other objectives.
  * **Techniques:**
    * **Data Theft:** Extracting sensitive information like personal data, financial records, or intellectual property.
    * **Ransomware Deployment:** Encrypting data or systems to demand a ransom for decryption.
    * **Disruption:** Causing system outages, deleting or corrupting files, or launching denial-of-service (DoS) attacks.
    * **Tampering:** Modifying or damaging data, systems, or configurations to disrupt operations or damage reputation.

<b> 7. Covering Tracks </b>
  * **Purpose:** To avoid detection and removal, making it harder for the victim to understand the attack and mitigate it.
  * **Techniques:**
    * **Log Manipulation:** Erasing or altering logs to remove evidence of the attack.
    * **Rootkit Installation:** Using rootkits to hide malicious activity and maintain stealth.
    * **Data Wiping:** Erasing or encrypting data to obscure the attacker's actions.


<b> Examples of Specific Techniques: </b>
  * **Phishing:** Crafting deceptive emails or messages to trick recipients into revealing sensitive information or downloading malware.
  * **SQL Injection:** Exploiting vulnerabilities in web applications to execute arbitrary SQL queries.
  * **Man-in-the-Middle (MitM) Attacks:** Intercepting and potentially altering communication between two parties without their knowledge.
  * **Denial-of-Service (DoS) Attacks:** Overloading a system or network with traffic to disrupt normal operations.
