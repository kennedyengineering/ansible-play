following latest tutorial from serversforhackers.com on ansible
run server.yml to use role
feh.yml was from earlier in the tutorial
[link] https://serversforhackers.com/c/an-ansible2-tutorial

# Things to install:
	- aptitude 		(no)
	- ccze			(no)
	- htop			(no)
       	- lolcat		(no)
       	- bash-completion	(config needed)
       	- autossh		(no)
       	- lolcat		(no)
       	- mtr			(no)
       	- dnsutils		(no)
       	- cmatrix		(no)
       	- speedtest-cli		(no)
       	- screen		(no)
       	- tree			(no)
       	- figlet		(no)
       	- wavemon		(no)
       	- netdiscover		(no)
       	- sqlite3		(no)
       	- iftop			(no)
       	- telnet		(no)
       	- iptables-persistent	(no? look more at iptables)
       	- netfilter-persistent	(no?)

# General config:
	- SSH keys
	- disable visual VIM 	(done)
	- login banner
	- unlimited bash memory
	- set timezone
	- iptables for SSH

ansible-playbook -i ./hosts server.yml
