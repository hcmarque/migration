# Migration Strategy and Task
Migration Task - Example on how to migrate the Following:
* Windows Server 2008 R2 and 
* Microsoft SQL Server 2008 R2 to Microsoft Azure;

Migration is a Team Support
1 - People;
2 - Process;
3 - Technology;

# Team
Hugo Marques / Paul Byrd  / Ed Knox / Nathan Swift / Jitendra Singh

## Step 1: Planning
* 1.1 - Let's start the session planning the for the migration.
Please find below the Migration in few steps:

<p align="center">
  <img src="images/migration001.png" alt="drawing" width="600"/>
</p>

# Poject breakdown:
* Tools and technologies that you will use to migrate an existing set of web applications from on-premises to Azure:
 - Azure Migrate;
 - Azure Site Recovery;
 - Azure Data Migration - Microsoft SQL Server 2008 R2 to Microsoft Azure - to Azure SQL DB
 - NSG for Segmentation;
 - Keep the same Application.

* Tools and technologies that you will use to migrate existing identities from on-premises to Azure:
- AD - Need Domain Controller;

* Tools and technologies that you will use to assess your existing environment and determine its baseline cost in Azure:
 - Azure Migrate;

* Design and architect a new baseline environment in Azure, including identity, networking, compute, and security:
 - 

## Step 2: Tools for the Migration
* Azure Migration for the Assess;
* Azure Site Recovery for the Migration - Reference: https://docs.microsoft.com/en-us/azure/site-recovery/migrate-tutorial-windows-server-2008
* Azure Database Migration Service for SQL Server migration

## Step 3: Active Director
On the AD Connect:
Install the AD COnnect (azure active director download)
Must to have the .NET FRamework 4.5.1 or later and Power Shell 3.0  (PSVersionTable)
Add Custom Domain name (contosomortage18.com)
App Service Certificate to select your plan
Active Director Domains and Trust (On the WInd Server) and use the Alternative UPN sufixes)
Make Primary on Custom domain;
check that *Manipulate the default domain; - from Sergio*
Run the syncronization; (azure credentials and local credentials) - select the specify custom sync groups
To check the sync - syncronization service manageron CMAD1


## Step 4: VPN Connection

Provisoining a VPN GW @ On Premise RG;
In order to include the Default GW on VMs - Scope options like default gateway (Router option 03)








