# Project Title
Prediksi Harga Komoditas Pangan Menggunakan Model Timeseries dengan Metode Autoregressive Integrated Moving Average (ARIMA)

# Project Description
Project ini merupakan bagian dari keikutsertaan saya dalam kompetisi Data Science Playground yang diselenggarakan oleh komunitas Data Science Indonesia. Data awal yang tersedia pada project ini adalah tabel harga tiga komoditas pangan (beras premium, bawang merah, dan daging ayam ras) di 34 provinsi dalam kurun waktu Januari 2018 - Juni 2023.

Tujuan dari project ini adalah memprediksi harga tiga komoditas pangan tersebut dari bulan Juli - September 2023, berdasarkan data harga pangan bulan Januari 2018 - Juni 2023. Adapun tahapan dari pengerjaan project ini adalah sebagai berikut:

<b> 1. Data Understanding </b>          : Identifikasi kolom dan tipe datanya, missing value, format nama kolom, dan sebagainya. Temuan abnormal pada tahapan ini akan dibenahi pada tahap selanjutnya <br>

<b> 2. Data Pre-processing </b>         : Sinkronisasi format nama kolom, imputasi (pengisian) missing value, dan merapikan kolom agar data siap untuk dilakukan proses machine learning modelling <br>

<b> 3. Exploratory Data Analysis  </b>  : Menganalisa pola pergerakan harga tiga komoditas di 34 provinsi. Dari analisa tersebut, disimpulkan bahwa setiap komoditas memiliki pola pergerakan yang berbeda satu sama lain. Adapun perbedaan antar wilayah (Sumatra dengan Jawa, Maluku dengan Sulawesi, etc) memiliki perbedaan pola yang tidak terlalu signifikan. <br>

<b> 4. Machine Learning Modelling and Model Evaluation </b>  : Mencari model ARIMA manakah yang paling tepat untuk prediksi harga masing-masing komoditas. Untuk komoditas bawang merah, prediksi menggunakan model ARIMA (20,2,0). Komoditas  beras premium dengan model ARIMA (1,2,4). Adapun komoditas daging ayam dengan model ARIMA (5,2,2). <br>

<b> 5. Price Forecasting          </b>  : Setelah model machine learning yang sesuai berhasil teridentikasi, barulah prediksi harga tiga bulan kedepan (Juli - September 2023) dapat dilakukan <br>

<b> 6. Kesimpulan dan Rekomendasi </b>  : Hasil Prediksi dapat dijadikan sebagai landasan dalam melakukan strategi pembelian pangan pada tiga bulan mendatang <br>

