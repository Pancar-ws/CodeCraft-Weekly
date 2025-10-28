# Struct
Struct adalah tipe data buatan untuk gabungkan variabel berbeda (seperti kelas sederhana).
## dalam C

```c
#include <stdio.h>
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
### Array Struct

```c
struct Mahasiswa kelas[2];
// Isi seperti di atas
```
## dalam Python (menggunakan Dictionary atau Class)

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