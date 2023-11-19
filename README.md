# install-apache2--dan--nginx

## Apache2
### Login ubuntu server
### Update dan upgrade
```sudo apt update && sudo apt upgrade```
### Install Apache2 
```sudo apt intall apache2```

![image1](https://user-images.githubusercontent.com/150003742/284023653-26444e54-8998-47d1-80cc-ea08e617e8c1.jpg)
### Cek intallasi Apache2
```sudo ufw app list ```
command ini akan menampilkan list dari aplikasi yang bisa di gunakan oleh Uncomplicated Firewall (UFW) di sistem Linux
### Cek Status Layanan Web Server Apache2
```sudo system status apache2```

![image2](https://user-images.githubusercontent.com/150003742/284023662-c7a971fb-9e34-438d-94f9-dcb44481b049.jpg)
### Install net tools 
```sudo apt install net-tools```
### Cek ip address
gunakan command 
```ifconfig```
atau
```Hostname -I```

![image3](https://user-images.githubusercontent.com/150003742/284023665-c8325253-2c9a-4ad9-8026-a813f6654ec4.jpg)
lalu copy ip address
### Apache2 default page
buka browser dan masukan ip address di kolom pencarian

![image4](https://user-images.githubusercontent.com/150003742/284023667-bce2c014-922e-4217-9d2b-a957e567da80.jpg)
anda berhasil
### Buat direktori baru di /var/www/html
```mkdir namadirektori```
contoh : mkdir web
lalu gunakan command cd untuk pergi ke direktori yang telah di buat
```cd namadirektori```
contoh : cd web
![image5](https://user-images.githubusercontent.com/150003742/284023670-2911da88-fd84-4204-a304-243f3e99db78.jpg)
### Buka text editor 
```sudo nano index.html```
masukkan text dengan format html
saya menggunakan :
image 6
### Cek hasil
gunakan web browser dan masukan ip address/namadirektori 
contoh : 192.168.1.11/web/
image 7
## Remote ke Command Prompt (CMD)
gunakan SSH
* buka CMD
* masukkan command ```ssh user@ip address``` contoh : revidyaa@192.168.1.11
* masukan passsword
image 8
## PuTTy
* Download PuTTY melalui browser
* masukan ip address ke dalam Putty
image 9
* login dengan cara memasukan user dan password
image 10
## Ubuntu Desktop
* Download Ubuntu Desktop melalui browser 
* Install Ubuntu di Virtual box
* Setting user dan Password untuk keperluan login
image 11
OS siap di gunakan
 


