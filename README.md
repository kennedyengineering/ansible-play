following latest tutorial from serversforhackers.com on ansible
run server.yml to use role
feh.yml was from earlier in the tutorial
[link] https://serversforhackers.com/c/an-ansible2-tutorial

# Things to install:
	- is config needed? yes/no
	- aptitude 		(no)
	- ccze			(no)
	- htop			(no)
	- lolcat		(no)
	- bash-completion	(no)
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
	- SSH keys		(done)
	- disable visual VIM 	(done)
	- login banner		(done)
	- unlimited bash memory (done)
	- set timezone		(done)
	- iptables for SSH	(done)

ansible-playbook -i ./hosts server.yml -K

optional: if not ssh keyed use --ask-pass


new command with environments:
ansible-playbook -i environments/remote_deployment server.yml
