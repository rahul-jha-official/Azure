# Virtual Machine (VM)
Virtual Machine is a Virtualized Operating System.
A service that cloud providers offer that falls under the category of  IaaS. It is a portion of a machine that is running in an Azure Data Center that you can control. You don't actually have control of Physical machine, but it looks and act like a server that you can control. It support window or linux OS. You can remote into it, install any software you wish, and you only need to pay for it for the time you use it.

Azure VMs are an IAAS offering:
- You can completely customize software that runs a VM.
- Often recomended when you run custom software.

>  Note: You are responsible for configuration, updates and maintenance of software that runs on the VM.

Scenarios when VM is needed:
-  **Testing and Development:** Because VM are easy to deply and configure, they allow you to quickly spin up different OS and application configurations that developer can use for testing.
-  **Run Applications in the cloud:** Cloud-based VM can offer significant cost savings. Often crops up when an organization deploy an application that might need to handle fluctuations in demand.<br>- Shut down VMs when demand drops.</br>- Start VMs up to meet a sudden increase in demand.</br>- Pay only for the resources you use.
-  **Extends Datacenter to the cloud:** Virtaul machines and virtual networks can be used to extend the on-prem datacenter to the cloud.<br>Allows organizations to run apps like SharePoint on azure VMs instead of running them on Physical server.<br>Makes it easier and sometimes even less expensive to deploy apps.
-  **Disaster Recovery:** Extending an on-prem datacenter to the cloud allows you to run apps in the cloud on VMs. If the primary datacenter fails, you can create VMs to run critical apps. Once primary datacenter comes back up, VMs can be shutdown.
-  **Lift and Shift:** Virtual machines are a good choice when you want to move from a physical on-prem server to the cloud. (Create an image of your physical server and create a VM)


**Resource Created with a VM deployment:**
>  Virtual Machine</br>
  Public IP Address</br>
  Network Security Group</br>
  Regular Network Interface (NIC)</br>
  Disk</br>
  Virtual Network (V-Net)</br>
