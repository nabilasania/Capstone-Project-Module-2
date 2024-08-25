# Capstone-Project-Module-2
(JCDSOL-015) - Nabila Saniaputri Trispantia

## Background
Project ini membahas pengaruh profit dan discount pada penjualan SaaS di berbagai segment. SaaS (Software as a Service) adalah salah satu jenis model layanan cloud computing di mana software sudah siap digunakan tanpa harus melakukan konfigurasi atau instalasi apa pun. Dataset SaaS-Sales yang tersedia mencerminkan penjualan dari sebuah perusahaan SaaS yang mencakup berbagai segmen pasar, produk, dan wilayah geografis. Data ini mencakup informasi penting seperti tanggal pesanan, negara, kota, industri, jenis produk, jumlah penjualan, diskon yang diberikan, dan profit yang dihasilkan.

Dalam persaingan bisnis SaaS (Software as a Service), perusahaan sering mengandalkan strategi diskon untuk menarik pelanggan dan meningkatkan penjualan di berbagai segmen pasar. Pada dasarnya, diskon merupakan salah satu cara untuk mempercepat pengambilan keputusan konsumen dalam membeli produk atau jasa yang ditawarkan. Dengan memberikan diskon, perusahaan dapat menawarkan harga yang lebih murah dibandingkan dengan harga normalnya. Hal ini dapat meningkatkan daya tarik produk atau jasa yang ditawarkan dan membuat konsumen lebih tertarik untuk membeli. Namun, meskipun diskon dapat meningkatkan volume penjualan, diskon juga menimbulkan risiko signifikan terhadap profitabilitas jika tidak dikelola dengan hati-hati.

Link Dataset dapat diakses [disini](https://drive.google.com/drive/folders/1dlpJfgvs8P_IyXqWB4WrNwk91fx0XAzU?usp=sharing)

Source: [revou](https://revou.co/kosakata/saas), [ilmu keuangan](https://www.ilmukeuangan.com/post/diskon-efektif-omzet-dan-laba-meningkat)

## Problem Statement
Perusahaan ingin mengetahui **bagaimana pengaruh diskon terhadap profitabilitas penjualan di berbagai segmen pasar dan produk? Apakah terdapat segmen pasar atau produk tertentu di mana diskon secara signifikan mempengaruhi profitabilitas?**

Dari rumusan ini, kita bisa fokus pada beberapa sub-pertanyaan berikut:

- Apakah ada segmen pasar tertentu di mana diskon lebih berpengaruh terhadap penurunan profit?
- Bagaimana pengaruh diskon terhadap profitabilitas di berbagai kategori produk?
- Apakah ada tingkat diskon tertentu yang masih dapat diterima tanpa mengorbankan profit secara signifikan?
- Apa saja faktor lain selain diskon yang mempengaruhi profitabilitas, dan bagaimana mereka berinteraksi dengan diskon?

## Data Dictionary
Dataset SaaS-Sales terdiri dari 19 kolom yaitu:

|kolom | Penjelasan |
|---- | ---- |
| Row ID | Nomor unik yang mengidentifikasi setiap baris dalam dataset|
| Order ID | Nomor unik yang mengidentifikasi setiap pesanan yang dilakukan oleh pelanggan|
| Order Date | Tanggal ketika pesanan dilakukan|
| Date Key | Representasi numerik dari Order Date dalam format YYYYMMDD |
| Contact Name | Nama kontak utama di perusahaan pelanggan yang melakukan pesanan |
| Country | Negara asal pelanggan yang melakukan pesanan|
| City | Kota asal pelanggan |
| Region | Wilayah tempat pelanggan berada |
| Subregion | Sub-wilayah yang lebih spesifik dari Region|
| Customer | Nama perusahaan atau entitas yang membeli produk atau layanan |
| Customer ID | Nomor identifikasi unik untuk setiap pelanggan |
| Industry | Industri atau sektor ekonomi di mana pelanggan beroperasi|
| Segment | Segmen pasar tempat pelanggan berada |
| Product | Nama produk atau layanan yang dijual |
| License | Nomor lisensi unik yang terkait dengan produk SaaS yang dijual|
| Sales | Jumlah total pendapatan yang dihasilkan dari penjualan produk atau layanan dalam satu transaksi |
| Quantity | Jumlah unit produk yang terjual dalam satu transaksi |
| Discount | Persentase atau nilai diskon yang diberikan pada transaksi tersebut|
| Profit | Keuntungan yang dihasilkan dari transaksi |
