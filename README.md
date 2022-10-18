**Hello nama saya Nadya Khairunnisa.Disini saya akan menjelaskan cara penggunaan GIT, yang kita perlukan ialah** *Aplikasi Git, Akun GIT*. Sebelum itu saya akan memberikan tutorial cara penginstallan GIT
##Cara penginstalan GIT 
- Pertama anda harus mendownload Aplikasi GIT, buka website resminya GIT di git-scm.com .
![14](https://user-images.githubusercontent.com/115801823/196491835-bc810dd2-b5db-4b64-8cf2-e57298817460.PNG)
Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support Setelah selesai download klik instal
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.
![13](https://user-images.githubusercontent.com/115801823/196492157-0789ba9e-1d93-451a-ba8e-17d097ea8023.PNG)

##_Cara membuat akun GIT_
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
![12](https://user-images.githubusercontent.com/115801823/196492597-b081f30e-a31a-40c4-a0d6-7e9cbefe7eb6.PNG)
- Pada langkah selanjutnya anda boleh langsung diskip saja.
##_Membuat repository baru_
- Ini adalah tampilan pertama setelah kalian selesai membuat akun GIT.
![11](https://user-images.githubusercontent.com/115801823/196493070-f5e551f6-92b2-40d3-bc52-8c2789f76247.PNG)

- Langkah selanjutnya nanti anda akan alihkan ke tab baru untuk membuat repository baru, isi sesuai inspirasi anda, setelah selesai klik buat repository.
- Lalu nanti ditab baru ada url, url ini akan digunakan untuk remote GITHUB.
![10](https://user-images.githubusercontent.com/115801823/196493309-8b82edbb-c683-4d96-ac78-7f5b42feaeef.PNG)

##_Membuat Repository Local_
- Lalu kita buka file explorer pilih dilocaldisk (c) (atau dimana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here.
![9](https://user-images.githubusercontent.com/115801823/196493500-3771a150-1a94-403f-9d8b-b372bc9eaa2c.PNG)

- Lalu kita menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email "email_user" $ git config --global user.name "nama_user"
![8](https://user-images.githubusercontent.com/115801823/196494197-262eb1c4-848b-45b7-8344-23a943165db0.PNG)

- Buatlah direktori baru dengan menggunakan perintah "mkdir LAB_PEMOGRAMAN1" lalu "cd LAB_PEMOGRAMAN1/".
![2](https://user-images.githubusercontent.com/115801823/196494548-58fe95ba-6404-4997-a017-948410b1085b.PNG)

####_Cara penggunaan GIT dengan perintah dasar git init fungsi perintahnya untuk membuat repository local_
- Lalu jalankan perintah git init untuk membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
![3](https://user-images.githubusercontent.com/115801823/196495026-a26ef0b4-62cc-4696-84c4-b715564153c2.PNG)

- Lalu buat 1 file baru bernama README.md, dengan memasukkan perintah _echo "#LATIHAN_1" >> README.md". Lalu untuk melihat file ketik perintah "ls -l"
![4](https://user-images.githubusercontent.com/115801823/196495442-a265a2c1-cf55-46a8-8f50-66c85f748d8c.PNG)

####_Cara penggunaan GIT dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. kalau ingin melihat infonya ketik perintah git status.
![5](https://user-images.githubusercontent.com/115801823/196495563-0eded39a-1f63-45b7-ae2e-1d830da7ee15.PNG)

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m "komentar commit"
![6](https://user-images.githubusercontent.com/115801823/196495669-5f5be8ca-f095-4928-95ae-d5098f7ae901.PNG)

#### File berhasil tersimpan
- Langkah berikutnya kita kembali ke website GITHUB untuk melihat repository yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_"git remote add origin [url] "DAN PERINTAH GIT CLONE" git clone [url]"_
####_Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/repository server pada local repository (working repository)
- Sudah mengetahui url github nya, lalu ketik perintah git remote add origin [url]. Url nya diganti dengan url github anda https://github.com/nadyakhorun/LATIHANN_1.git
![7](https://user-images.githubusercontent.com/115801823/196496064-b385d043-1d23-47fe-8df7-78ea62a4d43d.PNG)

#### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
- Untuk mengirim perubahan pada local repository ke server gunakan perintah "git push -u origin master". Ingat pada langkah ini kita harus memasukkan username dan password github.
![7](https://user-images.githubusercontent.com/115801823/196496195-94530401-28e3-493a-a310-3721217072e5.PNG)

#### Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repository server.
- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/nadyakhorun/LATIHANN_1.git. jika ingin masuk kediretori gunakan perintah "cd [nama direktori anda]", dan jika ingin melihat semua isi direktori gunakan perintah "ls -l"
![7](https://user-images.githubusercontent.com/115801823/196496485-ec67df01-b17a-4dcc-aceb-6e7f16ea572a.PNG)

- Selesai, jika ingin melihat hasilnya cek dilaman github arahkan ke repository nya.
#### *FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada dikanan atas.*
### *Terima Kasih*
