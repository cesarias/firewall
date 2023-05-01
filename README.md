<p align="center">
<img src="https://i.imgur.com/eStWstA.png" height="30%" width="30%" alt="Sentinel logo"/>
</p>

<h1>🧱🧱🧱 Azure Firewall 🧱🧱🧱</h1>
Demonstrating steps needed to configure a Firewall in azure.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure  
- Remote Desktop


<h2>Operating Systems Used </h2>

- MAC OS / Windows 10(VM)</b> 


<h2>🧱🧱🧱 Setting up Azure Firewall🧱🧱🧱</h2>

<p>
<img src="https://i.imgur.com/Zq6V9m4.png"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Create resource group within Azure subscription.  
</p>
<br />

<p>
<img src="https://i.imgur.com/ZtwruWv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Create subnets for the Virtual Network. 
</p>
<br />

<p>
<img src="https://i.imgur.com/FPZBuiH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Quick look at the Azure Resources created to be used in setting up the firewall. 
</p>

<p>
<img src="https://i.imgur.com/Eod41gm.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Topology view of the Azure resources.</p>

<p>
<img src="https://i.imgur.com/sTrxOff.png" width="80%" alt="Disk Sanitization Steps"/>

<p>
 Begin to set up the Firwall.
</p>

<p>
<img src="https://i.imgur.com/QeP4rYh.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Adding a Firewall Policy.
</p>

<p>
<img src="https://i.imgur.com/mwOZ01L.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Firewall has deployed
</p>

<p>
<img src="https://i.imgur.com/kKNAFrO.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Create a Firewall route to control outbound network access. 
</p>

<p>
<img src="https://i.imgur.com/xn5QO1Z.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Configured an application rule to the firewall policy that will allow access to only google.com
</p>

<p>
<img src="https://i.imgur.com/ajckRdo.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Logging into VM to test firewall policy and we're able to access google.com
</p>                                         
                                                                                    
 <p>
<img src="https://i.imgur.com/Q2KiQvk.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Try to reach another website but action is denied, Firewall policy is working as it should.
                                                                                    
 Thank you for viewing                                                                                   
</p>                                                                                   
                                                                                
 
<br />
