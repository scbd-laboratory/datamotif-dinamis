# Kumpulan contoh data motif dinamis

* dinamis-small.csv - 10.000 Row (Estimasi waktu pemrosesan: 1 - 5 Detik)
* dinamis-medium.csv - 100.000 Row (Estimasi waktu pemrosesan: 7 - 10 Detik)
* dinamis-large.csv - 1.000.000 Row (Estimasi waktu pemrosesan: 15 - 20 Detik)

## Format Data

Berikut merupakan format data, yang dapat diikuti. Pastikan untuk menggunakan separator berupa semicolon ```;```. Data dinamis memiliki kolom ```date``` yang merupakan informasi tanggal. 

date | source | target 
--- | --- | --- 
29/01/2021 | NODE A | NODE B 
29/01/2021 | NODE B | NODE C 
29/01/2021 | NODE D | NODE B 
29/01/2021 | NODE A | NODE D 

