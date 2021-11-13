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

# Hasil output perogram nilai terbesar :

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