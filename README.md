<h1>System Password Cracking</h1>

<h2>Description</h2>
Project consists of setting up multiple Virtual Machines to simulate using different password cracking utilities to crack passwords and encryptions in general and across different Operating Systems.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Command line</b> 
- <b>John the Ripper</b>
- <b>Cain and Abel</b>

<h2>Environments Used </h2>

- <b>Kali Linux VM</b>
- <b>Windows 7 VM</b>

<h2>Project walk-through:</h2>

<h3>Task A: John the Ripper - System Password Cracking</h3>

  1. Create Six different user with different passwords (separate into two groups) and add them to Kali VM. Then use John the Ripper to implement a dictionary attack to crack the passwords (no need to crack all of the passwords). 
<br />
<p align="center">
Creating the Accounts: <br/>
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/142434081/261088994-40d6eeec-e0ca-49ce-a853-6ba50941c25b.png"/>
<br />
<br />
Setting password for each of the created accounts:  <br/>
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/eb25df13-b07d-4e9f-99d6-8c621290768c)"/>
<br />
<br />
Process of getting the txt file and the using jack the ripper to decrypt the password for each user <br/>
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/b7e1df56-13d9-460e-8296-840a7202b6ef"/>
<br />
<br />

  2. Create a list of three users with the simple passsword in Windows 7 VM and use John the Ripper to crack the passwords (no need to crack all the passwords).<br/>
<br />
<p align="center">
Connecting to the Windows 7 through kali <br/>
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/fc949434-6b0c-48a5-b7c6-0e0515b11172)"/>
<br />
<br />
Creating the accounts on the windows 7 machine through kali and then getting the passwords and using jack the ripper to decrypt <br/>
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/f5d3d61a-d178-4481-bedb-fb6465811289"/>
<br />
<br />
  
  3. Use the same set of accounts you created in the previous step, use Cain and Abel to implement either a brute force attack or a dictionary attack to crack the passwords (no need to crack all the passwords).<br/>
<br />
<p align="center">
Setting up a remote desktop from kali to the windows 7 machine and activating Cain and Abel<br/>
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/fbf05d50-f05f-45d8-89e4-ea95609055ed"/>
<br />
<br />
Using cain and able to crack the passwords for the previously created users using cain and abel (in this case through brute force)<br />
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/eace6861-cb65-4c1d-bb48-e456a1675630"/>
<br />
<br />

<h3>Task B: John The Ripper - MD5/ZIP password cracking</h3>
<p align="center">
Saving the zip file to the vmshare for accessing it through the VM<br />
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/3f43150d-7b7c-4e5c-bbbe-24943fcfb7fb)"/>
<br />
<br />
Using Jack the Ripper to crack the password for the encrypted file <br />
<img src="https://github.com/HimothyRobinson/PasswordCrackingLab/assets/142434081/9eccd61f-8d91-4aa4-b3bd-a5c20cde5187"/>



  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
