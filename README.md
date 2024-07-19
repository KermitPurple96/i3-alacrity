# i3-compton-kitty

Just install kali
instal xct env https://github.com/xct/kali-clean
and execute all these commands https://github.com/KermitPurple96/i3-kitty/blob/main/config.sh


![kali3](https://github.com/user-attachments/assets/daf99662-3a72-4c40-9de3-1053975d50ee)



## Tools
- compton rofi kitty i3 & hack nerd fonts
- fish ZSH zoxide fzf gum peco pwsh & neovim
- incursore rustscan
- gobuster ffuf dirsearch 
- lsd bat
- evil-winrm neo4j bloodhound empire nxc impacket kerbrute wpscan
- red-tldr arsenal
- & many more tools in addition to some personal ones

## config
- to change the desktop background just change /home/$SUDO_USER/.fehbg
- to change between zsh and fish modify las line in /home/$SUDO_USER/.config/kitty/kitty.conf and execute chsh -s /usr/bin/fish

## functions
- tg -> sets a new target
- stop -> Removes the timer that appears when running tg
- mk -> creates an environment for a new target
- ports -> extracts ports from -oG nmap scan and suggest more scans
- shell -> generates reverse shell: shell <IP> <PORT> <SHELL_TYPE>
- recon -> search nmap scripts
- getips -> get the IPsv4 from a file
- getips6 -> get the IPsv6 from a file
- get -> get <n campo> <FS> <archivo> -> Ej: get 4 : file.txt == awk '{print $4} FS=":" file.txt'
- xp -> copy to clipboard
- md4 -> hash md4
- dockerrmc -> delete all containers
- dockerrmi -> deleta all images
- urlencode -> url encode 1st arg
- urldecode -> url decode 1st arg
- hexen -> hexencodes 1st arg
- hexde -> hexdecodes 1st arg
- rot13 -> rot13 cypher
- fibtrie -> extracts ips from /proc/net/fib_trie file
- rmk -> deletes at low level
- extract -> decompress any file
- ftext -> finds string in the current directory recusively
- cpp -> copy with progress bar
- & more!!

