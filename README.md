# Thunder Chicken Project

This is a proof of concepts (POC) project to spin up Azure DevTest Lab Resource Template using AzureRMPowerShell Scripts stored in GitHub

# High Level Goals:
Spec out the default architecture for the DevTest Lab's Resource Group

Required Resources:
* VNetwork 
* Network Security Groups (Firewall Rules)
* vSubnets
* Virtual Machines
* Storage Accounts
* Policies and Configurations


# Deliverables:
1.      Finalize the defined components and network architecture for the Base Resource Group
2.      Manually create the Base Resource Group 
3.      Capture and store the Base ARM Template
4.      Create the PowerShell Script to: Spin-upRG –Template <Base_Template >
5.      Create the PowerShell Script to: Spin-downRG –Template <Base_Template >
6.      Create the PowerShell Script to: Spin-upVM –Template <WinServer2016_vm >
7.      Create the PowerShell Script to: Spin-downVM –Template < WinServer2016_vm>
8.      Create the PowerShell Script to: Spin-upVM –Template <Windows10_vm>
9.      Create the PowerShell Script to: Spin-downVM –Template < Windows10_vm>
10.   Create and capture ARM Templates for each of the following 4 Resource Groups:  
    a.      AD-DC DevTest Lab
    b.      File Servers DevTest Lab
    c.      SharePoint DevTest Lab
    d.      SCCM DevTest Lab
11.   Setup the AdvSol GitHub Repositories (to hold the PowerShell DSC scripts) for each of the 4 projects above:
    a.      CI-xActiveDirectory
    b.      CI-xFileServers
    c.      CI-xSharePoint
    d.      Endpoint-xSCCM
12.   Identify the DSC Configurations and Resources needed to install and configure these applications, for each of the 4 projects
13.   Start the Deep Dive into DSC:

    Title1: Windows PowerShell Desired State Configuration Fundamentals
    Duration: 2h 57 min
    Presenter: Jeff Hicks
    
    Title2: Advanced Windows PowerShell Desired State Configuration 
    Duration: 3h 10 min
    Presenter: Jeff Hicks
#   T h u n d e r C h i c k e n  
 