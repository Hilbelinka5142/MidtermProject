# MidtermProject

# Introduction to Network Automation with Ansible: 
When we are looking at automation today, it is a great tool that has greatly increased efficient managing and maintaining network infrastructure.  Having a network is a must for almost any business, device, app, or data transfer.  And because these networks are getting more and more complex, having the ability to automate tasks becomes needed.  Networks need to be consistent as well as having many rapid changes. Ansible is able to help automation and address these needs. Some of the features that help with this are, ansible is agentless which means that it doesn’t require installations of agents or software on the network devices. Making it very easy to manage many different network devices from different vendors. Ansible also uses playbooks, which are readable and shareable automation scripts.  These can be very complex scripts making it easy to automate monitoring and troubleshooting on the network.
# Overview of Ansible: 
Ansible is an open-source program that allows you to automate specifically for configuring, managing, and setting up systems and infrastructure.  The primary purpose is to automate tasks that are repeated often, as well as configuring management, and just make the management of the complex IT environments a lot easier.  Ansible has a lot of different modules, all of which allow the user to have a wide range of pre-built modules for different tasks that they want to do.  You can also create custom modules to help with specific tasks that meet your specific automation needs. Anisble also has playbooks, which are just the automation scripts that it uses. These paybooks are written in YAML which layout the specific tasks, roles, and plays that are defined for the system.  The playbooks are readable as well as shareable, making it very easy to use.
# Ansible Playbooks: 
The playbooks that I made are config ACLs, config NTP, config OSPF, config VLAN, and config port security.  Each of these are simple chunks of code that help with very simple but used very often tasks. You can add and change what you would like in each one but with config VLAN it looks to see if there is a VLAN already there if not then it creates a VLAN 10 and names it.  ACLs are a more template depending on the type of control list you want to put into place. Setting up the OSPF with this playbook is super simple and easy. All you need to do is change the IP addresses and run the code.  Setting up the NTP playbook is super helpful and makes connecting to a NTP server and setting up the interface very easy. Port security: you are able to configure each port and say whether you want it enabled or not or what kind of settings you want put onto each port.
# Automation in Action: 

![image](https://github.com/Hilbelinka5142/MidtermProject/assets/144185910/9cf948af-f51e-4fb9-8d8a-782afeae654e)
![image](https://github.com/Hilbelinka5142/MidtermProject/assets/144185910/f652f25a-87ac-4701-9eb4-5c5defbd9f6e)
Here are just a couple screenshots showing the outputs.  You can see that the tasks are being implemented.  And how Ansible just makes configuration very simple because all you need to do is run the code.



# Challenges and Lessons Learned: 
When going through this activity, thinking of tasks that can be automated actually took me a little bit of time.  But once I was able to think of one task all the other ones just started to flow and it really just showed how much automation can help with setting up networks.  Another problem that I had was just getting it all running and making sure everything was working properly.  That just took some trial and error to see what code was working and wasn’t. Overall I learned a good amount about creating these playbooks and how much easier it can make things.
# Recommendation for Moving Forward with Ansible: 
I think going forward and using Ansible is a good idea.  It can be a very helpful tool to be able to implement and create networks with automation.





