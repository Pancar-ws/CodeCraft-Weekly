# Kondisional dalam C dan Python
## Pengantar Kondisional
Kondisional digunakan untuk menjalankan kode berbeda berdasarkan kondisi (true/false), seperti memeriksa nilai lulus atau tidak.
## Kondisional di Bahasa C
### If - Else Statement
```c
#include <stdio.h>
int main() {
    int nilai;
    printf("Masukkan nilai: ");
    scanf("%d", &nilai);
    if (nilai >= 60) {
        printf("Lulus!\n");
    } else {
        printf("Tidak lulus.\n");
    }
    return 0;
}
```
### If - Else If Statement
```c
if (nilai >= 80) {
    printf("A\n");
} else if (nilai >= 60) {
    printf("B\n");
} else {
    printf("C\n");
}
```
## Kondisional di Python
### If - Else Statement
```python
nilai = int(input("Masukkan nilai: "))
if nilai >= 60:
    print("Lulus!")
else:
    print("Tidak lulus.")
```
### If - Else If Statement
```python
if nilai >= 80:
    print("A")
elif nilai >= 60:  # elif = else if
    print("B")
else:
    print("C")
```
## Ternary Operator
Operator singkat untuk if-else sederhana.
### dalam C
```c
char grade = (nilai >= 60) ? 'L' : 'T';
printf("Status: %c\n", grade);
```
### dalam Python
```python
status = "Lulus" if nilai >= 60 else "Tidak lulus"
print("Status:", status)
```