# alpha-wpes

Alpha Windows Privilege Escalation Suite is not detected as malecious by Windows Defender or any other AV.

# Features

1. Enumeration of General Information: Alpha-wpes can retrieve general information about the operating system, such as OS version, architecture, installed patches, network configuration, and environment variables.

2. Service and Process Enumeration: It scans the system for running services and processes, providing details about their privileges, executables, and associated users.

3. File and Directory Permissions: Alpha-wpes examines the permissions of critical system files, directories, and registry keys. It identifies any misconfigured or insecure permissions that may lead to privilege escalation.

4. Scheduled Tasks and Jobs: It lists scheduled tasks and jobs on the system, including their associated executables and the users under which they run. This helps identify tasks that may be abused for privilege escalation.

5. Registry Auditing: Alpha-wpes checks for weak registry key permissions, identifying keys that can be modified by non-administrative users. This can be useful for finding misconfigurations that allow unauthorized modifications or privilege escalation.

6. Installed Software and Patch Levels: It scans the system for installed software and checks for known vulnerabilities associated with specific versions. This information can assist in identifying outdated or vulnerable software that can be exploited.

7. Network Enumeration: Alpha-wpes retrieves information about network interfaces, open ports, and established network connections. It helps identify potential avenues for lateral movement or privilege escalation through network services.

8. User and Group Enumeration: It enumerates users and groups on the system, highlighting any privileged or misconfigured accounts that can be targeted for privilege escalation.

9. Autologon Credentials: Alpha-wpes looks for autologon credentials stored in the Windows registry. This can reveal sensitive login information that may allow an attacker to gain unauthorized access.

10. Security Auditing: It performs security auditing checks, including checking for weak permissions, services running as SYSTEM, weak registry keys, and misconfigured group policies.


# Usage

No need to clone just download the Binary from Releases and run wpe.exe in CMD.

# Donate

. BTC: bc1qykzfyjdkyck5v4sd46j4y8ra6mgltvu6zqu69s

. XMR: 49RNZHq5kZJDJUK6RmnnxdhHwC7RNDTRM6VLj5ivsWiXGFXxdWFVJcHicrbY1TL4rn3fVhHGMNke4LmkJFVCsFuSEdcW47E

# Warning

This project is only for educational purposes. I am not responsible for any misuse!

# Contact
smridhgupta@proton.me

Developed by @smridh
