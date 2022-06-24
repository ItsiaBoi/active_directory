# Active Directory Setup

# Install VMs

1. Installed windows server 2022 on vmware
2. Installed windows 11 on vmware 
3. Installed Domain Controller
# Configure Domain Controller
1. User 'sconfig' to:
    - change hostname
    - change ip
    - change dns server
2. Install AD Windows feature:
    - Install-WindowsFeature AD-Domain-Services  
    - IncludeManagementTools    
    - configure DomainController
3. Add Workstation to domain
    - Clone Workstation
    - Change DNS of workstation
    - Join ws to domain
    - login as domain admin


        
