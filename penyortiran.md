# Penyortiran

- [ ] Catatan:

  - Terapkan sort & ketahui kasus terbaik / kasus terburuk, kompleksitas rata-rata masing-masing:
    - tidak ada bubble sort - ini mengerikan - O(n^2), kecuali jika n<=16
  - [ ] Stabilitas dalam algoritme pengurutan ("Apakah Quicksort stabil?")
    - [Stabilitas Algoritma Penyortiran](https://en.wikipedia.org/wiki/Sorting_algorithm#Stability)
    - [Stabilitas Dalam Mengurutkan Algoritma](http://stackoverflow.com/questions/1517793/stability-in-sorting-algorithms)
    - [Stabilitas Dalam Mengurutkan Algoritma](http://www.geeksforgeeks.org/stability-in-sorting-algorithms/)
    - [Algoritma Pengurutan - Stabilitas](http://homepages.math.uic.edu/~leon/cs-mcs401-s08/handouts/stability.pdf)
  - [ ] Algoritme mana yang dapat digunakan pada linked lists? Yang mana pada array? Yang mana pada keduanya?
    - Saya tidak akan merekomendasikan pengurutan linked lists, tetapi penggabungan semacam bisa dilakukan.
    - [Merge Sort Untuk Linked List](http://www.geeksforgeeks.org/merge-sort-for-linked-list/)

- Untuk heapsort, lihat struktur data Heap di atas. Jenis heap bagus, tapi tidak stabil

- [ ] [Sedgewick - Mergesort (5 video)](https://www.coursera.org/learn/algorithms-part1/home/week/3)

  - [ ] [1. Penggabungan](https://www.coursera.org/learn/algorithms-part1/lecture/ARWDq/mergesort)
  - [ ] [2. Mergesort dari bawah ke atas](https://www.coursera.org/learn/algorithms-part1/lecture/PWNEl/bottom-up-mergesort)
  - [ ] [3. Kompleksitas Sortir](https://www.coursera.org/learn/algorithms-part1/lecture/xAltF/sorting-complexity)
  - [ ] [4. Pembanding](https://www.coursera.org/learn/algorithms-part1/lecture/9FYhS/comparators)
  - [ ] [5. Stabilitas](https://www.coursera.org/learn/algorithms-part1/lecture/pvvLZ/stability)

- [ ] [Sedgewick - Quicksort (4 video)](https://www.coursera.org/learn/algorithms-part1/home/week/3)

  - [ ] [1. Quicksort](https://www.coursera.org/learn/algorithms-part1/lecture/vjvnC/quicksort)
  - [ ] [2. Seleksi](https://www.coursera.org/learn/algorithms-part1/lecture/UQxFT/selection)
  - [ ] [3. Kunci Duplikat](https://www.coursera.org/learn/algorithms-part1/lecture/XvjPd/duplicate-keys)
  - [ ] [4. System Sorts](https://www.coursera.org/learn/algorithms-part1/lecture/QBNZ7/system-sorts)

- [ ] UC Berkeley:

  - [ ] [CS 61B Kuliah 29: Penyortiran I (video)](https://archive.org/details/ucberkeley_webcast_EiUvYS2DT6I)
  - [ ] [CS 61B Kuliah 30: Penyortiran II (video)](https://archive.org/details/ucberkeley_webcast_2hTY3t80Qsk)
  - [ ] [CS 61B Kuliah 32: Penyortiran III (video)](https://archive.org/details/ucberkeley_webcast_Y6LOLpxg6Dc)
  - [ ] [CS 61B Kuliah 33: Penyortiran V (video)](https://archive.org/details/ucberkeley_webcast_qNMQ4ly43p4)

- [ ] [Bubble Sort (video)](https://www.youtube.com/watch?v=P00xJgWzz2c&index=1&list=PL89B61F78B552C1AB)
- [ ] [Menganalisis Bubble Sort (video)](https://www.youtube.com/watch?v=ni_zk257Nqo&index=7&list=PL89B61F78B552C1AB)
- [ ] [Sortir Penyisipan, Sortir Gabung (video)](https://www.youtube.com/watch?v=Kg4bqzAqRBM&index=3&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
- [ ] [Sortir Penyisipan (video)](https://www.youtube.com/watch?v=c4BRHC7kTaQ&index=2&list=PL89B61F78B552C1AB)
- [ ] [Merge Sort (video)](https://www.youtube.com/watch?v=GCae1WNvnZM&index=3&list=PL89B61F78B552C1AB)
- [ ] [Quicksort (video)](https://www.youtube.com/watch?v=y_G9BkAm6B8&index=4&list=PL89B61F78B552C1AB)
- [ ] [Sortir Pilihan (video)](https://www.youtube.com/watch?v=6nDMgr0-Yyo&index=8&list=PL89B61F78B552C1AB)

- [ ] Kode Merge sort:
  - [ ] [Menggunakan keluaran array (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/sorting/mergesort.c)
  - [ ] [Menggunakan keluaran array (Python)](https://github.com/jwasham/practice-python/blob/master/merge_sort/merge_sort.py)
  - [ ] [Di tempat (C ++)](https://github.com/jwasham/practice-cpp/blob/master/merge_sort/merge_sort.cc)
- [ ] Kode Quick sort:

  - [ ] [Implementasi (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/randomization/quick.c)
  - [ ] [Implementasi (C)](https://github.com/jwasham/practice-c/blob/master/quick_sort/quick_sort.c)
  - [ ] [Implementasi (Python)](https://github.com/jwasham/practice-python/blob/master/quick_sort/quick_sort.py)

- [ ] Implementasi:

  - [ ] Mergesort: O(n log n) rata-rata dan kasus terburuk
  - [ ] Quicksort: O(n log n) kasus rata-rata
  - Sortir seleksi dan sortir penyisipan keduanya merupakan kasus rata-rata O (n ^ 2) dan terburuk
  - Untuk heapsort, lihat struktur data Heap di atas

- [ ] Tidak wajib, tetapi saya merekomendasikan mereka:
  - [ ] [Sedgewick - Radix Sorts (6 video)](https://www.coursera.org/learn/algorithms-part2/home/week/3)
    - [ ] [1. String di Java](https://www.coursera.org/learn/algorithms-part2/lecture/vGHvb/strings-in-java)
    - [ ] [2. Penghitungan Indeks Kunci](https://www.coursera.org/learn/algorithms-part2/lecture/2pi1Z/key-indexed-counting)
    - [ ] [3. Urutan Radix String Pertama Digit Signifikan Terkecil](https://www.coursera.org/learn/algorithms-part2/lecture/c1U7L/lsd-radix-sort)
    - [ ] [4. Urutan Radix String Pertama Digit Paling Signifikan](https://www.coursera.org/learn/algorithms-part2/lecture/gFxwG/msd-radix-sort)
    - [ ] [5. Radix Quicksort 3 Arah](https://www.coursera.org/learn/algorithms-part2/lecture/crkd5/3-way-radix-quicksort)
    - [ ] [6. Array Suffix](https://www.coursera.org/learn/algorithms-part2/lecture/TH18W/suffix-arrays)
  - [ ] [Sortir Radix](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#radixSort)
  - [ ] [Sortir Radix (video)](https://www.youtube.com/watch?v=xhr26ia4k38)
  - [ ] [Sortir Radix, Sortir Counting (waktu linier diberikan batasan) (video)](https://www.youtube.com/watch?v=Nz1KZXbghj8&index=7&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
  - [ ] [Pengacakan: Penggandaan Matriks, Quicksort, Algoritma Freivalds (video)](https://www.youtube.com/watch?v=cNB2lADK3_s&index=8&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
  - [ ] [Menyortir dalam Waktu Linear (video)](https://www.youtube.com/watch?v=pOKy3RZbSws&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=14)

Sebagai ringkasan, berikut adalah representasi visual dari [15 algoritma pengurutan](https://www.youtube.com/watch?v=kPRA0W1kECg).
Jika Anda membutuhkan detail lebih lanjut tentang subjek ini, lihat bagian "Menyortir" di [Detail Tambahan tentang Beberapa Subjek](detail-tambahan-tentang-beberapa-subjek.md)

---

Selanjutnya - [Graphs](graphs.md)

---
