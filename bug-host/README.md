download apk termux di [sini](https://apkcombo.com/id/termux/com.termux/download/phone-0.119.0-beta.1-apk) jika sudah terpasang kemudian buka dan ketikan perintah di bawah ini
```
apt update && apt upgrade 
pkg install nmap 
pkg install wget 
nmap -p 80 --script dns-brute.nse (domain )
```
contoh penggunaan :
```
nmap -p 80 --script dns-brute.nse ruangguru.com
```
masukkan perintah di bawah ini untuk mengecek respon bug/host, jika respon bug 200 ok berarti bug bisa di gunakan
```
wget -S (subdomain)
```
contoh penggunaan :
```
wget -S coc-status.ruangguru.com
```
sumber :

https://www.kumpulanremaja.com/2019/04/mencari-bug-host-internet-gratis-dengan-termux.html?m=1#google_vignette
