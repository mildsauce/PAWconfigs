# PAWconfigs</br>
Privileged Access Workstation Configurations for Windows</br>

WindowsFirewallPolicy.wfw</br>
Deny inboud/outbound traffic by default. You must create rules for all processes based on their </br>
executable's path names, ports/protocols, local (your PAW/ESAE network) and remote host (Domain Controllers & such) </br>
IP addresses. Download this wfw file and import into your local or GPO firewall. This will be a template to </br>
build from. Remote Desktop and ICMP to your PAW are optional and good for initial rollout, but should </br>
eventually be disabled. </br>
