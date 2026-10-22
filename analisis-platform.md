
# Analisis Komparatif Platform: Web, Desktop, dan Mobile

## 1. Tabel Perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| **Bahasa utama** | HTML, CSS, JavaScript, dan TypeScript. Backend dapat menggunakan PHP, Python, Java, atau JavaScript dengan Node.js. | C#, C++, Java, atau JavaScript dengan HTML dan CSS melalui framework seperti Electron. | Kotlin atau Java untuk Android, Swift untuk iOS, serta Dart dengan Flutter untuk pengembangan lintas platform. |
| **Arsitektur** | Umumnya menggunakan arsitektur client-server. Browser bertindak sebagai client yang mengirim permintaan ke server untuk memperoleh halaman atau data. Aplikasi dapat berbentuk multi-page application (MPA) atau single-page application (SPA). | Aplikasi berjalan pada sistem operasi komputer. Arsitekturnya dapat terdiri atas antarmuka pengguna, logika bisnis, dan pengelolaan data. Aplikasi berbasis Electron menggunakan teknologi web dan Node.js untuk menjalankan aplikasi desktop lintas sistem operasi. | Aplikasi berjalan pada sistem operasi perangkat mobile. Arsitektur umumnya memisahkan antarmuka pengguna, logika aplikasi, dan pengelolaan data. Flutter memungkinkan pengembangan aplikasi Android dan iOS menggunakan satu basis kode. |
| **Cara distribusi** | Diakses melalui browser menggunakan URL tanpa harus memasang aplikasi secara konvensional. Pembaruan dilakukan melalui server sehingga pengguna dapat mengakses versi terbaru. | Didistribusikan melalui installer, paket aplikasi, situs pengembang, atau toko aplikasi. Aplikasi Electron dapat dikemas untuk Windows, macOS, dan Linux. | Umumnya didistribusikan melalui Google Play Store atau Apple App Store. Aplikasi Flutter dapat dikembangkan untuk Android dan iOS dari satu basis kode, kemudian dikemas sesuai platform tujuan. |
| **Keunggulan** | Mudah diakses dari berbagai perangkat, tidak memerlukan instalasi konvensional, pembaruan terpusat, serta mudah dibagikan melalui tautan. | Dapat terintegrasi dengan sistem operasi, mendukung penggunaan perangkat keras komputer, dan cocok untuk aplikasi produktivitas. Electron memungkinkan penggunaan keterampilan web untuk membuat aplikasi desktop lintas platform. | Praktis digunakan saat bepergian, dapat memanfaatkan fitur perangkat seperti kamera dan GPS, serta memiliki antarmuka yang dioptimalkan untuk layar sentuh. Flutter membantu mengurangi kebutuhan pemeliharaan basis kode terpisah untuk Android dan iOS. |
| **Keterbatasan** | Beberapa fitur bergantung pada browser dan koneksi internet. Akses terhadap perangkat keras dibatasi oleh kemampuan browser dan izin pengguna. | Instalasi dan pembaruan perlu dikelola. Kompatibilitas dan pengujian perlu mempertimbangkan sistem operasi yang berbeda. Aplikasi Electron juga dapat menggunakan sumber daya lebih besar karena membawa runtime sendiri. | Pengembangan perlu mempertimbangkan variasi perangkat, ukuran layar, versi sistem operasi, dan izin privasi. Fitur native tertentu mungkin memerlukan konfigurasi atau kode tambahan. Distribusi melalui toko aplikasi juga mengikuti kebijakan platform. |
| **Contoh aplikasi** | Gmail versi web, Google Docs versi web, dan aplikasi e-commerce berbasis browser. | Visual Studio Code, Slack versi desktop, dan aplikasi desktop berbasis Electron. | WhatsApp Mobile, Google Maps, dan aplikasi mobile perbankan. |

## 2. Analisis dan Kesimpulan

Berdasarkan tabel perbandingan, platform Web, Desktop, dan Mobile memiliki karakteristik, keunggulan, serta keterbatasan yang berbeda.

Platform Web sesuai untuk aplikasi yang membutuhkan akses luas melalui browser dan pembaruan terpusat. Pengguna dapat mengakses aplikasi melalui URL tanpa perlu melakukan instalasi konvensional. Namun, beberapa fitur dan kemampuan aplikasi bergantung pada browser serta koneksi internet.

Platform Desktop lebih sesuai untuk aplikasi produktivitas yang memerlukan integrasi dengan sistem operasi dan sumber daya komputer. Aplikasi desktop dapat dikembangkan menggunakan berbagai bahasa pemrograman dan framework. Meskipun demikian, pengembang perlu memperhatikan kompatibilitas sistem operasi, proses instalasi, serta pemeliharaan aplikasi.

Sementara itu, platform Mobile cocok untuk aplikasi yang membutuhkan mobilitas dan pemanfaatan fitur perangkat, seperti kamera, GPS, sensor, dan layar sentuh. Teknologi seperti Flutter memungkinkan pengembangan aplikasi untuk Android dan iOS menggunakan satu basis kode. Namun, pengembang tetap harus memperhatikan variasi perangkat, versi sistem operasi, izin privasi, dan kebijakan toko aplikasi.

Dengan demikian, pemilihan platform harus disesuaikan dengan kebutuhan pengguna, kompleksitas aplikasi, biaya pengembangan, keamanan, dan perangkat sasaran. Pengembangan lintas platform dapat menjadi alternatif untuk mengurangi duplikasi kode, misalnya menggunakan Electron untuk Desktop dan Flutter untuk Mobile. Namun, keputusan akhir tetap perlu mempertimbangkan performa, kebutuhan integrasi perangkat, serta kemudahan pemeliharaan.

## 3. Referensi

1. Pamungkas, R. (2018). *Teori dan implementasi pemrograman web*. UNIPMA Press. https://eprint.unipma.ac.id/74/

2. Colton, D. (2015). *Introduction to web design and development: HTML, CSS, JavaScript* (4th ed.). https://iwdd.doncolton.com/

3. Cohen, R., & Wang, T. (2014). *GUI design for Android apps*. Apress. https://link.springer.com/book/10.1007/978-1-4842-0382-8

4. Hermansyah, E. N., & Wibowo, A. (2025). *Dasar membangun aplikasi mobile dengan Flutter*. UNW Press. https://unwpress.unw.ac.id/index.php/unwpress/catalog/book/109

5. Jensen, P. B. (2017). *Cross-platform desktop applications: Using Node, Electron, and NW.js*. Manning Publications. https://livebook.manning.com/book/cross-platform-desktop-applications/about-this-book

---

**Catatan:** Referensi di atas digunakan untuk mendukung pembahasan pengembangan web, antarmuka Android, aplikasi mobile dengan Flutter, dan aplikasi desktop lintas platform. Ketersediaan akses teks lengkap bergantung pada penerbit atau repositori masing-masing.
