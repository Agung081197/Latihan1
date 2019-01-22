#latihan 1
# TUTORIAL PENGGUNAAN GIT
Download aplikasi Gitnya terlebih dahulu ya..., Agan bisa mendownloadnya diwebsite resminya yaitu **git-scm.com**
Sesuaikan dengan arsitektur komputer kita ya gan... supaya lebih maksimal ketika digunakan. Setelah selesai di download agan bisa langsung menginstalnya dikomputer agan masing-masing. setelah proses instalasi selesai,
Agan bisa langsung memakai git nya ya....
Tapi sebelum itu agan harus punya akun githubnya terlebih dahulu ya...
# BERIKUT TUTORIALNYA..... SELAMAT MEMBACA.....
1. Masukan user name agan menggunakan syntak berikut : 

*git config --global user.name "user_name_agan"*
![01 user name](https://user-images.githubusercontent.com/45969481/51546051-e2783580-1e95-11e9-8c35-99a84bde04fd.JPG)
2. Masukan Email agan

*git config --global user.email "email_agan"*
![02 email](https://user-images.githubusercontent.com/45969481/51547556-202a8d80-1e99-11e9-9a35-b7ebec96f882.JPG)
3. Masuk ke tempat penyimpanan dimana agan mau menyimpan repository lokal yang akan kita buat, disini saya akan menyimpannya di drive "E"

*cd /e*
![03 tempat menyimpan](https://user-images.githubusercontent.com/45969481/51547786-88796f00-1e99-11e9-81d9-82662a483bb6.JPG)
4. Setelah itu kita buat 1 folder gan.... disini saya membuat foder tersebut dengan nama "BAHASA PEMROGRAMAN 1"

*mkdir BAHASA\ PEMROGRAMAN\ 1*
![04 folder penyimpanan](https://user-images.githubusercontent.com/45969481/51548344-bb703280-1e9a-11e9-82d0-27ed301b7d20.JPG)
5. Kemudian masuk kedalam folder yang telah kita buat tadi.

*cd BAHASA\ PEMROGRAMAN\ 1*
![05 masuk folder](https://user-images.githubusercontent.com/45969481/51548359-c32fd700-1e9a-11e9-95a7-04fa78226a09.JPG)
6. Sesuai dengan judulnya yaitu "Latihan1" maka saya buat foder 1 lagi didalam folder BAHASA PEMROGRAMAN 1 dengan cara yang sama
seperti yang ada pada step 4 dan 5
![06 folder latihan](https://user-images.githubusercontent.com/45969481/51548372-c75bf480-1e9a-11e9-9a04-40257e0b4ab9.JPG)
7. berikut tampilan setelah kita masuk pada folder latihan1
![07 masuk folder latihan](https://user-images.githubusercontent.com/45969481/51548386-cc20a880-1e9a-11e9-9f97-63bf8cc67480.JPG)
8. Sekarang waktunya kita membuat direktori lokal dengan cara berikut

*git init*

Nah, repository baru berhasil di inisialisasi,
![08 direktori lokal](https://user-images.githubusercontent.com/45969481/51548395-d04cc600-1e9a-11e9-9e94-91de5b0be803.JPG)
9. Selanjutnya kita akan menambahkan file baru di direktory kita, disini saya membuatnya dengan nama README.md

*echo "#Latihan 1" >> README.md*
![09 readme md](https://user-images.githubusercontent.com/45969481/51548406-d5aa1080-1e9a-11e9-8853-3242deb52111.JPG)
10. Setelah file README.md kita buat, sekarang waktunya kita untuk menambahkan file tadi kedalam direktori kita dengan cara :

*git add*

![10 menambahkan file baru](https://user-images.githubusercontent.com/45969481/51548413-d93d9780-1e9a-11e9-9269-f31112a8f543.JPG)
11. Selanjutnya agan bisa menyimpan perubahan yang agan lakukan tadi dengan cara

*git commit -m "Komentar Bebas"

![11 menyimpan perubahan](https://user-images.githubusercontent.com/45969481/51548420-de024b80-1e9a-11e9-81cb-1c8915e0c7a1.JPG)
![12 new repository](https://user-images.githubusercontent.com/45969481/51548437-e35f9600-1e9a-11e9-90f5-55df983994f9.JPG)

# Selanjutnya kita akan menghubungkan repositori lokal yang telah kita buat ke repository server kita. Untuk langkah - langkahnya ayo ikutin terus ya,,,,

12. Kita buat repositori servernya terlebih dahulu.... agan bisa membuatnya dengan cara masuk ke akun github yang telah agan buat sebelumnya

Berikut tampilan untuk membuat repositorinya.....

![13 repository server](https://user-images.githubusercontent.com/45969481/51548441-e65a8680-1e9a-11e9-95cc-9bdce0b4c18e.JPG)
![14 copy link](https://user-images.githubusercontent.com/45969481/51548452-e8bce080-1e9a-11e9-8da6-a70c777e8222.JPG)

13. selanjutnya kita akan melakukan remote repository supaya user lain bisa mengakses ya,,,,

*git remote add origin  (URL)*
![15 remote](https://user-images.githubusercontent.com/45969481/51548461-ec506780-1e9a-11e9-8a79-e029a85e61d2.JPG)

14. Setelah itu kita kirim perubahannya ke server kita ya gan...

jangan lupa nanti minta login lho....

agan bisa memasukan user name sama password agan yang sudah dibuat,,,,

*git push -u origin master*
![16 login](https://user-images.githubusercontent.com/45969481/51548471-f1adb200-1e9a-11e9-90ef-5e22d6f3db0d.JPG)
![17 login sukses](https://user-images.githubusercontent.com/45969481/51548476-f4a8a280-1e9a-11e9-8ff2-6f415744f60f.JPG)
15. nah.......

berikut hasilnya,
![18 hasil](https://user-images.githubusercontent.com/45969481/51548484-f7a39300-1e9a-11e9-8bf7-0c08f8ee5e24.JPG)

16. tahap terakhir adalah clone repository,,, yaitu meng copy repository server secara otomatis sehingga membuat satu direktory sesuai dengan 
nama repositorynya

*git clone (url)
![19 cloning](https://user-images.githubusercontent.com/45969481/51548488-fa9e8380-1e9a-11e9-971c-c0eec43682d3.JPG)

# BEGITULAH TUTORIAL PENGGUNAAN GIT
# TERIMAKASIH DAN SAMPAI JUMPA :)



