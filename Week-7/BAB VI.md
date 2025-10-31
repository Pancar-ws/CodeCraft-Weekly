# Sorting dan Searching
---
## Tujuan Pembelajaran

1. Memahami konsep dasar pencarian dan pengurutan data.
2. Mengimplementasikan algoritma Binary Search dan Bubble Sort.
3. Mengenali kompleksitas waktu dari algoritma dasar.
---
## Dasar Teori

- **Searching:** mencari posisi elemen dalam data.
- **Sorting:** menyusun data dalam urutan tertentu.
- Kompleksitas waktu sering dilambangkan dengan Big O.
---
## Implementasi Binary Search (Python)

```python
def binary_search(arr, target):
    low, high = 0, len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            low = mid + 1
        else:
            high = mid - 1
    return -1

arr = [10, 20, 30, 40, 50]
print(binary_search(arr, 30))  # Output: 2
```
---
## Implementasi Bubble Sort (Python)

```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
    return arr

arr = [64, 34, 25, 12, 22]
print(bubble_sort(arr))
```
---
## Analisis Algoritma

- **Binary Search:** `O(log n)`
- **Bubble Sort:** `O(n²)`
---
## Latihan

1. Implementasikan **Linear Search**.
2. Ubah **Bubble Sort** menjadi urutan menurun (descending).
3. Gunakan **Binary Search** pada data yang tidak urut — amati hasilnya.
---
## Pertanyaan Refleksi

- Mengapa Binary Search membutuhkan data terurut?
- Apa kelemahan utama Bubble Sort?
---
## Referensi

- [Bubble Sort Visualization – HackerEarth](https://www.hackerearth.com/practice/algorithms/sorting/bubble-sort/visualize/)
- [Binary Search Visualizer](https://binary-search-visualization.netlify.app/)