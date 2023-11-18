# install-apache2--dan--nginx

## Apache2
### Login ubuntu server
### Update dan upgrade
> sudo apt update && sudo apt upgrade
### Install Apache2 
> sudo apt intall apache2
image 1
### Cek intallasi Apache2
> sudo ufw app list 
command ini akan menampilkan list dari aplikasi yang bisa di gunakan oleh Uncomplicated Firewall (UFW) di sistem Linux
### Cek Status Layanan Web Server Apache2
> sudo system status apache2
image 2
### Install net tools 
> sudo apt install net-tools
### Cek ip address
gunakan command 
> ifconfig 
atau
> Hostname -I
image 3
copy ip address
### Apache2 default page
buka browser dan masukan ip address di kolom pencarian
image 4
anda berhasil
### Buat direktori baru di /var/www/html
> mkdir namadirektori
contoh : mkdir web
lalu gunakan command cd untuk pergi ke direktori yang telah di buat
> cd namadirektori
contoh : cd web
image 5
###

