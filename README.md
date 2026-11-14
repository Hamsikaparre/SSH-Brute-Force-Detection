# SSH Brute Force Detection Using Kali Linux & Fail2Ban

## Project Overview
This project explores SSH brute-force attacks and defensive security monitoring in a controlled virtual lab environment using Kali Linux, OpenSSH, Fail2Ban, and Oracle VirtualBox.

The objective was to understand how repeated failed SSH login attempts can be monitored through authentication logs and how Fail2Ban can help protect systems against unauthorized access attempts.

## Tools and Technologies
- Kali Linux
- OpenSSH
- Fail2Ban
- Oracle VirtualBox
- Linux Terminal

## Practical Implementation

### Screenshot 1: SSH and Fail2Ban Service Status
This screenshot shows the service status of SSH and Fail2Ban. I checked whether the services were running and explored the SSH service configuration as part of the initial lab setup.

### Screenshot 2: SSH Authentication Logs
This screenshot shows repeated failed SSH login attempts performed in the local lab. I used `journalctl` to monitor authentication logs and understand how unsuccessful login attempts are recorded.

### Screenshot 3: Fail2Ban Configuration and Status
This screenshot shows the Fail2Ban jail status and configuration. I explored parameters such as maximum retry attempts and ban time and investigated compatibility and command-support issues.

## Challenge Faced
I encountered compatibility and command-support issues with my installed Fail2Ban version, which prevented me from successfully verifying automatic IP blocking. However, I was able to practise SSH authentication monitoring and analyse failed login attempts.

## Key Learnings
- Understanding SSH brute-force attacks.
- Linux service management.
- Monitoring authentication logs using journalctl.
- Exploring Fail2Ban jail configuration.
- Basic log analysis and troubleshooting.
- Understanding intrusion prevention concepts.

## Project Outcome
Gained practical exposure to SSH security monitoring, authentication log analysis, and defensive cybersecurity concepts.

**Note:** This project was performed in a controlled local virtual lab environment.
