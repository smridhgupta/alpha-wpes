# alpha-wpes 3.0

# Releasing 6th March, 2024

![image](https://github.com/smridhgupta/alpha-wpes/assets/106184548/4ada09ba-8f5d-48e5-8762-cc3b51817921)


Alpha Windows Privilege Escalation Suite 3.0

# Features

Alpha Windows Privilege Escalation Suite is designed to gather a wide array of system, network, and security information, as well as perform certain actions that compromise system security. 

1. System and OS Information Gathering: It collects detailed system information, OS versions, and lists Windows updates, helping to identify potentially vulnerable components.

2. Security Updates and Hotfix IDs: Retrieves and lists security updates and hotfix IDs to assess the patch level of the system.

3. Environment and Configuration: Extracts environment variables, PowerShell history, and checks for specific registry settings that could indicate system configuration and potential security weaknesses.

4. Network and Sharing Information: Lists network drives, queries Windows Server Update Services (WSUS) settings, and displays network shares, which could reveal sensitive information or misconfigurations.

5. User and Group Information: Lists all users, groups, and specific group memberships like Administrators, Remote Desktop Group, providing insight into potential targets for privilege escalation.

6. Security Policies and Auditing: Checks policies related to AlwaysInstallElevated, audit settings, and Windows Event Forwarding, which might offer avenues for privilege escalation.

7. Credential Management: Enumerates stored credentials, Logon credentials, and LSA protection, which could be exploited to gain higher privileges.

8. Networking and Communication: Retrieves IP configuration, lists open ports, and views routing tables, which is useful for both lateral movement and understanding the network layout.

9. Software and Services: Lists running services, processes, installed software, and startup programs, identifying potential vulnerable applications or services that run with high privileges.

10. Security Tool Configuration and Weaknesses: Attempts to modify security tool configurations, such as disabling Defender or firewall settings, to evade detection and restrictions.

11. Sensitive Information Extraction: Tries to extract sensitive information like WiFi profiles and passwords, user personal info, and SSH keys, which could be used for further attacks.

12. Remote Access and User Account Creation: Attempts to create new user account “hacker” with password “Hacker123 with administrative privileges and enable remote desktop access, directly compromising the system's security.

13. Defeating Security Defenses: Performs various actions aimed at defeating Windows Defender, Windows Firewall, App and Browser Control, and other security measures to maintain access and evade detection.

14. SSH and PuTTY Configurations: Extracts SSH agent keys, PuTTY session information, and SSH host keys, which might be used for unauthorized access to other systems.

15. Web Server Configuration Files: Searches for web.config files in common web server directories (inetpub, xampp) that could contain sensitive application settings or database connection strings.

16. SNMP Configuration: Checks the Simple Network Management Protocol (SNMP) configuration for potential misuse or information disclosure.

17. Network Shares and Mapping: Lists network shares, attempts to map them locally, and queries domain shares, which could expose sensitive information or be leveraged for lateral movement.

18. Software and Registry Enumeration: Lists installed software and queries registry keys related to software, startup programs, and third-party drivers, looking for vulnerable applications or misconfigurations.

19. Miscellaneous: Includes actions like checking for third-party drivers, viewing the hosts file, and retrieving the contents of the clipboard, which could contain sensitive information.


# Usage

No need to clone just download the Binary from Releases and run awpes.exe in CMD.

# Donate

. BTC: bc1qykzfyjdkyck5v4sd46j4y8ra6mgltvu6zqu69s

# Warning

This project is only for educational purposes. I am not responsible for any misuse!

# Contact
smridhgupta@proton.me

Developed by @smridhgupta
