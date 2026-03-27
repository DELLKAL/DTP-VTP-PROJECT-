<h1>VTP & DTP CONFIGURATION</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Intermediate Network Engineering Skills
In this lab, I applied practical switching concepts including:

* VLAN creation, segmentation, and host assignment
* VTP server/client configuration for centralized VLAN management
* DTP mode configuration for controlled trunk negotiation
* Switch‑to‑switch connectivity and trunk verification
* Troubleshooting VLAN propagation and interface issues
* Subnetting and IP addressing across multiple VLANs

This project reflects my growing capability in building and managing scalable Layer 2 network environments.
<br />


<h2>Environments Used </h2>

- <b>Cisco packet Tracer</b> 

<h2>Project walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/VcYsJOC.png" height="1935" alt="image" src="https://github.com/user-attachments/assets/b750eb16-8f1e-407c-a970-e47d9a6de532" />
" height="80%" width="80%" alt="vtp topology"/>
<br />
<br />
Vtp server configurations on the multilayer switch:  <br/>
<img src="https://i.imgur.com/wZRU401.png" height="80%" width="80%" alt="vtp topology"/>
<br />
<br />
All switch configurations Vtp mode switch 0,1-3 are mode client and switch 2 mode transparent: <br/>
<img src="https://i.imgur.com/39Kq6Zq.png" height="80%" width="80%" alt="vtp topology"/>
<br />
<br />
Confirm the ping from pc1 in Vlan 40 on switch 3 to pc0 Vlan 20 on switch 0: all received successfully  <br/>
<img src="https://i.imgur.com/7SwyuLt.png" height="80%" width="80%" alt="vtp topology"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="vtp topology"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
