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

## Data Analyzing

Dari data yang sudah diberikan, dari pihak manajemen DQLab store ingin mengetahui:
1. Overall performance DQLab Store by Years
2. Overall performance DQLab by Sub-Category product yang akan dibandingkan antara tahun 2011 dan tahun 2012
3. Efektifitas dan efisiensi promosi yang telah dilakukan dengan menghitung burn rate dari promosi berdasarkan tahun dan category

## Data Visualization and Discussion

1. Overall performance DQLab Store by Years

    Overall peformance DQLab Store dari tahun 2009 - 2012 untuk jumlah order dan total sales order finished. Overall performance ini diperoleh dari total penjualan (sales) dan jumlah order (number_of_order) dari tahun 2009 sampai 2012 (years). 
    <p align="center">
  <img src="https://github.com/glalitaf/Project-Data-Analysis-for-Retail-Sales-Performance-Report/blob/main/Data/Images/Sales%20Performance%20by%20Years.png" >
</p>
    
2. Overall performance DQLab by Sub-Category product

    Overall performance DQLab by Sub-Category product yang akan dibandingkan antara tahun 2011 dan tahun 2012.
      <p align="center">
  <img src="https://github.com/glalitaf/Project-Data-Analysis-for-Retail-Sales-Performance-Report/blob/main/Data/Images/Producion%20sub%20category%20performance%20in%202011%202012.png" width="600" height="400" >
</p>

3. Efektifitas dan efisiensi promosi

    Pada bagian ini kita akan melakukan analisa terhadap efektifitas dan efisiensi dari promosi yang sudah dilakukan selama ini. Efektifitas dan efisiensi dari promosi yang dilakukan akan dianalisa berdasarkan Burn Rate yaitu dengan membandigkan total value promosi yang dikeluarkan terhadap total sales yang diperoleh.

    DQLab berharap bahwa burn rate tetap berada diangka maskimum 4.5%
   
                                          Formula untuk burn rate : (total discount / total sales) * 100
    dilakukan pembuatan Derived Tables untuk menghitung total sales (sales) dan total discount (promotion_value) berdasarkan tahun(years) dan formulasi persentase burn    rate nya (burn_rate_percentage).
     <p align="center">
  <img src="https://github.com/glalitaf/Project-Data-Analysis-for-Retail-Sales-Performance-Report/blob/main/Data/Images/Promotion%20Effectiveness%20and%20Efficiency%20by%20Years.png" width="600" height="400" >
</p>
