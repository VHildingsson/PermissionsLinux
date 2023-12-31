<h1>Correct File Permissions in Linux Home Lab</h1>

<h2>Description and Summary</h2>
Access permissions to files and directories were not aligned with organizational guidelines. With the help of Linux the file and directory permissions can be set in order.
<h2>Tasks completed during project</h2>

- File and directory details checked with ls -la command
- Permission string “drwxrwxrwx” explained
- Removed writing access for other on the project_k.txt file
- Modified permissions for user and group on the hidden .project_x.txt file to ensure read access and remove write permissions
- Removed execute permissions on the drafts directory for group so that it is only accessible for the user.


<br />


<h2>Languages and Utilities Used</h2>

- <b>LinuxOS CLI</b>
- <b>Qwiklabs</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>LinuxOS</b> 

<h2>Project walk-through:</h2>

<p align="center">
Change File Permissions: <br/>
<img src="https://i.imgur.com/jr2E1bU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change File Permissions On Hidden File:  <br/>
<img src="https://i.imgur.com/ao6dj9h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Change Directory Permissions:  <br/>
<img src="https://i.imgur.com/8GBIcUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
