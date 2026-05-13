Project Overview


Website personal portfolio yang terdiri dari beberapa halaman: Index, About, Portfolio, Laprak, Contact, dan stylesheet custom.css.
Tujuan utama proyek adalah menampilkan profil, layanan, portofolio, laporan praktikum, informasi kontak, dan peta lokasi menggunakan Bootstrap 5 serta styling tambahan melalui custom.css.


1. index.html

Halaman utama berisi:

Navbar responsif dengan menu Home, About, Portfolio, Laprak, dan Contact.
Hero section dengan background image, judul besar, dan tombol tindakan.
Section layanan (Features) menggunakan card Bootstrap.
Section portofolio berisi gambar proyek menggunakan grid dan card.
Footer dengan informasi lisensi.
Menggunakan Bootstrap Icons dan custom.css untuk styling tambahan.


2. about.html

Halaman profil yang berisi:
Penjelasan singkat tentang pemilik portfolio.
Struktur layout dua kolom mengenai pengalaman, keahlian, dan ringkasan profesional.
Bagian visi dan misi.
Penambahan kelas dan struktur Bootstrap untuk tampilan bersih dan responsif.
Background halaman menggunakan custom.css.


3. contact.html

Halaman untuk menghubungi pemilik portfolio, berisi:
Informasi kontak seperti lokasi, nomor telepon, email, dan tombol WhatsApp.
Setiap item kontak dibungkus dengan link sehingga dapat langsung mengarah ke tujuan (Maps, Telepon, Email, WhatsApp).
Formulir kontak dengan validasi dasar fields.
Embedded Google Maps menggunakan iframe.
Menggunakan layout 2 kolom untuk tampilan rapi.


4. laprak.html

Halaman kumpulan laporan praktikum yang berisi:
Card laporan praktikum berdasarkan mata kuliah.
Badge mata kuliah pada setiap card.
Filter laporan berdasarkan mata kuliah.
Modal detail laporan yang menampilkan ringkasan, tools, dan hasil praktikum.


5. custom.css

File utama untuk styling tambahan mencakup:
Padding body untuk mengimbangi navbar yang fixed.
Efek hover pada feature card (transform dan shadow).
Efek hover pada card laporan praktikum.
Konfigurasi tinggi gambar card portofolio.
Mengatur background hero dan responsive layout.
Set background-image global untuk semua halaman.
Mengubah warna tombol indikator carousel menjadi abu-abu dan dark-gray pada indikator aktif.
Pengaturan tombol disabled dan responsive tweaks.


Cara Penggunaan

Tempatkan semua file HTML pada root folder proyek.

Pastikan custom.css berada pada root folder proyek.

Pastikan folder images/ berisi background dan gambar portofolio.
Pastikan koneksi internet aktif untuk memuat CDN Bootstrap dan Icons.
Jalankan website dengan membuka index.html melalui browser.

Dependencies

Bootstrap 5

Bootstrap Icons

External CDN untuk styling dan script Bootstrap
