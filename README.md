# PAWconfigs</br>
Privileged Access Workstation Configurations for Windows</br>

WindowsFirewallPolicy.wfw</br>
Deny inboud/outbound traffic by default, no rule merge with the local policy store. </br>
You must create rules for all processes based on theirexecutable's path names, ports/protocols, </br>
local (your PAW/Bastion network) and remote host (Domain Controllers & such) IP addresses.</br>
Download this wfw file and import into your local or GPO Windows Firewall settings. This will be a template to </br>
build from. Remote Desktop and ICMP to your PAW are optional and good for initial rollout, but should </br>
eventually be disabled or heavily restricted. </br>
