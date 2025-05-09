<p align="center">
  <img src="https://github.com/G-Force-X/nextvpn/blob/main/original.png?raw=true" alt="Tampilan Menu" width="600"/>
</p>


## SUPPORT OS  
  
➽ Debian 10 & 11 (recommended)   
➽ Ubuntu 20.04   

### CARA INSTALASI :     

1.  :    
<pre><code>apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub</code></pre>

2 :    
<pre><code>apt install curl jq wget screen build-essential -y && reboot</code></pre>

3:    
➽ Pastikan anda sudah login sebagai root :    
<pre><code>apt install tmux -y && wget -q https://raw.githubusercontent.com/G-Force-X/nextvpn/refs/heads/main/home && chmod +x home && tmux new-session -d -s synchvpn './home' && tmux attach -t synchvpn</code></pre>

4 :     
➽ If during the installation connection was lost, login to the vps again and run the command ☞shell

<pre><code>tmux attach -t synchvpn</code></pre>
