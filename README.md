# AGN-UDP By KHALED AGN

THIS IS A SCRIPT FOR AUTO INSTALLATION OF UDP (HYSTERIA SERVER) 



# Client app star tunnel plus

<p>
<a href="https://play.google.com/store/apps/details?id=stp.startunnel.plus"><img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="100"></a>
</p>


# Installation


// Download the script
```
wget https://raw.githubusercontent.com/starrising321/starudp/main/installer_udp.sh
```
// Edit script configuration 
```
nano installer_udp.sh
```
// Install the script
```
chmod +x installer_udp.sh; ./installer_udp.sh
```

systemctl stop hysteria-server.service

systemctl start hysteria-server.service

systemctl status hysteria-server.service

sudo iptables -I INPUT -p tcp -m tcp --dport 36712 -j ACCEPT
sudo iptables -I INPUT -p udp -m udp --dport 36712 -j ACCEPT
ufw allow 36712/udp
ufw allow 36712
## :octocat: by KHALED AGN
<ul>
 <li>TELEGRAM CHANNEL: https://t.me/star_jani</li>
 </ul>
 
## :octocat: Credits

1. [@apernet )
