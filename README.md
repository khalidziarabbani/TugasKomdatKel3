# Tugas Komdat Kel 3

### Aplikasi Web "KitchenOwl"

#### Sekilas Tentang

KitchenOwl adalah aplikasi lintas-platform untuk manajemen daftar belanja, penyimpanan resep, pelacak pengeluaran, dan perencana makanan. Aplikasi ini mengikuti desain bahasa Material.

#### Instalasi

##### Prasyarat

Pastikan Anda memiliki VM lokal atau VPS yang menjalankan Linux. Selain itu, pastikan Docker dan git sudah terinstal di sistem.

##### Langkah Instalasi

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

#### Konfigurasi

Beberapa konfigurasi tambahan mungkin diperlukan tergantung pada kebutuhan, seperti mengatur batas upload file atau memori. Namun, untuk penggunaan dasar, konfigurasi standar Docker Compose sudah mencukupi.

#### Maintenance

- Untuk membuat backup database tiap pekan, Anda dapat menggunakan alat seperti `docker exec` untuk menjalankan perintah backup pada kontainer Docker yang sesuai.
- Untuk menghapus direktori sampah, Anda dapat menggunakan cronjob dengan perintah `rm` yang sesuai.

#### Otomatisasi

Anda dapat membuat skrip shell untuk menjalankan langkah-langkah instalasi dan maintenance secara otomatis.

#### Cara Pemakaian

- Akses aplikasi melalui web browser dengan URL: http://20.244.51.50/
- Fungsi-fungsi utama termasuk manajemen daftar belanja, penyimpanan resep, pelacak pengeluaran, dan perencana makanan.

### Pembahasan

#### Pendapat

KitchenOwl adalah aplikasi yang bermanfaat untuk manajemen dapur dan rencana makan. Antarmuka pengguna yang menggunakan desain bahasa Material memudahkan pengguna untuk berinteraksi dengan aplikasi.

#### Kelebihan

- Antarmuka pengguna yang ramah pengguna dan mudah digunakan.
- Fitur lengkap termasuk manajemen daftar belanja, penyimpanan resep, pelacak pengeluaran, dan perencana makanan.

#### Kekurangan

- Proses instalasi awal mungkin sedikit rumit bagi pengguna yang tidak terbiasa dengan Docker dan terminal.

#### Perbandingan dengan Aplikasi Sejenis

Bandingkan dengan aplikasi sejenis seperti AnyList atau Out of Milk, KitchenOwl memiliki antarmuka yang lebih modern dan menyediakan lebih banyak fitur untuk manajemen daftar belanja dan resep.

### Referensi

- GitHub KitchenOwl Repository: [https://github.com/TomBursch/kitchenowl](https://github.com/TomBursch/kitchenowl)
- Docker Compose Documentation: [https://docs.docker.com/compose/](https://docs.docker.com/compose/)

### GitHub Repository

Saya akan membantu Anda dalam membuat repositori GitHub dan mengunggah laporan projek ini. Silakan berikan tautan repositori yang Anda ingin gunakan atau tentukan nama repositori yang ingin Anda gunakan.

link web hosting 20.219.92.39
