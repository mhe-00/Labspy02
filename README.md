# labspy02

![gambar](screenshot1/gambar1.png)


# Lab 2 :  Struktur  Kondisi


# Latihan 1 :


1.	Buat program sederhana dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

# Program :

	#membuat judul program

print(' ')

print('Program menentukan Nilai Terbesar dari 2 bilangan')

	#input bilangan

print(' ')

a = int(input("masukan bilangan pertama: "))

b = int(input("masukan bilangan kedua: "))

	#Menentukan Nilai Bilangan  dengan if else

print(' ')

if a > b:

    maks = a

else:

    maks = b

	#mencetak nilai maksimum

print('Nilai Terbesar adalah %d' % maks)

![gambar](screenshot1/gambar2.png)

# Hasil output program nilai terbesar :

![gambar](screenshot1/gambar3.png)

# Latihan 2 :

1.	Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

def bubble_sort(array):

#jumlah list

    n = len(array)

#perulangan pertama

    for i in range(n):

#perulangan kedua

        for j in range(n - i - 1):

#bandingkan masing-masing elemen

            if array[j] > array[j + 1]:

#jika lebih besar, tukar

                array[j], array[j + 1] = array[j + 1], array[j]

    return array

print(' ')

unordered = [5, 3, 4, 8, 1, 2, 9, 6]

print(bubble_sort(unordered))



![gambar](screenshot1/gambar4.png)

# Hasil output program :

![gambar](screenshot1/gambar5.png)

# Lab 3: Perulangan

# Latihan 1 :

1.	Buat program dengan perulangan bertingkat (nested) for  yang menghasilkan output sebagai berikut :

![gambar](screenshot1/gambar6.png)

# Program :


print(list(range(10)))

print(list(range(1, 11)))

print(list(range(2, 12)))

print(list(range(3, 13)))

print(list(range(4, 14)))

print(list(range(5, 15)))

print(list(range(6, 16)))

print(list(range(7, 17)))

print(list(range(8, 18)))

print(list(range(9, 19)))

![gambar](screenshot1/gambar7.png)

# Hasil output program :

![gambar](screenshot1/gambar8.png)

# Latihan 2 :

1.	Tampilkan n bilangan acak yang lebih kecil dari 0.5
2.	Nilai n diisi pada saat runtime 
3.	Anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

![gambar](screenshot1/gambar11.png)

# Penjelasan alur program :

1.	print("Tampilkan n bilangan acak yang lebih kecil dari 0.5") - adalah perintah untuk menampilkan judulnya.

2.	jumlah = int(input("Masukkan jumlah n: ")) - adalah perintah untuk menginput nilai n tersebut

3.	import random - adalah perintah untuk mengimport built-in random yang telah tersedia di python

4.	for i in range(jumlah): - adalah perintah untuk i sebagai integer dalam baris jumlah

5.	print("data ke", i+1,"=",(random.uniform(0.1,0.5))) - adalah perintah untuk menampilkan hasil yang telah di input dengan ketentuan random   uniform mulai dari nilai 0.1 sampai 0.5

# program :

![gambar](screenshot1/gambar9.png)

# Hasil output perogramnya :

![gambar](screenshot1/gambar10.png)


# Tugas Praktikum 2


1.	Buat repository dengan nama labspy02

2.	Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if.

3.	Uraikan langkah atau algoritmanya pada file README.md, sertakan juga flowchart dan screenshot hasil eksekusi program. Tampilkan 3 kondisi inputan data.

4.	Commit dan push pada repository

5.	submit url repository pada classroom

 
# FLOWCHART


Pada flowchart dibawah ini menunjukan percabangan dengan lebih dari satu kondisi.

![gambar](screenshot1/gambar12.png)

Flowchart diatas menggambarkan proses untuk menentukan input tiga buah bilangan, dari ketiga bilangan tersebut di tampilkan bilangan terbesarnya. Terdapat 3 buah kondisi yang masing-masing mempunyai ketentuan yang harus dipenuhi untuk menentukan apakah masing – masing bilangan tersebut memenuhi syarat.

# Alur flowchart diatas dapat saya jelaskan seperti berikut :

Apabila suatu bilangan kita inputkan dari yang terkecil sampai yang terbesar maka program tersebut akan menampilkan sebuah bilangan yang terbesar.

# Ini adalah programnya :

![gambar](screenshot1/gambar13.png)

# Ini adalah outputnya :

![gambar](screenshot1/gambar14.png)

# Tugas Praktikum 3


# Latihan 1: latihan1.py


1.	Tampilkan n bilangan acak yang lebih kecil dari 0.5.
2.	nilai n diisi pada saat runtime
3.	anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya
4.	gunakan fungsi random ( ) yang dapat diimport terlebih dahulu

![gambar](screenshot1/gambar15.png)

# program :

![gambar](screenshot1/gambar18.png)

# Penjelasan alur program :

1.	print("Tampilkan n bilangan acak yang lebih kecil dari 0.5") - adalah perintah untuk menampilkan judulnya.

2.	jumlah = int(input("Masukkan jumlah n: ")) - adalah perintah untuk menginput nilai n tersebut

3.	import random - adalah perintah untuk mengimport built-in random yang telah tersedia di python

4.	for i in range(jumlah): - adalah perintah untuk i sebagai integer dalam baris jumlah

5.	print("data ke", i+1,"=",(random.uniform(0.1,0.5))) - adalah perintah untuk menampilkan hasil yang telah di input dengan ketentuan random   uniform mulai dari nilai 0.1 sampai 0.5

# Hasil output program :

![gambar](screenshot1/gambar19.png)


# Latihan 2: latihan2.py


1.	Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk berhenti.

![gambar](screenshot1/gambar16.png)

# program :

![gambar](screenshot1/gambar20.png)


# penjelasan alur program


1.	print("Menampilkan bilangan terbesar dari n buah data yang diinput") - adalah perintah untuk menampilkan judul program
2.	max = 0 - adalah perintah untuk menampilkan nilai max yang adalah 0
3.	while True: - adalah perintah untuk pengulangan hingga waktu yang tidak ditentukan
4.	a = int(input("Masukkan Bilangan: ")) - adalah perintah untuk menginput nilai integer

5.	if max < a: - adalah perintah untuk tipe data if atau jika, maksimal nilai lebih kecil dari a atau integer
6.	max = a - perintah untuk nilai maximal sama dengan a atau integer

7.	if a ==0: - perintah untuk tipe data if atau jika a sama dengan 0 maka
8.	break - perintah untuk mengakhiri pengulangan, jadi jika menginput nilai 0 maka pengulangan berakhir atau selesai

9.	print("Bilangan Terbesar Adalah: ", max) - adalah perintah untuk menampilkan hasil bilangan yang terbesar dari angka-angka yang telah terinput

# Hasil output program :


![gambar](screenshot1/gambar21.png)

# Tugas Praktikum 3

1.	Buat repository baru labpy03
2.	Masukkan latihan1.py dan latihan2.py ke dalam repository.
3.	Buat program sederhana dengan perulangan: program1.py
Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.
4.	buat file README.md, yang berisi penjelasan alur algoritma program latihan1.py, latihan2.py, dan program1.py beserta screenshot hasilnya.
5.	kemudian commit dan push ke repository (github)
6.	kirim url repository ke classroom.

![gambar](screenshot1/gambar17.png)

# Program :

![gambar](screenshot1/gambar22.png)


# Penjelasan alur program


1.	print("Laba Investasi") - adalah untuk menampilkan judul
2.	x = int(input("Uang Modal Awal: ")) - adalah untuk menginput nilai x sebagai modal awal
3.	a = 0*x - a adalah bulan pertama, karena bulan pertama belum memiliki laba, jadi masih 0 dikali dengan x nilai uang modal awal
4.	b = 0*x - b adalah bulan kedua, karena bulan kedua belum memiliki laba, jadi nilai x dari uang modal dikali dengan 0
5.	c = 0.01*x - c adalah bulan ketiga, dan sudah memiliki laba 1%, jadi ditulis 0.01 bentuk sederhana dari 1% dikali dengan modal atau uang awal dengan nilai x
6.	d = 0.01*x - d adalah bulan keempat, dan labanya 1%, jadi ditulis 0.01 dikalikan dengan nilai x yang adalah uang awal atau modal
7.	e = 0.05*x - e adalah bulan kelima, dan laba pada bulan kelima sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal
8.	f = 0.05*x - f adalah bulan keenam, dan laba pada bulan keenam sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal
9.	g = 0.05*x - g adalah bulan ketujuh, dan laba pada bulan ketujuh sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal
10.	h = 0.02*x - h adalah bulan kedelapan, dan laba pada bulan kedelapan sebesar 2%, maka ditulis 0.02 dikalikan dengan nilai x untuk nilai uang awal atau modal
11.	y=[a,b,c,d,e,f,g,h] - adalah untuk menentukan syarat y yang berisi a,b,c,d,e,f,g,h
12.	for i in range(len(y)): - adalah untuk perulangan data dengan isi data y, dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke urutan yang diinputkan dari data y
13.	print("Laba Bulan Ke",i+1 ,"sebesar: ",y[i]) - untuk menampilkan hasil laba dari bulan ke 1 sampai terakhir
14.	z=(a+b+c+d+e+f+g+h) - Z untuk data yang berisi hasil penjumlahan laba dari bulan pertama sampai bulan ke delapan
15.	print("Jumlah Laba Selama 8 Bulan: ",z) - menampilkan hasil dari jumlah laba


# Hasil output program :

![gambar](screenshot1/gambar23.png)

