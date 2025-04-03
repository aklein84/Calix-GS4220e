# Calix GS4220e
I wrote this Ansible playbook to help facilitate rebooting my Calix GS4220e router provided by Western Iowa Networks. 

I was having wireless issues with connections getting dropped randomly, and a quick restart of my router corrected the issue. In order to make the process faster or to schedule reboots, with the help of my browser's developer tools, I was able to figure piece together a process to automate this task. 

### Variables
*router_ip* = IP address of the router.

*router_username* = Administrative account used to login to router and issue reboot. ***Stored in vault.***

*router_password* = Password for the above account. ***Stored in vault.***

*pushover_app_token* = [Pushover](https://pushover.net) application token ***Stored in vault.***

*pushover_user_token* = [Pushover](https://pushover.net) user token ***Stored in vault.***
