# Looping (For dan While) dalam C dan Python
## Looping dalam C
### Syntax Dasar `For`
`for (inisialisasi; kondisi; increment) { kode; }`
### Contoh

```c
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        printf("%d ", i);
    }
    return 0;
}
```
Output: `1 2 3 4 5`
### Syntax Dasar `While`
### Contoh

```c
int i = 1;
while (i <= 5) {
    printf("%d ", i);
    i++;
}
```
## Looping dalam Python
### Syntax Dasar `For`
`for variabel in range(awal, akhir):`
### Contoh

```python
for i in range(1, 6):  # 1 sampai 5
    print(i, end=" ")
```
### Syntax Dasar `While`
### Contoh

```python
i = 1
while i <= 5:
    print(i, end=" ")
    i += 1
```