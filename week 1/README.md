`Tugas ini merupakan tugas mata kuliah Konsep Jaringan yang dibimbing oleh Bpk. Dr. Ferry Astika Saputra,ST, M.Sc`

# Installing Debian using VirtualBox

1. **VirtualBox Section**
- Pada menubar Machine, pilih menu New.
![](../assets/debian1.png)
- Setting sesuai dengan masing-masing, klik Next hingga Finish.
![](../assets/debian2.png)
![](../assets/debian3.png)
![](../assets/debian4.png)
![](../assets/debian5.png)

2. **Debian Section**
- Pilih menu Graphical Install.
![](../assets/debian6.png)
- Pilih sesuai dengan masing-masing, jangan lupa isi informasi yang sesuai dan jangan lupa mengisi hostname dengan format SysAdmin-NRP.
![](../assets/debian7.png)
![](../assets/debian8.png)
![](../assets/debian9.png)
![](../assets/debian10.png)
![](../assets/debian11.png)
![](../assets/debian12.png)
![](../assets/debian13.png)
- Pada bagian partition, pilih menu Manual.
![](../assets/debian14.png)
- Buat partition dengan ketentuan berikut:
1. 20GB -> /
2. 5GB -> /storage
3. (remaining) -> swab area
![](../assets/debian15.png)
- Sesudah partition, klik Next hingga Finish.
![](../assets/debian16.png)
![](../assets/debian17.png)
![](../assets/debian18.png)
![](../assets/debian19.png)



# Debian Homeworks

1. Setting user di `visudo`

![](../assets/debian20.png)

2. Maksud dari `less /etc/gr`

Perintah "less /etc/group" digunakan untuk membuka file /etc/group menggunakan program pembaca teks bernama "less" pada sistem Linux atau Unix. File /etc/group adalah salah satu file konfigurasi pada sistem Linux yang menyimpan informasi tentang grup pengguna (user groups).

Ketika Anda menjalankan perintah "less /etc/group", Anda akan melihat isi dari file tersebut. Biasanya, isi file /etc/group terdiri dari baris-baris yang mewakili grup-grup pengguna pada sistem, dan setiap baris memiliki format yang terstruktur.

![](../assets/debian21.png)


3. Perbedaan dari `su` dan `su -`

- su: Beralih ke pengguna lain tanpa mereset lingkungan sepenuhnya. Lingkungan tetap pada pengaturan sebelumnya, seperti variabel lingkungan dan direktori kerja.

- su - atau su -l: Beralih ke pengguna lain dengan mereset lingkungan sepenuhnya, menyamakan dengan lingkungan yang diatur saat pengguna itu melakukan login. Ini termasuk pengaturan direktori kerja, variabel lingkungan, dan konfigurasi lainnya.

![](../assets/debian20.png)