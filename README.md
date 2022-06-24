# Active Directory Setup

# Install VMs
1. Server Install
    -Installed Windows Server 2022 on Vmware Workstation
2. Workstation Install
    -Installed Windows 11 on Vmware Workstation
# Configure Domain Controller
1. User 'sconfig' to:
    - change hostname
    - change ip
    - change dns server
2. Install AD Windows feature:
    - Installed Domain Controller
    - Install-WindowsFeature AD-Domain-Services  
    - IncludeManagementTools    
    - configure DomainController
3. Add Workstation to domain
    - Clone Workstation
    - Change DNS of workstation
    - Join ws to domain
    - login as domain admin


        
