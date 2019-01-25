# DesiredStateConfiguration

Working towards having a set of scripts that will entirely automate building an windows environment within the confines of Hyper-V

  - Configures the Hyper-V host
  - Configures Hyper-V itself
  - Creates and prepares all required virtual disks
  - Creates and prepares all required virtual machines
  - Performs all initial setup tasks on all VM's
  - Ensures all required shares, folders, files and application packages exist where they should
  - Installs all required roles and features on all VM's
  - Builds the domain controller(s) and deploys new AD forest and domain
  - Builds the PKI and deploys AD certificate server(s)
  - Builds DSC Nano Servers
  - Prepares both servers as web pull servers and deploys local configurations to this effect
  - Configure failover between the DSC nano servers
 
