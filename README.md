# Cara Menggunakan GIT
## Belajar Koneksikan Repository lokal ke Repository Github


### Pertama Buat akun Github dan Buat repository baru
Buat akun github pada github.com lalu jika sudah buat Repository baru
![Gambar 0](screnshoot/ss3.png)
Jika sudah salin link repository yang telah dibuat
![Gambar 1](screnshoot/ss4.png)
### Kedua download dan Install GIT Bash 
Download terlebih dahulu GIT Bash nya dir https://git-scm.com/downloads dan Install seperti Biasa
![Gambar 2](screnshoot/ss5.png)
### Ketiga buat folder repository lokal pada komputer 
Buat folder repository lokal pada komputer seperti pada gambar 
![Gambar 3](screnshoot/ss6.png)
Lalu klik kanan pada folder tersebut dan pilih GIT Bash here
![Gambar 4](screnshoot/ss7.png)
Untuk akses awal diharuskan daftar nama dan email dengan command "git config --global user.name “nama_user” dan git config --global user.email “nama_email”
Jika sudah lakukan clone repository github ke repository lokal dengan command git clone "URL YANG TELAH DI COPY TADI
![Gambar 5](screnshoot/ss8.png) 
Lalu masuk ke repository yang telah di clone dengan command cd "nama direktory" ada tanda (main/master) seperti pada gambar jika behasil masuk ke direktory
![Gambar 6](screnshoot/ss9.png)
Maka kalian sudah berhasil koneksikan repository lokal dengan repository github
jika sudah ada perubahan pada repository lokal bisa di cek dengan command "git status" text yang berwarna merah adalah file yang mengalami perubahan atau penambahan 
![Gambar 7](screnshoot/ss10.png) 
jika sudah ada perubahan pada repository lokal dan ingin upload ke repository github dengan command "git add" untuk add file yang telah mengalami perubahan/penambahan
![Gambar 8](screnshoot/ss11.png) 
jika sudah di add lakukan git commit untuk konfirmasi add dengan command "git commit -m "komentar perubahan"
![Gambar 9](screnshoot/ss12.png) 
lalu lakukan command "git push -u origin main/master" untuk upload ke repository github
![Gambar 10](screnshoot/ss13.png) 

## Maka file perubahan telah terupload pada repository github
![Gambar 11](screnshoot/ss14.png) 

#### Selesai

