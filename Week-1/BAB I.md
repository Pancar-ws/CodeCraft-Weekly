# Pengantar Variable dan Tipe Data
## Tipe-tipe Data Dasar di Python

Di Python, data memiliki tipe dasar yang menyimpan nilai dengan cara tertentu:
- **int**: Bilangan bulat, contoh: 5, -10.
- **float**: Bilangan desimal, contoh: 3.14, -2.5.
- **str**: Teks, contoh: "Halo".
- **bool**: Benar/salah, contoh: True atau False.

**Contoh di Python:**

```python
umur = 20          # int
tinggi = 170.5     # float
nama = "Andi"      # str
aktif = True       # bool
print(umur, tinggi, nama, aktif)
```

Output: `20 170.5 Andi True`
## Cara Deklarasi dan Inisialisasi Variable di Python

Deklarasi berarti membuat variabel, inisialisasi berarti memberi nilai awal. Di Python, cukup tulis nama_variabel = nilai.

**Contoh:**

```python
# Deklarasi dan inisialisasi sekaligus
nilai_uts = 85
print("Nilai UTS:", nilai_uts)
```
## Cara Mengambil Input dari User menggunakan Fungsi Input()

Gunakan input() untuk meminta masukan dari keyboard. Hasilnya selalu string, jadi konversi jika perlu.

**Contoh:**

```python
nama = input("Masukkan nama: ")
umur = int(input("Masukkan umur: "))  # Konversi ke int
print(f"Halo {nama}, umur {umur} tahun.")
```