# PBI-Kimiafarma
Challenge
Sebagai seorang Big Data Analytics Intern di Kimia Farma, tugas
Anda akan mencakup serangkaian tantangan yang memerlukan
pemahaman mendalam tentang data dan kemampuan analisis. Salah
satu proyek utama Anda adalah mengevaluasi kinerja bisnis Kimia
Farma dari tahun 2020 hingga 2023. Berikut ini adalah task yang
harus anda lakukan:
➢ Importing Dataset to BigQuery
Pada proyek ini anda ditugaskan untuk mengimpor dataset
yang telah disediakan:
- kf_final_transaction.csv (link),
- kf_inventory.csv (link),
- kf_kantor_cabang.csv (link),
- kf_product.csv (link).
Anda harus mengimport keempat dataset tersebut untuk
menjadi tabel pada BigQuery, nama tabelnya merupakan nama
dari dataset, namun tanpa ".csv"
➢ Buat tabel analisa
Pada proyek ini, anda juga diminta untuk membuat tabel analisa
berdasarkan hasil aggregasi dari ke-empat tabel yang sudah
diimport sebelumnya. Berikut ini adalah kolom-kolom yang
mandatory pada tabel tersebut:
● transaction_id : kode id transaksi,
● date : tanggal transaksi dilakukan,
● branch_id : kode id cabang Kimia Farma,
● branch_name : nama cabang Kimia Farma,
● kota : kota cabang Kimia Farma,
● provinsi : provinsi cabang Kimia Farma,
02
Challenge
● rating_cabang : penilaian konsumen terhadap cabang Kimia
Farma
● customer_name : Nama customer yang melakukan
transaksi,
● product_id : kode product obat,
● product_name : nama obat,
● actual_price : harga obat,
● discount_percentage : Persentase diskon yang diberikan
pada obat,
● persentase_gross_laba : Persentase laba yang seharusnya
diterima dari obat dengan ketentuan berikut:
■ Harga <= Rp 50.000 -> laba 10%
■ Harga > Rp 50.000 - 100.000 -> laba 15%
■ Harga > Rp 100.000 - 300.000 -> laba 20%
■ Harga > Rp 300.000 - 500.000 -> laba 25%
■ Harga > Rp 500.000 -> laba 30%,
● nett_sales : harga setelah diskon,
● nett_profit : keuntungan yang diperoleh Kimia Farma,
● rating_transaksi : penilaian konsumen terhadap transaksi
yang dilakukan.
Syntax BigQuery yang telah dibuat dikumpulkan dalam
bentuk link repository di GitHub.
03
Challenge
➢ Create Dashboard Performance Analytics Kimia Farma
Business Year 2020-2023
Pada proyek ini, anda harus membuat sebuah dashboard
analisis kinerja Kimia Farma tahun 2020-2023 di Google Looker
Studio. Dashboard ini anda buat berdasarkan tabel analisa yang
telah anda buat sebelumnya pada BigQuery, sehingga anda
perlu menghubungkan table tersebut ke Google Looker Studio.
Anda dapat mendesain dashboard sesuai dengan kreativitas
anda masing-masing, namun dashboardnya harus
mencangkup:
● Judul Dashboard
● Summary Dashboard
● Filter Control
● Snapshot Data
● Perbandingan Pendapatan Kimia Farma dari tahun ke tahun
● Top 10 Total transaksi cabang provinsi
● Top 10 Nett sales cabang provinsi
● Top 5 Cabang Dengan Rating Tertinggi, namun Rating
Transaksi Terendah
● Indonesia's Geo Map Untuk Total Profit Masing-masing
Provinsi
● Dan analisis lainnya yang dapat anda eksplorasi.
Semua hasil pekerjaan selain dituangkan dalam PPT, juga
diperlukan untuk membuat video presentasi / penjelasan dari
hasil pekerjaannya.
