

`Tugas ini merupakan tugas mata kuliah Konsep Jaringan yang dibimbing oleh Bpk. Dr. Ferry Astika Saputra,ST, M.Sc`

## Table of Contents
- [Sending Mail to Another Group](#langkah---langkah)




# Langkah - langkah

1. Pertama pastikan resolv.conf terdapat search kelompok3.local, setelah itu masukkan perintah telnet mail.kelompok3.local 25 untuk mengirim pesan
   ke kelompok lain
2. Setelah itu ketikkan 
   MAIL FROM: <pengirim@kelompok3.local>

   RCPT TO:<penerima@kelompok2.local>

   DATA
   halo saya dari kelompok3.local

   . (untuk mengakhiri session ngirim email: . kemudian enter)

   QUIT (untuk mengakhiri session email)

3. Kemudian cek mail di device penerima dengan 2 cara melalui evolution atau menggunakan terminal:
   1. Buka melalui evolution, pastikan akun yang terlogin sesuai dengan yang menerima email kemudian cek pada inbox jika berhasil menerima mail
      maka akan muncul seperti ini:
      
      Menerima mail dari kelompok3.local:

      ![gambar](../assets/sent-telnet.jpg)

      Menerima mail dari kelompok2.local:

      ![gambar](../assets/received-evolution.jpg)

   2. Kemudian jika kita cek pada terminal menggunakan perintah
      telnet kelompok3.local 110
      
      user username (sesuaikan dengan username di debian)
      
      pass password (sesuaikan dengan password di debian)
      
      list (memunculkan list email yang ada di debian)
      
      retr nomerlist (ganti nomerlist sesuai dengan mail yang ingin diperiksa)
      
      quit (jika dirasa sudah cukup)
      
      ![gambar](../assets/received-telnet.jpg)
   