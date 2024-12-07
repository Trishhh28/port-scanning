# Port Scanning with Nmap and Kali Linux  

## Objective  
This project aimed to explore the effectiveness of port scanning using Nmap on Kali Linux for identifying open ports and assessing network security. The goal was to gain hands-on experience in network reconnaissance and vulnerability identification, crucial for proactive threat detection and mitigation.  

### Skills Learned  
- Comprehensive understanding of network port scanning and its applications.  
- Proficiency in using Nmap for active network reconnaissance.  
- Analysis of port states (open, closed, filtered) and their security implications.    
- Enhanced problem-solving skills in identifying potential vulnerabilities in network configurations.  

### Tools Used  
- **Nmap** for port scanning and service detection.  
- **Kali Linux** as the operating system for running security tests.  
- **Wireshark** to analyze network traffic and verify scan accuracy.   

## Steps  

1. **Environment Setup:**  
   - Install Kali Linux as the base operating system.  
   - Ensure Nmap is installed (pre-installed on Kali Linux).  
   - Set up a target environment (local network or test VMs) for scanning.  

2. **Perform a Basic Port Scan:**  
   - Use the following command to identify open ports on the target:  
     ```bash
     nmap <target-ip>
     ```  
   - Example Screenshot:  
    ![Screenshot 2024-12-06 135818](https://github.com/user-attachments/assets/aee3db5c-9178-4639-be5f-98e0ba68fff7)
    ![nmap1](https://github.com/user-attachments/assets/7c69a31a-d921-4976-8e44-d6261641151c)

3. **Advanced Scanning Techniques
:**  
   - Use flags for advanced features such as stealth scan, service detection, and OS identification:  
     ```bash
     nmap -sS -sV -O <target-ip>
     ```
     ![nmap3](https://github.com/user-attachments/assets/7a219e48-2b35-4749-a894-9d9cdefa5ff2)

4. **Analyze Scan Results:**  
   - Interpret port states (e.g., open, filtered, closed) and identify running services.  
   - Use **Wireshark** to capture and analyze network traffic during the scan.  

 

5. **Refine and Document:**  
   - Document findings, including potential vulnerabilities or misconfigurations.  
   - Propose mitigations for identified risks.  

