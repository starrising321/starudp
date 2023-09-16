# SCRIP-UDP By Star Tunnel Plus

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
chmod +x installer_udp.sh
```
// CMD
```
./installer_udp.sh
```
// Allowed Port
```
sudo ufw allow 10000:65000/udp
ufw enable
```
// Find Json
```
find / -name config.json
```
// Edit Password
```
nano /etc/hysteria/config.json
```
// Command 1
```
systemctl stop hysteria-server.service
```
// Command 2
```
systemctl start hysteria-server.service
```
// Command 3
```
systemctl status hysteria-server.service
```
// Command 4
```
sudo iptables -I INPUT -p tcp -m tcp --dport 36712 -j ACCEPT
sudo iptables -I INPUT -p udp -m udp --dport 36712 -j ACCEPT
ufw allow 36712/udp
ufw allow 36712
```
====================================
## :octocat: By Star Tuunel Plus Team

TELEGRAM Contact: 
 <p>
<a href="https://t.me/star_jani"><img src="https://cdn.icon-icons.com/icons2/3053/PNG/512/telegram_macos_bigsur_icon_189662.png" height="100"></a>
</p>
 
## :octocat: Credits  {-KHALED AGN-}

