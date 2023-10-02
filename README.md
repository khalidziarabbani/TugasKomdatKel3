# Tugas Komdat Kel 3
### Aplikasi Web "KitchenOwl"
<h1 align="center"><img src="http://20.244.51.50/icons/Icon-192.png"></h1>


# Sekilas Tentang
[`^ kembali ke atas ^`](#)

**KitchenOwl** adalah sebuah aplikasi lintas-platform yang canggih dan praktis yang dirancang untuk membantu Anda dalam berbagai aspek yang berkaitan dengan dapur dan makanan. Aplikasi ini menyediakan beragam fitur yang berguna, termasuk manajemen daftar belanja, penyimpanan resep, pelacakan pengeluaran, dan perencanaan makanan, semuanya dalam satu platform yang mudah diakses. 

Dengan desain yang mengikuti konsep bahasa Material, KitchenOwl menawarkan tampilan yang intuitif dan modern, memudahkan penggunaan dan navigasi. Dengan aplikasi ini, Anda dapat mengoptimalkan pengalaman berbelanja, mengorganisir koleksi resep Anda, mengontrol pengeluaran dapur, dan merencanakan makanan dengan lebih efisien.

# Prasyarat
[`^ kembali ke atas ^`](#)
- Linux OS (Ubuntu 20.04 LTS atau Debian 11)
- Docker
- Virtual Machine Azure

# Instalasi
[`^ kembali ke atas ^`](#)
1. Login ke server menggunakan ssh
   ```
   ssh khalid@20.244.51.50
   ```
   lalu masukan password virtual machine
2. Docker
   
   Ubuntu: [Panduan Instalasi Docker pada Ubuntu](https://docs.docker.com/engine/install/ubuntu)
   
3. Clone repositori KitchenOwl dari GitHub:
   
    ```bash
    git clone https://github.com/TomBursch/kitchenowl.git
    ```

4. Masuk ke direktori KitchenOwl:

    ```bash
    cd kitchenowl
    ```
5. Mengatur port (opsional)

   ikuti langkah dokumentasi (docker compose) yang ada pada github KitchenOwl [disini](https://docs.kitchenowl.org/self-hosting/)

6. Jalankan aplikasi menggunakan Docker Compose:

    ```bash
    docker-compose up -d
    ```

    Aplikasi web akan dapat diakses melalui http://ip-vm:port

# Konfigurasi
[`^ kembali ke atas ^`](#)

Beberapa konfigurasi tambahan mungkin diperlukan tergantung pada kebutuhan, seperti mengatur batas upload file atau memori. Namun, untuk penggunaan dasar, konfigurasi standar Docker Compose sudah mencukupi.

# Maintenance
[`^ kembali ke atas ^`](#)

- Untuk membuat backup database tiap pekan, Anda dapat menggunakan alat seperti `docker exec` untuk menjalankan perintah backup pada kontainer Docker yang sesuai.
- Untuk menghapus direktori sampah, Anda dapat menggunakan cronjob dengan perintah `rm` yang sesuai.

# Cara Pemakaian
[`^ kembali ke atas ^`](#)

- Akses aplikasi melalui web browser dengan URL: http://20.244.51.50/
- Login
  <h1 align="center"><img src="img/login.png"></h1>
- Setelah login, anda akan masuk ke menu household dan dapat membuat household baru
  <h1 align="center"><img src="img/households.png"></h1>
  <h1 align="center"><img src="img/buathousehold.png"></h1>
  
Di dalam household terdapat berbagai fitur:
1. Anda dapat membuat daftar belanja dengan mencari item belanja yang ingin anda tambahkan pada menu search
<h1 align="center"><img src="img/daftarbelanja.png"></h1>

2. Pada menu resep anda dapat membuat maupun menambahkan resep
- Anda dapat menambahkan resep pada button disebelah kanan bawah
<h1 align="center"><img src="img/Resep.png"></h1>
- Terdapat dua pilihan untuk menambahkan resep, cara pertama anda dapat mengakses website https://cookpad.com/ dan copy-paste pada menu tambahkan resep dari URL
<h1 align="center"><img src="img/buatresep.png"></h1>
    1. Copy-paste link pada website cookpad
<h1 align="center"><img src="img/cookpad.png"></h1>
<h1 align="center"><img src="img/tambahresepdariurl.png"></h1>
    2. Kemudian lengkapi resep yang anda tambahkan dari link cookpad
<h1 align="center"><img src="img/lengkapiresep.png"></h1>
<h1 align="center"><img src="img/tambahkanresep.png"></h1>
    3. Setelah melengkapi anda dapat melihat preview resep yang anda tambahkan
<h1 align="center"><img src="img/previewresep.png"></h1>
- Cara kedua anda dapat menambahkan secara manual
<h1 align="center"><img src="img/tambahresepmanual.png"></h1>

3. Pada menu Meal Planner anda dapat menambahkan jadwal makanan yang telah anda buat pada menu resep
<h1 align="center"><img src="img/meal planner.png"></h1>

4. Pada menu Balances anda dapat mencatat pemasukan maupun pengeluaran
<h1 align="center"><img src="img/balance.png"></h1>
<h1 align="center"><img src="img/pemasukkandanpengeluaran.png"></h1>

# Pembahasan
[`^ kembali ke atas ^`](#)

#### Pendapat

KitchenOwl adalah aplikasi yang bermanfaat untuk manajemen dapur dan rencana makan. Antarmuka pengguna yang menggunakan desain bahasa Material memudahkan pengguna untuk berinteraksi dengan aplikasi.

#### Kelebihan

- Antarmuka pengguna yang ramah pengguna dan mudah digunakan.
- Fitur lengkap termasuk manajemen daftar belanja, penyimpanan resep, pelacak pengeluaran, dan perencana makanan.

#### Kekurangan

- Proses instalasi awal mungkin sedikit rumit bagi pengguna yang tidak terbiasa dengan Docker dan terminal.

#### Perbandingan dengan Aplikasi Sejenis

Bandingkan dengan aplikasi sejenis seperti AnyList atau Out of Milk, KitchenOwl memiliki antarmuka yang lebih modern dan menyediakan lebih banyak fitur untuk manajemen daftar belanja dan resep.

# Referensi
[`^ kembali ke atas ^`](#)

- GitHub KitchenOwl Repository: [https://github.com/TomBursch/kitchenowl](https://github.com/TomBursch/kitchenowl)
- Docker Compose Documentation: [https://docs.docker.com/compose/](https://docs.docker.com/compose/)
