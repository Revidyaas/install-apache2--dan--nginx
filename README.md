# install-apache2--dan--nginx

## Apache2
### Login ubuntu server
### Update dan upgrade
```sudo apt update && sudo apt upgrade```
### Install Apache2 
```sudo apt intall apache2```
image 1
### Cek intallasi Apache2
```sudo ufw app list ```
command ini akan menampilkan list dari aplikasi yang bisa di gunakan oleh Uncomplicated Firewall (UFW) di sistem Linux
### Cek Status Layanan Web Server Apache2
```sudo system status apache2```
image 2
### Install net tools 
```sudo apt install net-tools```
### Cek ip address
gunakan command 
```ifconfig```
atau
```Hostname -I```
image 3
lalu copy ip address
### Apache2 default page
buka browser dan masukan ip address di kolom pencarian
image 4
anda berhasil
### Buat direktori baru di /var/www/html
```mkdir namadirektori```
contoh : mkdir web
lalu gunakan command cd untuk pergi ke direktori yang telah di buat
```cd namadirektori```
contoh : cd web
image 5
### Buka text editor 
```sudo nano index.html```
image 6
masukkan text dengan formal html
saya menggunakan :
image 7
### Cek hasil
gunakan web browser dan masukan ip address/namadirektori 
contoh : 192.168.1.11/web/
image 8
## Remote ke Command Prompt (CMD)
gunakan SSH
* buka CMD
* masukkan command ```ssh user@ip address``` contoh : revidyaa@192.168.1.11
* masukan passsword
image 9
## PuTTy
* Download PuTTY melalui browser
* masukan ip address ke dalam Putty
image 10
* login dengan cara memasukan user dan password
image 11
## Ubuntu Desktop
* Download Ubuntu Desktop melalui browser 
* Install Ubuntu di Virtual box
* Setting user dan Password untuk keperluan login
image 12
 


