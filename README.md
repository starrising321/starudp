`✵•.¸,✵°✵.｡.✰  𝓢𝓽𝓪𝓻 𝓣𝓾𝓷𝓷𝓮𝓵 𝓟𝓵𝓾𝓼 ✰.｡.✵°✵,¸.•✵´
ミ◦❧◦°˚°◦.¸¸◦°´❤*•.¸♥ 𝕊ℂℝ𝕀ℙ-𝕌𝔻ℙ By 𝓢𝓽𝓪𝓻 𝓣𝓾𝓷𝓷𝓮𝓵 𝓟𝓵𝓾𝓼 ♥¸.•*❤´°◦¸¸.◦°˚°◦☙◦彡

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
## :octocat: `✵•.¸,✵°✵.｡.✰ 𝔹𝕪 𝕊𝕥𝕒𝕣 𝕋𝕦𝕦𝕟𝕖𝕝 ℙ𝕝𝕦𝕤 𝕋𝕖𝕒𝕞 ✰.｡.✵°✵,¸.•✵´

<p>
<a href="https://t.me/star_jani"><img src="https://edawa.net/wp-content/uploads/Join-telegram.png" height="100"></a>
</p>
 
## :octocat: Credits  ıllıllı⭐🌟 K͙H͙A͙L͙E͙D͙ A͙G͙N͙ 🌟⭐ıllıllı

