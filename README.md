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
