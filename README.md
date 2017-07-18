Feature script Auto-Install : 

- OpenSSH, port : 22, 80
- Dropbear, port : 143, 443
- Squid3, port : 8080, 3128 (limit to IP SSH)
- Badvpn   : badvpn-udpgw port 7300
- Webmin   : http://IPVPS:10000/
- Nginx    : 81
- OpenVPN TCP 1194
- Script menu : daftar perintah
- Script usernew : membuat akun SSH
- Script trial : membuat akun trial
- Script hapus : menghapus akun SSH
- Script login : melihat login user
- Script member : daftar user
- Script resvis : restart service dropbear, webmin, squid3, openvpn dan ssh
- Script speedtest : speedtest VPS
- Script about : informasi tentang script auto install

Sebelum script Auto Install berikut diinstall, pastikan bahwa VPS Anda mempunyai OS Debian 7 32 Bit. Pastikan juga VPS masih fresh.

Auto-Install Script :-

apt-get install wget && wget https://raw.github.com/silentriders/Debian7/master/debian7.sh && ./debian7.sh
