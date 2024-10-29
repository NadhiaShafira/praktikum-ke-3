# praktikum ke 2- Struktur Kondisi

Nama = Nadhia Shafira

Kelas = TI.24.A.5

NIM = 312410498

Mata Kuliah = Bahasa Pemograman

# penggunaan stuktur kondisi menggunakan statsment ```if```,```else``` dan ```elif``` dalam python

Dalam Python, ```if``` dan ```else``` digunakan untuk pengambilan keputusan berdasarkan kondisi tertentu. Program akan mengeksekusi blok kode tertentu jika kondisi pada ```if``` bernilai True, dan blok lainnya (yang berada di dalam ```else```) jika kondisi tersebut ```False```

apa itu ```elif```?

```elif``` adalah singkatan dari ```else if```." Ini digunakan dalam struktur kontrol ```if``` untuk menambahkan kondisi tambahan setelah kondisi awal yang diuji. Jika kondisi pertama (yang diawali dengan ```if```) adalah ```False```, maka Python akan memeriksa kondisi-kondisi yang ada di setiap pernyataan ```elif``` secara berurutan. Jika salah satu dari kondisi ```elif``` tersebut adalah True, maka blok kode yang sesuai akan dieksekusi.

# penggunaan ```if``` dan ```else``` untuk gaji karyawan

```python
 if gaji > 3000000:
    print ("gaji sudah di atas UMR")
    if berkeluarga:
        print ("wajib ikutan asuransi dan menabung ntuk pensiun")
```

 memeriksa apakah gaji lebih dari 3.000.000.

jika true akan mencetak "gaji sudah di atas UMR"

memeriksa apakah sudah berkeluarga?

jika true maka akan mencetak "wajib ikutan asuransi dan menabung ntuk pensiun"

```python
else:
    print ("tidak perlu ikutan asuransi")
    if punya_rumah:
        print("wajib bayar pajak rumah")
```
        
jika kurang dari 3.000.000. maka akan mencetak "tidak perlu ikutan asuransi"

```if punya_rumah``` kalau true akan mencetak "wajib bayar pajak rumah"
![foto](https://github.com/NadhiaShafira/Flowchart-/blob/817be615a1aa2c25fa9b75c485c3852a066181d6/gmbr%201%20tgs%20flwchrt.jpg)
# hasil kode program

![foto](https://github.com/NadhiaShafira/Flowchart-/blob/31b9b5d1e07e425a0aed69ab5fec6af14689aea2/Screenshot%202024-10-28%20232514.png)

```python
if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"
```
```if```: Mengecek apakah nilai akhir lebih dari 80.

Jika True, variabel huruf diisi dengan "A", dan program tidak memeriksa kondisi lainnya (blok selesai di sini).

```elif```: (else if) Memeriksa kondisi tambahan jika kondisi pertama (nilai akhir > 80) False.

Jika akhir > 70: Huruf diisi "B". Jika akhir > 50: Huruf diisi "C". Jika akhir > 40: Huruf diisi "D".

```else```: Menangani semua kondisi lainnya (yaitu jika nilai akhir ≤ 40). Dalam kasus ini, huruf diisi dengan "E".
