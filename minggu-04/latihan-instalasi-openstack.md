## Mendeploy Openstack menggunakan ubuntu 18.04 dan devstack

### Requirement
- Instalasi fresh ubuntu 18:04
- Minimal memory 4 GB
- Minimal 2 CPU
- Koneksi Internet

### Step 1 : Update Sistem Ubuntu
login ke sistem ubuntu dan dan update apt

![](images/1.PNG)
![](images/2.PNG)
lalu kemudian reboot

### Step 2 : Menambahkan user Stack
Devstack harus dijalankan menggunakan user selain root dan menggunakan sudo. maka perlu dibuat akun baru untuk mengeksekusi dan menjalankan devstack

![](images/3.PNG)

lalu kemudian switch ke stack user untuk test

![](images/4.PNG)

### Step 3 : Download Devstack

Download dari github dengan command berikut

![](images/5.PNG)

Buat file local.conf dengan 4 password dan host IP address

![](images/6.PNG)
![](images/7.PNG)

### Step 4 : Start Openstack Deployment

![](images/8.PNG)

setelah command dijalankan maka proses download dan instalasi akan dimulai

![](images/9.PNG)

### Step 5 : Login ke Openstack Dashboard

Masuk ke IP server dan akses ke dashboard sesuai dengna ip yang telah terserdia

![](images/10.PNG)

![](images/11.PNG)

kemudian login dengan menggunakan user demo atau user admin

![](images/12.PNG)