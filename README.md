# Nama : Naza Sefti Prianita

# NIM : 312210306

# Kelas : TI.22.A3

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Python String|[Click Here](#Python-String)|
|2|Latihan 1|[Click Here](#Latihan1)|
|3|Latihan 2|[Click Here](#Latihan2)|

# Python String

- String adalah jenis yang paling populer di Python.

- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.

- Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

- Membuat string semudah memberikan nilai pada sebuah variabel.

# Latihan 1

![lat 1](https://user-images.githubusercontent.com/115772516/212949618-31078bda-1278-4f71-821c-675177896b69.jpeg)

# Penjelasan Latihan 1

- Untuk menghitung jumlah karakter,gunakan fungsi len().

        print(len(txt))

- Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [] dan deklarasi nomor dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukkan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir,gunakan index [-1]. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan index [2:5].

        # Mengambil karakter terakhir
        print(txt[-1])
        # Mengambil karakter index ke-2 sampai index ke-4 (llo)
        print(txt[2:5])

- Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.

- Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")).

        # Menghilangkan spasi pada text tersebut (HelloWorld)
        print(txt.replace(" ", ""))

- Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower().

        # Mengubah text menjadi huruf besar
        print(txt.upper())
        # Mengubah text menjadi huruf kecil
        print(txt.lower())

- Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace().

        # Mengganti karakter H dengan karakter J
        print(txt.replace("H", "J"))
        print()

# Output Latihan 1

![image](https://user-images.githubusercontent.com/115772516/212958794-4e686903-bd5d-476c-85e8-a0689404094f.png)

# Latihan 2

![lat 2](https://user-images.githubusercontent.com/115772516/212959009-1e55b0eb-05d0-48e3-b226-569d69ee7de5.jpeg)

# Penjelasan Latihan 2

- Untuk memasukkan variabel ke dalam string, tambahkan kurung kurawal {} untuk menempatkan variabel sebelumnya.

        umur = 19
        txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

        print(txt.format(umur))

# Output Latihan 2

![image](https://user-images.githubusercontent.com/115772516/212959795-9917e404-cc62-4ccc-95a5-d69177348d85.png)

# Selesai
