# B2BR Cheatsheet

# How does a Virtual Machine work?

A VM is a computer file that has its own memory, CPU, disks, but in a non-tangible way. It is all code. It runs in a physical server through an Hypervisor, that acts creating VM’s and managing the available hardware between VM’s and the host OS.

# OS choice

I chose Debian because it has a bigger community, consequently it would be easier to get help if needed.

# Differences between CentOs and Debian

CentOs is more focused on entreprises and used for large-scale businnesses. It is a very stable distro.

Debian, on its part, has one of the most active communities online, what really helps if you face any problem or bug. It is also updated more frequently than CentOs, which can be good (less bugs), or bad (if you need stability).

# The purpose of Virtual Machines

- Building and deploying apps to the cloud
- Trying out a new operating system (OS)
- Spinning up a new environment to make it simpler and quicker for developers to run dev-test scenarios
- Accessing virus-infected data or running an old application by installing an older OS

# Differences between apt and aptitude

Both are package managers that can be used on Debian.

APT (Advanced Package Manager) is CLI only, but still allows the user to install, remove, update and list packages.

Aptitude does the same as APT, but adds a GUI, allowing users to interactively search for packages.

# What AppArmor is?

AppArmor is an application that helps protecting our environment from internal and external threats, by enforcing good behavior and preventing both known and unknown application flaws from being exploited.

It allows to set a security profile for each application, specifying what actions each application can perform in the system.

# LVM

Disk partitioning was made manually, following the subject's structure. We had to use **Logical Volume Manager**, or LVM, which allows us to dinamically partition a disk, based in Physical Volumes (PV's), Volume Groups (VG's) and Logical Volumes (LV's).

# Useful commands

- Checking if a service is up and running:
    
    ```bash
    systemctl status <SERVICE>
    ```
    
- Check running OS:
    
    ```bash
    uname -a
    ```
    
- Managing groups:
    
    ```bash
    groups
    groupadd <GROUP>
    ```
    
- Managing users:
    
    ```bash
    adduser <NAME>
    userdel <NAME>
    usermod -a -G <GROUP> <USERNAME>
    ```
    
- Password policy:
    
    ```bash
    /etc/pam.d/common-password
    /etc/login.defs
    ```
    
- Hostname:
    
    ```bash
    hostname
    /etc/hostname
    /etc/hosts
    ```
    
- Partitions:
    
    ```bash
    lsblk
    ```
    
- Sudo rules:
    
    ```bash
    /etc/sudoers.d/sudoconfig
    visudo sudoconfig
    ```
    
- UFW
    
    ```bash
    ufw enable
    ufw status
    ufw allow
    ufw deny
    ```
    
- SSH
    
    ```bash
    /etc/ssh/sshd_config
    ssh <username>@<localhost> -p 4242
    ```
    
- Crontab:
    
    ```bash
    crontab -e
    ```
