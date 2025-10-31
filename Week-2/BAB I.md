# Pengantar Variable dan Tipe Data
---
## Tujuan Pembelajaran

Setelah mengikuti praktikum ini, mahasiswa diharapkan mampu:
1. Menjelaskan pengertian variabel dan tipe data dalam pemrograman.
2. Mengimplementasikan tipe data dasar di Python dan C.
3. Menggunakan fungsi `input()` dan konversi tipe data dengan benar.
---
## Dasar Teori

Variabel adalah tempat untuk menyimpan nilai sementara selama program berjalan.  
Tipe data menentukan jenis nilai yang dapat disimpan dalam variabel tersebut.
### Tipe-tipe Data Dasar di Python

- **int**: Bilangan bulat (contoh: 5, -10)
- **float**: Bilangan desimal (contoh: 3.14, -2.5)
- **str**: Teks atau string (contoh: `"Halo"`)
- **bool**: Nilai logika (True atau False)
### Tipe-tipe Data Dasar di C

- **int**: Bilangan bulat
- **float** dan **double**: Bilangan pecahan
- **char**: Karakter tunggal
- **bool** (memerlukan `stdbool.h`): Nilai logika
---
## Implementasi dalam Bahasa C

```c
#include <stdio.h>
#include <stdbool.h>

int main() {
    int umur = 20;
    float tinggi = 170.5;
    char nama[] = "Andi";
    bool aktif = true;

    printf("Umur: %d\n", umur);
    printf("Tinggi: %.1f\n", tinggi);
    printf("Nama: %s\n", nama);
    printf("Aktif: %d\n", aktif);
    return 0;
}
```
---
## Implementasi dalam Bahasa Python

```python
umur = 20          # int
tinggi = 170.5     # float
nama = "Andi"      # str
aktif = True       # bool

print(umur, tinggi, nama, aktif)
```
---
## Studi Kasus

> Buatlah program yang meminta input nama dan umur dari pengguna, kemudian tampilkan sapaan dengan format:  
> “Halo [nama], umur kamu [umur] tahun.”

**Contoh Implementasi Python:**

```python
nama = input("Masukkan nama: ")
umur = int(input("Masukkan umur: "))
print(f"Halo {nama}, umur kamu {umur} tahun.")
```
---
## Latihan

1. Ubah tipe data pada program di atas menjadi `float` dan tampilkan hasilnya.
2. Buat program yang menampilkan hasil penjumlahan dua bilangan input dari pengguna.
3. Jelaskan perbedaan antara tipe data `int` dan `float` melalui contoh.
---
## Pertanyaan Refleksi

- Apa yang terjadi jika kita tidak melakukan konversi tipe data saat menggunakan `input()`?
- Mengapa setiap bahasa pemrograman memiliki tipe data berbeda?
---
## Referensi

- [Python Official Documentation – Data Types](https://docs.python.org/3/library/stdtypes.html
- [C Programming Reference – Data Types](https://en.cppreference.com/w/c/language/type)