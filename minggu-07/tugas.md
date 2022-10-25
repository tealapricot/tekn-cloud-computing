## Instalasi image docker Nginx

buka terminal dan buat direktori untuk nginx
![](images/13.PNG)

kemudian kita running perintah untuk membuat container baru dan expose port ke 8080
docker run --name testing-nginx -d -p 8080:80 nginx

![](images/14.PNG)

lalu coba kita cek di docker desktop

![](images/15.PNG)

lalu jika sudah benar-benar suksek running maka kita buka browser dengan alamat
http://localhost:8080/

![](images/16.PNG)

Nginx sukses running