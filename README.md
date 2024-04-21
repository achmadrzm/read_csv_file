# read_csv_file
A program that can read and process CSV files and has the option to display the required information

====================================================================================================
Pada sebuah program studi terdapat 4 buah mata kuliah (MK):
MK-A
MK-B
MK-C
MK-D

Tiap mata kuliah memiliki sebuah file nilai mata kuliah dalam format CSV (menggunakan delimiter ;), yaitu:
MK-A.csv
MK-B.csv
MK-C.csv
MK-D.csv
(File-file tersebut dapat diunduh di bagian bawah penjelasan tugas ini).

File-file nilai mata kuliah tersebut berisi data:
Kolom ke-1: NIM mahasiswa yang mengambil MK tersebut
Kolom ke-2: Nama mahasiswa yang mengambil MK tersebut
Kolom ke-3: Nilai yang didapat mahasiswa tersebut.

Sebagai catatan, seorang mahasiswa boleh saja hanya mengambil mata kuliah tertentu. Sehingga NIM dan namanya mungkin hanya tercantum pada beberapa file saja. 

====================================================================================================
Tugas Anda adalah membuatlah sebuah program yang dapat mengolah keempat file CSV tersebut serta memiliki opsi untuk menampilkan informasi berikut:
1. Menampilkan daftar mata kuliah yang diambil seorang mahasiswa beserta nilai yang dia dapatkan. Contoh:
Input: 2488
Output:
NIM: 2488
Nama: Nalani Salgado
Nilai:
MK-A: 99
MK-D: 88

2. Menampilkan rata-rata nilai dari seluruh mata kuliah yang diambil seorang mahasiswa. Contoh:
Input: 2488
Output:
NIM: 2488
Nama: Nalani Salgado
Rata-rata nilai: 93.5

3. Menampilkan nama-nama mahasiswa yang mendapat nilai tertinggi pada sebuah mata kuliah beserta NIM dan nilainya. Contoh:
Input: MK-A
Output:
NIM NAMA NILAI
4330 Charlie Livingston 100
4732 Trevor Patterson 100
1839 Camden Ortiz 100
8875 Hunter Estrada 100
4409 Ashlynn Jordan 100

4. Menampilkan jumlah mahasiswa yang mendapatkan nilai antara: 0-60, 61-75, 76-90, dan 91-100 dari sebuah mata kuliah. Contoh:
Input: MK-A
Output:
0-60: 98
61-75: 162
76-90: 113
91-100: 110

5. Menampilkan sejumlah N mahasiswa yang mendapat nilai rata-rata tertinggi dari seluruh mata kuliah yang dia ambil beserta NIM dan nilai rata-ratanya. Contoh:
Input: 10
Output:
NIM NAMA RATA-RATA
2981 Amalia Bonilla 100
2365 Ricardo Dodson 100
8104 Kairi Figueroa 100
8309 Ashlyn Hawkins 99.5
2073 Trent Colon 99.5
2004 Jasper Beck 99
2552 Deandre Jones 99
4051 Penelope Church 99
6390 Alia Huerta 99
1839 Camden Ortiz 98.5
