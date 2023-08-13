<h1>Active-Directory-Bulk-User-Creation</h1>

<h2>Description</h2>
This is a little project I have used by taking advantage of Josh Madakors Powershell script which will automate and create 1000 users.



<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Open the script "_CREATE_USERS_.ps1": <br/>
<img src="https://i.imgur.com/q6EnqyF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set-ExecutionPolicy Unrestricted (this will enable us to run the script), then change directory to the file location of the script:  <br/>
<img src="https://i.imgur.com/yEYZxhL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run the script: <br/>
<img src="https://i.imgur.com/R2CRMTS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Users are now being created:  <br/>
<img src="https://i.imgur.com/lEA1Fm2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time), go into AD and under users it will show the ones being created :  <br/>
<img src="https://i.imgur.com/KVdwuim.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To see how many users we created we can right click "mydomain" and press "find" this will indicate the total number of users created bottom left:  <br/>
<img src="https://i.imgur.com/ajasFMV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
1000 users created successfully:  <br/>
<img src="https://i.imgur.com/PUAw1Oe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
