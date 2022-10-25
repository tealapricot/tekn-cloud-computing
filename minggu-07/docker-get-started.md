## Getting Started Docker

Pertama-tama silahkan daftar akun docker untuk dapat menggunakan docker

https://login.docker.com/
lalu klik sign up
![](images/6.PNG)

Masukkan email dan password lalu klik Sign Up
![](images/7.PNG)

kemudian setelah selesai melakukan registrasi, akun tersebut bisa digunakan untuk login di docker desktop di tombol sign in kanan atas

![](images/8.PNG)

Berikut tampilan docker desktop
![](images/9.PNG)
semua container yang telah dijalankan akan muncul disini.

### Membuat container

buka terminal lalu masukkan perintah berikut
docker run -d -p 80:80 docker/getting-started
lalu jalankan di terminal

![](images/10.PNG)

setelah dijalankan kita coba cek di docker desktop, apakah sudah runnung container yang sudah kita jalankan tadi

![](images/11.PNG)

jikas sudah running maka kita buka web dengan alamat http://localhost:80

![](images/12.PNG)

jika muncul seperti ini berarti container sudah sukses dijalankan