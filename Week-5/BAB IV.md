# Fungsi dan Prosedur dalam C dan Python
---
## Tujuan Pembelajaran

1. Menjelaskan konsep fungsi dan prosedur.
2. Membuat dan memanggil fungsi dengan parameter dan return value.
3. Memahami modularitas program.
---
## Dasar Teori

Fungsi adalah blok kode yang dapat digunakan berulang kali.

- **Fungsi** mengembalikan nilai (`return`).
- **Prosedur** hanya menjalankan tugas tanpa mengembalikan nilai.
---
## Implementasi dalam Bahasa C

```c
#include <stdio.h>

int tambah(int a, int b) {
    return a + b;
}

void cetak(char pesan[]) {
    printf("%s\n", pesan);
}

int main() {
    cetak("Halo!");
    printf("Hasil: %d\n", tambah(3, 4));
    return 0;
}
```
---
## Implementasi dalam Bahasa Python

```python
def tambah(a, b):
    return a + b

def cetak(pesan):
    print(pesan)

cetak("Halo!")
print("Hasil:", tambah(3, 4))
```
---
## Latihan

1. Buat fungsi `rata_rata(a, b, c)` yang mengembalikan nilai rata-rata.
2. Buat prosedur `sapa()` yang menampilkan “Selamat datang di praktikum!”.
3. Implementasikan fungsi tanpa parameter yang mengembalikan nilai tetap.
---
## Pertanyaan Refleksi

- Apa manfaat utama penggunaan fungsi dalam program besar?
- Apa perbedaan fungsi dan prosedur dari sisi implementasi?
---
## Referensi

- [C Functions – GeeksforGeeks](https://www.geeksforgeeks.org/functions-in-c/)
- [Python Functions – W3Schools](https://www.w3schools.com/python/python_functions.asp)