# Capstone-Project-2 (Supermarket Data Analytics)

# Latar Belakang
Sebuah toko supermarket ingin merekrut data scientist untuk melakukan analisis terhadap aktivitas (penjualan maupun promosi) di tokonya. Toko tersebut merasa sudah melakukan banyak cara tetapi belum ada yang maksimal untuk meningkatkan Revenue penjualan toko.

# Rumusan Masalah
Toko ingin mengetahui 3 hal :

1. Jenis produk yang diminati sehingga bisa menambahkan variansi pada jenis produk tersebut
2. Bentuk campaign/promosi yang cocok untuk customernya
3. Behaviour customer untuk metode pembelian (online/offline)

# Tahap-tahap yang Dilakukan
## 1. Data Understanding dan Cleaning
- Dataset memiliki 2240 baris dan 29 kolom
- Dataset ini memiliki nilai data kosong pada kolom `Income` sebanyak 24 baris
- Data kosong ini bisa kita gantikan dengan nilai 0, tidak perlu dihapus dikarenakan kita bisa beranggapan bahwa customer tersebut tidak memiliki income (tidak bekerja)
- Pada kolom Marital_Status, valuenya berisikan Single, Together, Married, Divorced, Widow, Alone, Absurd, YOLO. Untuk case ini, kita akan membuatnya menjadi 2 jenis saja yaitu Married dan Single.
- Pada kolom Dt_Customer, akan kita konversikan menjadi tahun sehingga kita bisa menambahkan kolom Age
  
## 2. Data Analysis
Menganalisa dataset berdasaarkan beberapa pendekatan :
- Jumlah komplain berdasarkan `ID`, `Education`, `Marital_Status`, `Income`
- Jenis produk yang diminati berdasarkan `Jumlah Transaksi`, `Value Transaksi`, `Income`
- Distribusi `Age` customer supermarket
- Bentuk `Campaign` yang paling efisien
- Jumlah transaksi pada channel `Offline` dan `Online`

## 3. Membuat kesimpulan beserta rekomendasi kepada customer
Memberikan kesimpulan berdasarkan data analysis dan juga rekomendasi yang bertujuan untuk meningkatkan pendapatan supermarket

## 4. Membuat dashboard monitoring 
Membuat dashboard pada tableau yang bertujuan agar memudahkan pihak supermarket untuk memonitoring penjualannya.

# Penutup
Harapannya, data analisis ini dapat membantu pihak toko untuk lebih memahami customernya. Sehingga pihak toko dapat melakukan action seperti campaign yang lebih tepat sasaran untuk meningkatkan penjualan toko.
