# Project Data Analysis for Retail Sales Performance Report
## About

Project ini dilakukan untuk menganalisis Sales Performance dari DQLab Store pada tahun 2009-2012. Dataset yang digunakan berisi transaksi dari tahun 2009 sampai dengan tahun 2012 dengan jumlah raw data sebanyak 5500, termasuk di dalamnya order status yang terbagi menjadi order finished, order returned dan order cancelled
Adapun dataset yang sudah diberikan dan akan digunakan pada project ini berisi data sebagai berikut:
1.	OrderID
2.	Order Status
3.	Customer
4.	Order Date
5.	Order Quantity
6.	Sales
7.	Discount %
8.	Discount
9.	Product Category
10.	Product Sub-Category

Nama tabel yang akan digunakan pada project ini adalah dqlab_sales_store <a href="https://github.com/glalitaf/Project-Data-Analysis-for-Retail-Sales-Performance-Report/blob/main/Data/Dataset/dqlab_sales_store.xlsx">link.</a>

## Data Trasnformation
Untuk melakukan analisis dan memenuhi business request diatas dataset terlebih dahulu diekstrak menggunakan SQL. 
SQL statment untuk data  transfromasi data dapat dilihat pada <a href="https://github.com/glalitaf/Project-Data-Analysis-for-Retail-Sales-Performance-Report/blob/main/Data/Dataset/dqlab_sales_store.xlsx">link</a> ini

Dari data yang sudah diberikan, business request DQLab store terdiri dari:

1. Overall performance DQLab Store by Years

    Overall peformance DQLab Store dari tahun 2009 - 2012 untuk jumlah order dan total sales order finished. Overall performance ini diperoleh dari total penjualan (sales) dan jumlah order (number_of_order) dari tahun 2009 sampai 2012 (years). 
 
2. Overall performance DQLab by Sub-Category product

    Overall performance DQLab by Sub-Category product yang akan dibandingkan antara tahun 2011 dan tahun 2012.
    
3. Efektifitas dan efisiensi promosi

    Pada bagian ini kita akan melakukan analisa terhadap efektifitas dan efisiensi dari promosi yang sudah dilakukan selama ini. Efektifitas dan efisiensi dari promosi yang dilakukan akan dianalisa berdasarkan Burn Rate yaitu dengan membandigkan total value promosi yang dikeluarkan terhadap total sales yang diperoleh.

    DQLab berharap bahwa burn rate tetap berada diangka maskimum 4.5%
   
                                   Formula untuk burn rate : (total discount / total sales) * 100
    dilakukan pembuatan Derived Tables untuk menghitung total sales (sales) dan total discount (promotion_value) berdasarkan tahun(years) dan produk sub kategori serta formulasi persentase burn rate nya (burn_rate_percentage).
    

## Data Visualization Retail Sales Performance 
Untuk tahap terakhir dilakukan visualisasi data dengan mempresentasikannya dalam bentuk dashboard.  Dua grafik memperlihatkan sales performance berdasarkan tahun dan produk sub kategori, dua grafik lainnya memperlihatkan efektifitas dan efisiensi promosi.  Dashboard dapat dilihat pada 
<a href="https://public.tableau.com/profile/griya.lalita.f#!/vizhome/SalesPerformanceDashboard_16171963851880/Dashboard1?publish=yes">LINK</a> ini.

<p align="center">
  <img src="https://user-images.githubusercontent.com/80236012/113165038-da816080-926b-11eb-8a5c-aa33d0f7b6c9.png"width="600" height="400">
</p>


     
