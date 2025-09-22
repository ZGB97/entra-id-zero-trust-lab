<h1>Cloud Security: Conditional Access, PIM, and Identity Governance in Microsoft Entra ID ☁️🔒</h1>


<h2>Description</h2>
This project demonstrates enterprise access controls in Microsoft Entra ID P2 by configuring Conditional Access, Access Reviews, and Privileged Identity Management (PIM). 
<h4>In this lab I:</h4>

- Enforced MFA for admins
- Simulated audit/recertification processes with Access Reviews
- Implemented just-in-time role activation with PIM

All controls were aligned with NIST SP 800-53 to reflect Zero Trust security principles. I also created an Audit PDF documenting the Access Control Policy and attaching 
evidence screenshots.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Entra ID P2 (Azure AD Premium)</b>
- <b>Microsoft 365 Admin Center</b>
- <b>Conditional Access Policies</b>
- <b>Identity Governance: Access Reviews</b>
- <b>Privileged Identity Management (PIM)</b>
- <b>Azure Sign-in Logs</b> 


<h2>Program Screenshots:</h2>

<p align="center">
Created test users in Entra ID.: <br/>
<img src="https://i.imgur.com/4aaFa6e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured Conditional Access policy.:  <br/>
<img src="https://i.imgur.com/XXNmtRU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Password reset workflow.: <br/>
<img src="https://i.imgur.com/yficGjJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Policy in portal.:  <br/>
<img src="https://i.imgur.com/SO07lua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successful login after MFA.: <br/>
<img src="https://i.imgur.com/0eduKKu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Evidence of Conditional Access being enforced: <br/>
<img src="https://i.imgur.com/8QoE3cN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Group created for governance.: <br/>
<img src="https://i.imgur.com/GjnyAvJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Access Review configuration.: <br/>
<img src="https://i.imgur.com/jN4mmj8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PIM eligibility setup.: <br/>
<img src="https://i.imgur.com/S07bFJF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PIM role settings (MFA + justification).:  <br/>
<img src="https://i.imgur.com/HmQWjY0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
