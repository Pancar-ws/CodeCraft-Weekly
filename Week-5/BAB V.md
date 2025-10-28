# Array dalam C dan Python
---
## Tujuan Pembelajaran

1. Menjelaskan konsep array dan indeks.
2. Mengimplementasikan array di C dan Python.
3. Memahami perbedaan array statis dan list dinamis.
---
## Dasar Teori

Array adalah kumpulan data sejenis yang disimpan dalam urutan indeks.

- Indeks dimulai dari 0.
- Di C, ukuran array tetap.
- Di Python, list bersifat dinamis.
---
## Implementasi dalam Bahasa C

```c
#include <stdio.h>
int main() {
    int arr[5] = {10, 20, 30, 40, 50};
    for (int i = 0; i < 5; i++) {
        printf("arr[%d] = %d\n", i, arr[i]);
    }
    return 0;
}
```
---
## Implementasi dalam Bahasa Python

```python
arr = [10, 20, 30, 40, 50]
for i in range(5):
    print(f"arr[{i}] = {arr[i]}")
```
---
## Latihan

1. Tambahkan input dari pengguna untuk mengisi array.
2. Buat program menghitung jumlah seluruh elemen array.
3. Buat list 2D (matriks) berisi nilai mahasiswa.
---
## Pertanyaan Refleksi

- Mengapa ukuran array di C tidak bisa diubah?
- Bagaimana Python mengatasi keterbatasan tersebut?
---
## Referensi

- [C Arrays – Programiz](https://www.programiz.com/c-programming/c-arrays)
- [Python Lists – W3Schools](https://www.w3schools.com/python/python_lists.asp)