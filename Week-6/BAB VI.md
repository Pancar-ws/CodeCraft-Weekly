# Sorting dan Searching
## Binary Search
Algoritma pencarian cepat pada data terurut. Bagi array jadi dua, periksa tengah.
### dalam Python

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
    return -1  # Tidak ditemukan

arr = [10, 20, 30, 40, 50]
print(binary_search(arr, 30))  # Output: 2
```

Link Visualisasi: [Binary Search Visualizer](https://binary-search-visualization.netlify.app/)
## Bubble Sort
Sorting sederhana: Bandingkan pasangan tetangga, tukar jika salah urut.
### dalam Python

```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
    return arr

arr = [64, 34, 25, 12, 22]
print(bubble_sort(arr))  # [12, 22, 25, 34, 64]
```

Link Visualisasi: [Bubble Sort visualize | Algorithms | HackerEarth](https://www.hackerearth.com/practice/algorithms/sorting/bubble-sort/visualize/)
