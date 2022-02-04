<h1 align=center>
 Born2BeRoot
</h1>

<p align=center>
 This projects aims to introduce the world of virtualization.
 It consists in creating a Virtual Machine in VirtualBox (or UTM) under specific instructions. At the end of this project we should be fully comfortable with the    concept of Virtualization, as well as dealing with command-line based systems, partitioning memory with LVM, setting up SSH ports, MACs, Firewalls, among many other  important concepts.
</p>

<h3 align=center>
 1. Operating System
</h3>
<p align=center>
 We could choose between two operating systems: Debian or CentOs. I chose <b>Debian</b> because it is more user-friendly and has a wider community than CentOs, that is commonly used by big enterprises as it is supported by Red Hat.
</p>

<h3 align=center>
2. LVM Partitioning
</h3>
<p align=center>
  Disk partitioning was made manually, following the subject's structure. We had to use <b>Logical Volume Manager</b>, or LVM, which allows us to dinamically partition a disk, based in Physical Volumes (PV's), Volume Groups (VG's) and Logical Volumes (LV's).<br>
   The subject gives us two structure options:<br>
   One for the </b>mandatory</b> part:<br>
   <img width="480" alt="image" src="https://user-images.githubusercontent.com/37090738/152538613-51e218dd-3475-4c58-9754-02a28d5ad75d.png"><br>
   And another one for the <b>bonus</b> part (the one I chose):<br>
   <img width="480" alt="image" src="https://user-images.githubusercontent.com/37090738/152537717-3e5d6ea3-3294-4979-8483-68e080db608b.png"><br>
</p>

<h3 align=center>
 3. SSH Service
</h3>
<p align=center>
 A SSH Service should be set with some rules and running on specific ports.
</p>

<h3 align=center>
 4. UFW Firewall
</h3>
<p align=center>
 A Firewall was set using <b>Uncomplicated Firewall</b>, or <b>UFW</b>, only allowing connections from specific ports.
</p>

<h3 align=center>
 5. Sudo and Password Policy
</h3>
<p align=center>
A strong password policy was set in place using <b>pam_cracklib</b>, a PAM Module to check the strength of a password.
Also, sudo service was set with a series of strict rules, that grant some additional security to our server.
</p>

<h3 align=center>
 6. Monitoring Script
</h3>
<p align=center>
 Finally, we had to create a monitoring script that shows us some important information about our server. It uses wall to display the information to all users, and crontab to show the message on reboot and every ten minutes.
 The message displayed should be like the following: <br>
 <img width="480" alt="image" src="https://user-images.githubusercontent.com/37090738/152543786-f66a55c8-bcc9-4101-902a-593c7531f968.png"><br>
</p>

<h3 align=center>
 7. Bonus Part
</h3>
<p align=center>
 For the Bonus Part, besides the partitioning, a wordpress website whould be set and hosted by our server, using <b>lighttpd</b>, <b>MariaDB</b> and <b>PHP</b>.
 Furthermore, we should choose and install a package of our choice that we think is useful for our server, being able to justify our choice.
</p>
