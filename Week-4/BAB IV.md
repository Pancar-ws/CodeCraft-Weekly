# Fungsi dan Prosedur dalam C dan Python
## Pengertian Fungsi dan Prosedur

- **Fungsi**: Blok kode yang mengembalikan nilai (return).
- **Prosedur**: Blok kode tanpa return (hanya jalankan tugas).
## Deklarasi Fungsi dan Prosedur dalam C
### Deklarasi Fungsi dalam C

```c
int tambah(int a, int b) {  // Fungsi return int
    return a + b;
}
```

Panggil: `int hasil = tambah(3, 4);`
### Deklarasi Prosedur dalam C

```c
void cetak(char pesan[]) {  // Prosedur (void)
    printf("%s\n", pesan);
}
```
### main():

```c
#include <stdio.h>
int main() {
    cetak("Halo!");
    printf("Hasil: %d\n", tambah(3, 4));
    return 0;
}
```
## Deklarasi Fungsi dan Prosedur dalam Python
Di Python, semua adalah fungsi (prosedur jika tanpa return).
### Deklarasi Fungsi dalam Python

```python
def tambah(a, b):  # Fungsi
    return a + b

def cetak(pesan):  # Prosedur
    print(pesan)

# Panggil
cetak("Halo!")
print("Hasil:", tambah(3, 4))
```

