# alpha-wpes 3.0

# Alpha Windows Privilege Escalation Suite 3.0

<img width="1178" alt="Screenshot 2024-03-05 at 4 01 33 PM" src="https://github.com/smridhgupta/alpha-wpes/assets/106184548/0baf45b6-00a8-4dd8-a937-2ae768698a6d">



Alpha Windows Privilege Escalation Suite is designed to gather a wide array of system, network, and security information, as well as perform certain actions that compromise system security.


Performs various system checks and operations aimed at identifying potential vulnerabilities and escalating privileges on Windows systems.


# Usage

```
git clone https://github.com/smridhgupta/alpha-wpes.git
cd alpha-wpes
awpes3.exe
```

NOTE: To make the most of it, run it as Administrator in CMD.


# Features

```
System Info:

Enumerates Basic System Information
Gets OS Version
Lists Windows updates
Enumerates Processor Architecture
Retrieves Hotfix IDs
Lists Security Updates
Gets Environment variables
Gets PowerShell History
Gets PowerShell Transcript files
PowerShell Module Logging Information
Queries Internet Settings
Displays Drives
```

```
Users:

Enumerates User
Enumerates All Local Users
Logged Uses/Sessions
User Password Policy
Gets Clipboard
```

```
Groups:

Enumerates All Groups
Gets Users Under Group Administrators
Gets User Privileges
Gets Account Operators
Admin SD Holder Users Groups
Members of the "Backup Operators" Group
Members of the "DnsAdmins" Group
Members of the "Event Log Readers" Group
Members of the "Exchange Windows Permissions" Group
Members of the "Remote Desktop Users" Group
Members of the "Remote Management Users" Group
Members of the "Server Operators" Group
```

```
Services and Processes:

Running Services and Processes
Gets SYSTEM Processes
List of Services
Service Brief
Gets Binary Path of Services
Gets System32 Services
Lists Installed Software
Gives User trusted Services suggestion
Check for Programs run on Startup
```

```
Network:

Get a list of computers
Shares on the Domains
Shares of this computers
Tries to Mount the Share locally
Current Shares
TCP/IP HOSTS File
Windows IP Configuration
Open Ports
Routing Table
ARP Table 
Firewall Rules
```

```
Antiviruses and Detectors:

Gets Audit Settings
Checks for Windows Event Forwarding
Check for Admin Password Enable
Local Security Authority (LSA) Protection check
Check for Credential Guard
```

```
Extracting Credentials:

Alpha-WPES also includes features that could be utilized for malicious purposes, such as extracting sensitive information like passwords from different locations.
Getting SAM and SYSTEM dump as well as cached credentials.
Queries Windows Registry for certain values related to user authentication
Retrieves user personal information, which might include stored credentials used for network authentication.
Attempts to extract Wi-Fi passwords stored on the system.
Retrieves SSH-related information, including stored session configurations and SSH host keys, which can be used for authentication.
```

```
Hacker:

Alpha-WPES attempts to add a new user with elevated privileges to the system.
It tries to add a new user with the username "hacker" and the password "Hacker123!".
It adds the newly created user to the administrators group.
Enables Remote Desktop access.
Allow Remote Desktop connections by setting specific registry keys.
Adds a rule to allow incoming Remote Desktop Protocol (RDP) traffic through port 3389.
```

```
Defeating Windows Defender:

Alphs-WPES attempts to defeat Windows Defender by modifying various system settings and configurations.
It adds an exclusion for files with the ".exe" extension, which might contain malicious scripts.
Disables User Account Control (UAC)
Disables Controlled Folder Access
Disables Potentially Unwanted Application (PUA) Protection
Sets Default Actions for Threats to Quarantine
Sets Scan Schedule Day to Day Saturday
Disables Windows Firewall for all profiles.
```

```
Miscellaneous Checks:

Profiles on Wi-Fi
Enumerates SNMP
Extracts Winlogon Info
Extracts user personal info
Gets Putty Sessions
Attempts to Start SSH Agent
Looks for web.config file in inetpub
Lists Installed Third Party Drivers
Looks for web.config file in xampp
Adds domain object ACL for the specified principal with all rights.
Getting the ACL of the Domain Admins group and resolves GUIDs
Retrieves deleted objects from Active Directory
Gets WSUS Info.
Check for AlwaysInstallElevated
```

# Scenario 1: Elevating Privileges for Robust Remote Hacking

Your objective is to test the organization's network defenses by simulating an attacker who has already gained initial access to a system but needs to escalate their privileges to access more sensitive areas of the network. Here, the Alpha Windows Privilege Escalation Suite comes into play. 
It displays detailed system information, lists installed updates, and identifies potential security vulnerabilities without breaking a sweat. It stealthily queries system settings, evades defences, extracts sensitive information, and even adds a new administrator user that too within seconds, ensuring that your access is not just elevated but cemented, allowing for deeper penetration into the system. The suite becomes the cornerstone of your strategy, enabling an extremely fast, efficient, and robust privilege escalation process that is essential for the success of your operation.


# Scenario 2: Swift Data Exfiltration with a Physical Hotplug Device

Now, imagine you're demonstrating the risks associated with physical access to computer systems. A scenario where a seemingly innocuous USB device, such as a Rubber Ducky, is used for rapid data exfiltration. Embedded with the Alpha Windows Privilege Escalation Suite, this device is not just a tool; it's a master key to any system it touches.
As soon as the device is plugged into, it bypasses security measures, querying system configurations, and extracting critical data all within the blink of an eye. The tool's capability to retrieve Wi-Fi passwords, list running services, and extract saved credentials, all without leaving a trace is phenomenal.
This powerful demonstration serves as a stark reminder of the importance of physical security measures and the potential consequences of neglecting them.

# Donate

. BTC: bc1qykzfyjdkyck5v4sd46j4y8ra6mgltvu6zqu69s

# Disclamer

The developer retains the copyright to the script uploaded on this repository. This script is provided for educational and informational purposes only.

The developer makes no representations or warranties regarding the accuracy or completeness of the script. Users downloading or utilizing the script do so at their own risk and discretion. The developer shall not be liable for any direct, indirect, incidental, special, or consequential damages arising out of the use or inability to use the script.

By downloading or using the script, you agree to abide by the terms and conditions mentioned here. If you have any questions or need further information, please contact the developer Smridh Gupta, Email- smridhgupta@proton.me.

# Contact
smridhgupta@proton.me

Developed by @smridhgupta
