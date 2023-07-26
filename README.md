# 
<p align="center">
<img src="https://cdn-dhhph.nitrocdn.com/YwrWfrMMnPrQoiMcCnngShsqFHLItupA/assets/images/optimized/rev-63bfebd/wp-content/uploads/2017/06/Azure-Backup.png"/>
</p>

<h1>Implementing Microsoft Azure Backup</h1>
This tutorial outlines how to create and configure effective backup policies for Azure virtual machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Rhyme
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Project Outilne</h2>

- Create a Recovery Vault
- Configure Backup Policies
- Create an Azure Virtual Machine
- Implement Azure VM Backup

<h2></h2>

<p>
<img src="https://github.com/kyanahenry/azure-backup/assets/137842747/7fe9e5e3-9b77-4229-8075-e6c620473df7"/>
</p>
<p>
Azure stores backup data in Recovery Vaults, so we want to begin by creating one. For this example, I've named the Recovery Vault 'RhymeRecoveryVault'.
</p>
<br />

<p>
<img src="https://github.com/kyanahenry/azure-backup/assets/137842747/8879b9d7-611c-4586-8743-187f0f555bc8"/>
</p>
<p>
Now, let's navigate to the new resource we created and find 'Backup Policies' in the left menu. Here, we can create policies for daily, weekly, monthly, and yearly backup points. It's important to make sure the backup is scheduled during non-peak business hours, so let's use 2:00 am for this example. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
