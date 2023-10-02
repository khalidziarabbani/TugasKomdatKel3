# Tugas Komdat Kel 3
### Aplikasi Web "KitchenOwl"
<h1 align="center"><img src="http://20.244.51.50/icons/Icon-192.png"></h1>


# Sekilas Tentang
[`^ kembali ke atas ^`](#)

**KitchenOwl** adalah sebuah aplikasi lintas-platform yang canggih dan praktis yang dirancang untuk membantu Anda dalam berbagai aspek yang berkaitan dengan dapur dan makanan. Aplikasi ini menyediakan beragam fitur yang berguna, termasuk manajemen daftar belanja, penyimpanan resep, pelacakan pengeluaran, dan perencanaan makanan, semuanya dalam satu platform yang mudah diakses. 

Dengan desain yang mengikuti konsep bahasa Material, KitchenOwl menawarkan tampilan yang intuitif dan modern, memudahkan penggunaan dan navigasi. Dengan aplikasi ini, Anda dapat mengoptimalkan pengalaman berbelanja, mengorganisir koleksi resep Anda, mengontrol pengeluaran dapur, dan merencanakan makanan dengan lebih efisien.

# Prasyarat
[`^ kembali ke atas ^`](#)

1. **Docker**: Pastikan Docker sudah terinstal di sistem Anda. Docker digunakan untuk mengelola kontainer aplikasi. Untuk menginstal Docker pada Ubuntu, jalankan perintah berikut:

    ```bash
    sudo apt update
    sudo apt i#### Prasyaratnstall docker.io
    ```

2. **Docker Compose**: Docker Compose adalah alat yang digunakan untuk mendefinisikan dan menjalankan aplikasi multi-kontainer. Pastikan Docker Compose sudah terinstal. Untuk menginstal Docker Compose pada Ubuntu, jalankan perintah berikut:

    ```bash
    sudo apt install docker-compose
    ```

3. **Git**: Pastikan Git sudah terinstal untuk mengkloning repositori KitchenOwl. Untuk menginstal Git pada Ubuntu, jalankan perintah berikut:

    ```bash
    sudo apt install git
    ```
# Instalasi
[`^ kembali ke atas ^`](#)

1. Clone repositori KitchenOwl dari GitHub:
   
    ```bash
    git clone https://github.com/TomBursch/kitchenowl.git
    ```

2. Masuk ke direktori KitchenOwl:

    ```bash
    cd kitchenowl
    ```

3. Jalankan aplikasi menggunakan Docker Compose:

    ```bash
    docker-compose up -d
    ```

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
- Fungsi-fungsi utama termasuk manajemen daftar belanja, penyimpanan resep, pelacak pengeluaran, dan perencana makanan.

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

### GitHub Repository

Saya akan membantu Anda dalam membuat repositori GitHub dan mengunggah laporan projek ini. Silakan berikan tautan repositori yang Anda ingin gunakan atau tentukan nama repositori yang ingin Anda gunakan.

link web hosting 20.219.92.39
