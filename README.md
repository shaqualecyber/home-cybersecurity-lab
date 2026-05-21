# Home Cybersecurity Lab Setup

## Objective
The purpose of this lab was to build a personal cybersecurity lab environment on a MacBook using VMware Fusion. I created separate virtual machines for Windows and Fedora to practice operating system installation, virtualization, system configuration, and future cybersecurity labs.

## Environment
- macOS
- VMware Fusion
- Windows 10 virtual machine
- Fedora Linux virtual machine

## Skills Practiced
- Virtualization
- Operating system installation
- ISO mounting
- VM resource allocation
- User account setup
- Basic system configuration
- Troubleshooting
- Technical documentation

## Tools Used
- VMware Fusion
- Windows ISO
- Fedora ISO
- macOS
- YouTube walkthroughs
- FTCC lab documentation

## Lab Summary
I installed VMware Fusion on my MacBook and created a Windows virtual machine using a Windows ISO file. After installation, I configured the operating system settings, created a user account, and verified the system was working properly.

I also created a separate Fedora virtual machine to begin building a multi-operating-system lab environment for future cybersecurity practice.

## Steps Completed

### 1. Installed VMware Fusion
Installed VMware Fusion on macOS to create and manage virtual machines.

### 2. Created Windows VM
Created a new virtual machine, mounted the Windows ISO, assigned system resources, and completed the Windows installation.

### 3. Configured Windows Settings
Completed initial Windows setup, configured user account settings, and verified the system was functional.

### 4. Created Fedora VM
Created a second virtual machine for Fedora Linux, mounted the Fedora ISO, and completed the operating system installation.

### 5. Verified Lab Environment
Confirmed that both virtual machines were installed successfully and ready for future cybersecurity labs.

## Challenges Encountered

One challenge I encountered during this lab was understanding the difference between the Windows VM setup process and the Fedora VM setup process. When I created the Windows VM, I had to walk through the operating system installation, user account setup, and initial system configuration. With Fedora, the VM booted into the desktop environment much faster than expected, which required me to slow down and verify the user account, system settings, and environment details after the initial launch.

I also had to get more comfortable with Linux user account behavior. At one point, I noticed the home folder name did not match the username I expected to be working under, which led me to review the user account settings and how Fedora handles live sessions and local accounts. This helped me better understand why confirming the active user, hostname, and system details matters before documenting a lab.

Another small challenge was relearning basic terminal workflow. During network connectivity testing, I initially forgot how to stop or limit a continuous ping command. I reviewed the proper syntax and used ping -c 4 google.com to send a set number of packets, which created cleaner output for documentation.

Overall, these challenges helped me practice troubleshooting, verifying system configuration, and becoming more comfortable navigating Fedora as a Linux environment.

## Results
Successfully created a basic home cybersecurity lab environment with separate Windows and Fedora virtual machines.

## Screenshots

### VMware Fusion Dashboard
![VMware Fusion Dashboard](images/vmware-fusion-dashboard.png)

### Windows VM
![Windows VM](images/windows-vm-desktop.png)

### Fedora VM
![Fedora VM](images/fedora-vm-terminal.png)

## Key Takeaways
This lab helped me better understand virtualization, operating system deployment, ISO mounting, VM setup, and how virtual machines can support cybersecurity training and future SOC-focused labs.

## Future Improvements
- Configure VM networking
- Practice Windows Event Viewer analysis
- Install security tools
- Practice Linux commands in Fedora
- Build future SOC and phishing analysis labs
