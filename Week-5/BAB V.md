# Array
Array adalah kumpulan data sejenis dengan indeks (mulai 0).
## dalam C

```c
#include <stdio.h>
int main() {
    int arr[5] = {10, 20, 30, 40, 50};  // Deklarasi dan inisialisasi
    for (int i = 0; i < 5; i++) {
        printf("arr[%d] = %d\n", i, arr[i]);
    }
    return 0;
}
```
### input Array

```c
int nilai[3];
for (int i = 0; i < 3; i++) {
    printf("Nilai %d: ", i+1);
    scanf("%d", &nilai[i]);
}
```
## dalam Python

```python
arr = [10, 20, 30, 40, 50]  # List sebagai array
for i in range(5):
    print(f"arr[{i}] = {arr[i]}")

# Input
nilai = []
for i in range(3):
    nilai.append(int(input(f"Nilai {i+1}: ")))
```