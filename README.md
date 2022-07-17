![database-monitoring](https://user-images.githubusercontent.com/99951561/179403611-3b17afeb-61d5-44ff-a20e-979d5421a8eb.jpg)

Pada project kali ini, kita akan menganalisis database Northwind.

Video Analisis 
https://drive.google.com/file/d/1AC6qHJQmy6D19PayeScQjzY7VDM5ED6g/view?usp=sharing

Data Source :
https://drive.google.com/drive/folders/1fTHrwh_gcLsOFKXHnUzUGEu_APxLoD9i

Di dalam file ipynb tersebut, akan dijelaskan step by step yang akan dilakukan untuk menganalisis dan apa saja yang akan di lakukan
Database akan diimport ke Jupyter Notebook menggunakan SQL, kemudian akan dibuat table menggunakan pandas,
Kemudian akan divisualisasikan menggunakan seaborn, dan matplotlib.
Akan juga ada beberapa uji statistik yaitu uji korelasi dan normalitas menggunakan scipy.
Dialam file ipynb tersebut juga akan menjawab pertanyaan" berikut:

Listdown Question Project Modul 2 Randy Irawani 

General Question
1. Bagaimana konteks bisnis berdasarkan dengan data yang telah diberikan? Silahkan
buat asumsi atau penamaan jika diperlukan.
2. Ada berapa banyak tabel yang disediakan oleh database yang tersedia? Jabarkan
setiap tabelnya!

SQL
1. Apakah tabel OrderDetails, Products, Orders, Customers, dan Categories dapat digabungkan
menjadi 1 tabel? Jika memungkinkan, tampilkan tabel yang memuat informasi
transaksi yang melibatkan kelima tabel tersebut.
2. Berasal dari mana saja negara customer kita? Apa saja perusahaan yang berada di negara tersebut? Serta berapa jumlah total orderan yang mereka lakukan?

Data Manipulation
1. Apakah terdapat anomaly berupa missing values, data duplicate, kesalahan data
formatting, dan/atau inconsistency typing? Jika ada tunjukan serta lakukan
penanganan pada anomaly tersebut.
2. Apakah terdapat tipe data yang berupa datetime pada data? Jika iya, apakah tipe
data yang berupa datetime tersebut dapat dicari tahu selisihnya? Silahkan tampilkan
hasilnya, berikan insight yang sesuai (jika memungkinkan).
3. Darimana saja lokasi Country customer perusahaan? Country mana saja yang paling sering melakukan transaksi? Jabarkan dan berikan insight!

Data Visualisation & Statistics
1. Berikan visualisasi terkait Top 5 sales per customer? bagaimana treatment dan strategi
yang bisa dimanfaatkan dengan melihat adanya tampilan tersebut?
2. Bagaimana persentase Sales berdasarkan Negara? Apa kesimpulan dan insight yang dapat diambil dari plot tersebut?
3. Apakah terdapat perbedaan Sales antara Top 5 Customer? Buktikan dengan uji statistik!
3. Apakah terdapat hubungan antara “Quantity”, “Unit Price”, dan “Sales”? Jika iya, variable mana saja yang paling mempengaruhi satu sama lain? Visualisasikan bentuk hubungannya!

Semoga project berikut bisa memberikan insight yang diperlukan.
