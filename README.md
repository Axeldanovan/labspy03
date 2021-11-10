# labspy03

# Latihan 1
# Program Untuk Menampilkan n Bilangan Acak Yang Lebih Kecil Dari 0.5
# Flowchart 

berikut flowchart dari program latihan 1, untuk menampilkan n bilangan acak yang lebih kecil dari 0.5

![Screenshot_376](https://user-images.githubusercontent.com/81457697/141036782-8d1a6df3-a900-47c0-912f-8707fe2df670.png)

# Algoritma
1.print("Tampilkan n bilangan acak yang lebih kecil dari 0.5") - adalah perintah untuk menampilkan judulnya.

2.jumlah = int(input("Masukkan jumlah n: ")) - adalah perintah untuk menginput nilai n tersebut

3.import random - adalah perintah untuk mengimport built-in random yang telah tersedia di python

4.for i in range(jumlah): - adalah perintah untuk i sebagai integer dalam baris jumlah

5.print("data ke", i+1,"=",(random.uniform(0.1,0.5))) - adalah perintah untuk menampilkan hasil yang telah di input dengan ketentuan random uniform mulai dari nilai 0.1 sampai 0.5

# input
![Screenshot_377](https://user-images.githubusercontent.com/81457697/141039577-69c75647-e19e-47aa-9b26-a227868364d4.png)

# output 
![Screenshot_389](https://user-images.githubusercontent.com/81457697/141061163-ce8ec442-1b17-4f05-ae3b-7f4b98fdb527.png)

# latihan 2
# Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan
# flowchart
![Screenshot_381](https://user-images.githubusercontent.com/81457697/141052320-f74445bc-b5bf-465a-8f59-8dd6f3f04d71.png)
![Screenshot_382](https://user-images.githubusercontent.com/81457697/141052345-af669fe0-ca0c-40ee-9429-e5f40c97364f.png)

# algoritma
1.print("Menampilkan bilangan terbesar dari n buah data yang diinput") - adalah perintah untuk menampilkan judul program

2.max = 0 - adalah perintah untuk menampilkan nilai max yang adalah 0

3.while True: - adalah perintah untuk pengulangan hingga waktu yang tidak ditentukan

4.a = int(input("Masukkan Bilangan: ")) - adalah perintah untuk menginput nilai integer

5.if max < a: - adalah perintah untuk tipe data if atau jika, maksimal nilai lebih kecil dari a atau integer

6.max = a - perintah untuk nilai maximal sama dengan a atau integer

7.if a ==0: - perintah untuk tipe data if atau jika a sama dengan 0 maka

8.break - perintah untuk mengakhiri pengulangan, jadi jika menginput nilai 0 maka pengulangan berakhir atau selesai

9.print("Bilangan Terbesar Adalah: ", max) - adalah perintah untuk menampilkan hasil bilangan yang terbesar dari angka-angka yang telah terinput

# input 
![Screenshot_383](https://user-images.githubusercontent.com/81457697/141053464-5666c00b-2576-42eb-aab1-aac3f7e46f1f.png)

# output
![Screenshot_390](https://user-images.githubusercontent.com/81457697/141061219-f59a44ab-2569-4266-ad52-9d63e006f03a.png)

# program 1
# Membuat program sederhana dengan perulangan 

# flowchart
![Screenshot_385](https://user-images.githubusercontent.com/81457697/141057529-34bda7dd-8aa5-49db-9cff-e96ee89fe989.png)

![Screenshot_386](https://user-images.githubusercontent.com/81457697/141057546-ab05d455-0466-4e8e-9f76-8f6a6e51e179.png)

# algoritma
print("Laba Investasi") - adalah untuk menampilkan judul

x = int(input("Uang Modal Awal: ")) - adalah untuk menginput nilai x sebagai modal awal

a = 0*x - a adalah bulan pertama, karena bulan pertama belum memiliki laba, jadi masih 0 dikali dengan x nilai uang modal awal

b = 0*x - b adalah bulan kedua, karena bulan kedua belum memiliki laba, jadi nilai x dari uang modal dikali dengan 0

c = 0.01*x - c adalah bulan ketiga, dan sudah memiliki laba 1%, jadi ditulis 0.01 bentuk sederhana dari 1% dikali dengan modal atau uang awal dengan nilai x

d = 0.01*x - d adalah bulan keempat, dan labanya 1%, jadi ditulis 0.01 dikalikan dengan nilai x yang adalah uang awal atau modal

e = 0.05*x - e adalah bulan kelima, dan laba pada bulan kelima sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

f = 0.05*x - f adalah bulan keenam, dan laba pada bulan keenam sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

g = 0.05*x - g adalah bulan ketujuh, dan laba pada bulan ketujuh sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

h = 0.02*x - h adalah bulan kedelapan, dan laba pada bulan kedelapan sebesar 2%, maka ditulis 0.02 dikalikan dengan nilai x untuk nilai uang awal atau modal

y=[a,b,c,d,e,f,g,h] - adalah untuk menentukan syarat y yang berisi a,b,c,d,e,f,g,h

for i in range(len(y)): - adalah untuk perulangan data dengan isi data y, dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke urutan yang diinputkan dari data y

print("Laba Bulan Ke",i+1 ,"sebesar: ",y[i]) - untuk menampilkan hasil laba dari bulan ke 1 sampai terakhir
z=(a+b+c+d+e+f+g+h) - Z untuk data yang berisi hasil penjumlahan laba dari bulan pertama sampai bulan ke delapan

print("Jumlah Laba Selama 8 Bulan: ",z) - menampilkan hasil dari jumlah laba

# input
![Screenshot_387](https://user-images.githubusercontent.com/81457697/141059179-000d2b86-fceb-494c-99c2-6130871c397b.png)

# output
![Screenshot_388](https://user-images.githubusercontent.com/81457697/141059194-d18a538c-0885-4155-bc23-6edc9cbf7421.png)

