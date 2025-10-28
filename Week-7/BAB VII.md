# Struct dalam C dan Python
---
## Tujuan Pembelajaran

1. Memahami konsep struct sebagai tipe data gabungan.
2. Mengimplementasikan struct untuk menyimpan data kompleks.
3. Membandingkan struct dengan class di Python.
---
## Dasar Teori

Struct digunakan untuk menggabungkan variabel dari berbagai tipe data menjadi satu kesatuan logis.  
Dalam Python, konsep serupa dapat direpresentasikan menggunakan **class**.

---
## Implementasi dalam Bahasa C

```c
#include <stdio.h>
#include <string.h>

struct Mahasiswa {
    char nama[50];
    int umur;
    float ipk;
};

int main() {
    struct Mahasiswa mhs;
    strcpy(mhs.nama, "Andi");
    mhs.umur = 20;
    mhs.ipk = 3.5;

    printf("Nama: %s\n", mhs.nama);
    printf("Umur: %d\n", mhs.umur);
    printf("IPK: %.2f\n", mhs.ipk);
    return 0;
}
```
---
## Implementasi dalam Bahasa Python

```python
class Mahasiswa:
    def __init__(self, nama, umur, ipk):
        self.nama = nama
        self.umur = umur
        self.ipk = ipk

mhs = Mahasiswa("Andi", 20, 3.5)
print(f"Nama: {mhs.nama}")
print(f"Umur: {mhs.umur}")
print(f"IPK: {mhs.ipk:.2f}")
```
---
## Latihan

1. Tambahkan atribut `jurusan` pada struct/class.
2. Buat array dari beberapa struct mahasiswa.
3. Buat fungsi untuk menampilkan semua data mahasiswa.
---
## Pertanyaan Refleksi

- Apa keunggulan struct dibanding array?
- Apa perbedaan mendasar antara struct di C dan class di Python?
---
## Referensi

- [C Struct – GeeksforGeeks](https://www.geeksforgeeks.org/structures-in-c/)
- [Python Classes – W3Schools](https://www.w3schools.com/python/python_classes.asp)