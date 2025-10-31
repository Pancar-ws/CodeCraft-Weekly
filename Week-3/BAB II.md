# Kondisional dalam C dan Python
---
## Tujuan Pembelajaran

1. Menjelaskan konsep percabangan (kondisional).
2. Menerapkan struktur `if`, `else if`, dan `else` pada bahasa C dan Python.
3. Menggunakan operator ternary untuk membuat keputusan sederhana.
---
## Dasar Teori

Kondisional digunakan untuk menentukan alur eksekusi program berdasarkan kondisi tertentu (True/False).

---
## Implementasi dalam Bahasa C

```c
#include <stdio.h>
int main() {
    int nilai;
    printf("Masukkan nilai: ");
    scanf("%d", &nilai);

    if (nilai >= 80) {
        printf("A\n");
    } else if (nilai >= 60) {
        printf("B\n");
    } else {
        printf("C\n");
    }

    return 0;
}
```
---
## Implementasi dalam Bahasa Python

```python
nilai = int(input("Masukkan nilai: "))

if nilai >= 80:
    print("A")
elif nilai >= 60:
    print("B")
else:
    print("C")
```
---
## Studi Kasus

> Buatlah program yang menentukan status kelulusan mahasiswa berdasarkan nilai input.  
> Nilai ≥ 60: "Lulus", selain itu "Tidak Lulus".
---
## Visualisasi

```
[Mulai] → [Input Nilai] → [Cek ≥60?] → [Lulus / Tidak Lulus] → [Selesai]
```
---
## Latihan

1. Modifikasi program untuk menampilkan predikat (A, B, C, D).
2. Tambahkan kondisi agar nilai di luar 0–100 ditolak.
3. Implementasikan versi Python dengan operator ternary.
---
## Pertanyaan Refleksi

- Apa yang terjadi jika kita tidak menuliskan `else` di akhir?
- Mengapa indentasi penting dalam Python?
---
## Referensi

- [C If-Else Statement – Programiz](https://www.programiz.com/c-programming/c-if-else-statement)
- [Python If Statement – W3Schools](https://www.w3schools.com/python/python_conditions.asp