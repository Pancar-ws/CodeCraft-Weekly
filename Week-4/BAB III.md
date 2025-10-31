# Looping (Perulangan) dalam C dan Python
---
## Tujuan Pembelajaran

1. Memahami konsep perulangan dan penggunaannya.
2. Menerapkan struktur `for` dan `while`.
3. Menggunakan loop untuk menyelesaikan permasalahan sederhana.
---
## Dasar Teori

Loop digunakan untuk mengulang eksekusi blok kode selama kondisi tertentu terpenuhi.

---
## Implementasi dalam Bahasa C

```c
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        printf("%d ", i);
    }
    return 0;
}
```
---
## Implementasi dalam Bahasa Python

```python
for i in range(1, 6):
    print(i, end=" ")
```
---
## Studi Kasus

> Buat program yang menampilkan deret bilangan genap dari 2 hingga 10 menggunakan `for`.
---
## Visualisasi

```
i = 1 → cek kondisi → cetak i → tambah i → ulang sampai kondisi salah
```
---
## Latihan

1. Ubah program agar menampilkan bilangan ganjil.
2. Buat versi `while` dari program di atas.
3. Tambahkan fitur menghitung jumlah total seluruh angka yang dicetak.
---
## Pertanyaan Refleksi

- Apa perbedaan `for` dan `while`?
- Kapan sebaiknya menggunakan `while` dibanding `for`?
---
## Referensi

- [C For Loop – Tutorialspoint](https://www.tutorialspoint.com/cprogramming/c_for_loop.htm)
- [Python Loops – W3Schools](https://www.w3schools.com/python/python_for_loops.asp)