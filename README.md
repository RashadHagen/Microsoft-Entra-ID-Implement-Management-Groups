<h1>Microsoft Entra ID – Implement Management Groups</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
In this project, you will work within a Microsoft Azure tenant where centralized governance and controlled access to subscriptions and management groups are required using role-based access control. The task is to configure Microsoft Entra ID so that a Global Administrator or User Access Administrator can manage access privileges across all Azure subscriptions and management groups within the tenant. You will access Microsoft Entra ID through the Azure portal, navigate to the management and properties settings, and enable the appropriate toggle to allow the designated administrator role to manage access at the tenant level. You will then save the configuration to apply the permission change, ensuring it is limited only to Global Administrators or User Access Administrators. As a result, the selected administrator role gains the ability to assign Azure roles across all subscriptions and management groups in the tenant, enabling centralized RBAC management while maintaining defined administrative boundaries.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Microsoft Azure, Microsoft Entra ID</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 11 & Windows Server 2025</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: RBAC = Role-Based Access Control.</b></span>  
<br/><br/><br/>


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Microsoft Entra ID from https://portal.azure.com</b></span>  
<br/><br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b><a href="https://github.com/RashadHagen/How-To-Open-Microsoft-Entra-ID-From-PortaldotAzuredotcom" style="font-family: Arial, sans-serif; font-size: 22px; font-weight: bold;"> (LINK: How To Open Entra ID From portal.azure.com)</b></span>  
  <br/>

<table>
  <tr>
    <td><img src="https://imgur.com/HC3wQdl.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/TqJVTYp.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Manage (far-left column).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/WUW4lK8.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/gAUqR3n.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/2Xxn2jC.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Properties (towards the bottom of the Manage drop-down).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/KDRyFk4.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/B5p8Fwg.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/wlS7UvL.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In the section: Access management for Azure resources, Click: The toggle to “Yes” below the username of the Global Administrator  OR  User Access Administrator you want to manage access privileges.</b></span>  
<br/><br/>


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: This will allow them to manage access to all Azure subscriptions and management groups in this tenant.</b></span>  
<br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: This is only for the Global Administrator  OR  User Access Administrator of that tenant.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0Wtu0rW.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/u7aGnC0.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/F6UKhRw.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/zW1jjHA.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Save (bottom-left).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/VRJ3mHA.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />
