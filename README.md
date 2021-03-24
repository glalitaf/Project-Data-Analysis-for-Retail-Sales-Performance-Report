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

Nama tabel yang akan digunakan pada project ini adalah dqlab_sales_store

## Data Analyzing

Dari data yang sudah diberikan, dari pihak manajemen DQLab store ingin mengetahui:
1. Overall performance DQLab Store by Years
2. Overall performance DQLab by Sub-Category product yang akan dibandingkan antara tahun 2011 dan tahun 2012
3. Efektifitas dan efisiensi promosi yang telah dilakukan dengan menghitung burn rate dari promosi berdasarkan tahun dan category

## Data Visualization and Discussion

1. Overall performance DQLab Store by Years
   Overall peformance DQLab Store dari tahun 2009 - 2012 untuk jumlah order dan total sales order finished. Overall performance ini diperoleh dari total penjualan (sales) dan jumlah order (number_of_order) dari tahun 2009 sampai 2012 (years). 
    
2. Overall performance DQLab by Sub-Category product 
   Overall performance DQLab by Sub-Category product yang akan dibandingkan antara tahun 2011 dan tahun 2012
3. Efektifitas dan efisiensi promosi
   Pada bagian ini kita akan melakukan analisa terhadap efektifitas dan efisiensi dari promosi yang sudah dilakukan selama ini.
   Efektifitas dan efisiensi dari promosi yang dilakukan akan dianalisa berdasarkan Burn Rate yaitu dengan membandigkan total value promosi yang dikeluarkan terhadap    total sales yang diperoleh.
   DQLab berharap bahwa burn rate tetap berada diangka maskimum 4.5%
                                                  Formula untuk burn rate : (total discount / total sales) * 100
   dilakukan pembuatan Derived Tables untuk menghitung total sales (sales) dan total discount (promotion_value) berdasarkan tahun(years) dan formulasi persentase burn    rate nya (burn_rate_percentage).
