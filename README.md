[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8274649&assignment_repo_type=AssignmentRepo)


---

## Dataset Description

* Pada challenge ini, data diakses menggunakan `bigquery-public-data` pada Google Cloud Big Query.
* Gunakan database `thelook_ecommerce`.


## Problems

Kamu adalah seorang data analis di The Look yang merupakan salah satu platform e-commerce terbesar di planet Mars. Kamu diminta untuk membuat laporan evaluasi aktivitas penjualan di platform tersebut.

Untuk mempermudah pekerjaan kamu supaya terarah, kamu harus menentukan problem statement dengan success criteria berdasarkan SMART. Namun tantangannya, kamu tentukan problem statement berdasarkan penjabaran-penjabaran analisis dalam bentuk persoalan yang harus kamu jawab menggunakan Query SQL. (SMART akan berdasarkan dari poin-poin penjabaran).


**Poin penjabaran:**

1. Berapa persen jumlah user yang retention dari Januari - Juni 2022 dari total keseluruhan user yang ada? (Asumsi definisi retention minimal melakukan transaksi 6 kali selama periode) Apa kesimpulan/insight yang bisa kamu berikan?
2. Berikan informasi rata-rata, minimum, dan maksimum jumlah transaksi yang dilakukan oleh user loyal? (Tampilkan hanya dalam satu dataframe dan berdasarkan satu query select SQL) Informasi apa yang bisa kamu berikan?
3. Berikan informasi rata-rata, minimum, dan maksimum uang yang dihabiskan oleh user loyal? (Tampilkan hanya dalam satu dataframe dan berdasarkan satu query select SQL) Informasi apa yang bisa kamu berikan?
4. Berasal dari sumber trafik mana saja kebanyakan user loyal akses platform The Look? Informasi apa yang bisa kamu berikan?
5. Apakah ada hubungan antara sumber trafik dengan loyal atau tidaknya seorang user? (Gunakan chi-square test untuk menguji hubungan itu) _Hint: Output tabel query hanya ada dua kolom yaitu kolom 'trafic source' dan 'loyal' (kolom 'loyal' berisikan `ya` dan `tidak` saja.