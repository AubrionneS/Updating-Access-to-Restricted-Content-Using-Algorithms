<h1>Updating Access to Restricted Content Using Algorithms</h1>

<h2>Description</h2>
 The organization has an allow list of IP addresses that are identified by the file. Also, there is a separate remove list that identifies IP addresses that should no longer have access to the content. This project utilizes an algorithm to automate updating the "allow_list.txt" file to remove the IP addresses that are no longer applicable.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Requests</b>

<h2>Environments Used </h2>

- <b>VM</b>

<h2>Project Walk-Through:</h2>

<p align="center">
Open the File that Contains the Allow List: <br/>
<img src="https://i.imgur.com/7dN1fYV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/RuFRzEa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Read the File Contents: <br/>
<img src="https://i.imgur.com/lSZtJUR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Convert the String into a List:  <br/>
<img src="https://i.imgur.com/pqOPoTf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Iterate Though the Remove List:  <br/>
<img src="https://i.imgur.com/JdTEitA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove IP Addresses that are on the Remove List:  <br/>
<img src="https://i.imgur.com/tzY5E21.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Update the File with the Revised List of IP Addresses:  <br/>
<img src="https://i.imgur.com/jXwvhFV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Gq7rmG0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
