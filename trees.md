# Trees

## Trees - Catatan & Latar Belakang

- [ ] [Seri: Trees (video)](https://www.coursera.org/lecture/data-structures/trees-95qda)
- konstruksi pohon dasar
- traversal
- algoritma manipulasi
- [ ] [BFS(breadth-first search) dan DFS(depth-first search) (video)](https://www.youtube.com/watch?v=uWL6FJhq5fM)
  - Catatan BFS:
    - level order (BFS, menggunakan queue)
    - kompleksitas waktu: O(n)
    - kompleksitas ruang:
      terbaik: O(1)
      terburuk: O(n/2)=O(n)
  - Catatan DFS:
    - kompleksitas waktu: O(n)
    - kompleksitas ruang:
      terbaik: O(log n) - rata-rata. ketinggian tree
      terburuk: O(n)
    - dalam urutan (DFS: kiri, sendiri/self, kanan)
    - pasca urutan (DFS: kiri, kanan, sendiri/self)
    - pra urutan (DFS: sendiri/self, kiri, kanan)

## Binary search trees: BSTs

- [ ] [Ulasan Binary Search Tree (video)](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
- [ ] [Serial (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/p82sw/core-introduction-to-binary-search-trees)
  - starts with symbol table and goes through BST applications
- [ ] [Pendahuluan (video)](https://www.coursera.org/learn/data-structures/lecture/E7cXP/introduction)
- [ ] [MIT (video)](https://www.youtube.com/watch?v=9Jry5-82I68)
- C/C++:
  - [ ] [Binary search tree - Implementasi di C/C++ (video)](https://www.youtube.com/watch?v=COZK7NATh4k&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=28)
  - [ ] [Implementasi BST - alokasi memori di stack dan heap (video)](https://www.youtube.com/watch?v=hWokyBoo0aI&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=29)
  - [ ] [Temukan min dan max elemen dalam binary search tree (video)](https://www.youtube.com/watch?v=Ut90klNN264&index=30&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
  - [ ] [Temukan ketinggian pohon biner (video)](https://www.youtube.com/watch?v=_pnqMz5nrRs&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=31)
  - [ ] [Binary tree traversal - strategi luas-pertama dan mendalam-pertama (video)](https://www.youtube.com/watch?v=9RHO6jU--GU&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=32)
  - [ ] [Pohon biner: Level Order Traversal (video)](https://www.youtube.com/watch?v=86g8jAQug04&index=33&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
  - [ ] [Binary tree traversal: Preorder, Inorder, Postorder (video)](https://www.youtube.com/watch?v=gm8DUJJhmY4&index=34&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
  - [ ] [Periksa apakah pohon biner adalah binary search tree atau bukan (video)](https://www.youtube.com/watch?v=yEwSGhSsT0U&index=35&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
  - [ ] [Hapus node dari Binary Search Tree (video)](https://www.youtube.com/watch?v=gcULXE7ViZw&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=36)
  - [ ] [Penerus Berurutan di binary search tree (video)](https://www.youtube.com/watch?v=5cPbNCrdotA&index=37&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
- [ ] Implementasikan:
  - [ ] insert // masukkan nilai ke dalam pohon
  - [ ] get_node_count // dapatkan hitungan nilai yang disimpan
  - [ ] print_values // mencetak nilai di pohon, dari min hingga maks
  - [ ] delete_tree
  - [ ] is_in_tree // mengembalikan nilai true jika nilai yang diberikan ada di pohon
  - [ ] get_height // mengembalikan tinggi dalam node (tinggi node tunggal adalah 1)
  - [ ] get_min // mengembalikan nilai minimum yang disimpan di pohon
  - [ ] get_max // mengembalikan nilai maksimum yang disimpan di pohon
  - [ ] is_binary_search_tree
  - [ ] delete_value
  - [ ] get_successor // mengembalikan nilai tertinggi berikutnya di pohon setelah nilai yang diberikan, -1 jika none

## Heap / Prioritas Antrian / Biner Heap

- Heap (tumpukan)
- Priority Queue (Prioritas Antrian)
- Binary Heap (Biner Heap)
- divisualisasikan sebagai pohon, tetapi biasanya linier dalam penyimpanan (array, linked list)
- [ ] [Heap](<https://en.wikipedia.org/wiki/Heap_(data_structure)>)
- [ ] [Pendahuluan (video)](https://www.coursera.org/learn/data-structures/lecture/2OpTs/introduction)
- [ ] [Penerapan Naif (video)](https://www.coursera.org/learn/data-structures/lecture/z3l9N/naive-implementations)
- [ ] [Pohon Biner (video)](https://www.coursera.org/learn/data-structures/lecture/GRV2q/binary-trees)
- [ ] [Keterangan Tinggi Pohon (video)](https://www.coursera.org/learn/data-structures/supplement/S5xxz/tree-height-remark)
- [ ] [Operasi Dasar (video)](https://www.coursera.org/learn/data-structures/lecture/0g1dl/basic-operations)
- [ ] [Pohon Biner Lengkap (video)](https://www.coursera.org/learn/data-structures/lecture/gl5Ni/complete-binary-trees)
- [ ] [Pseudocode (video)](https://www.coursera.org/learn/data-structures/lecture/HxQo9/pseudocode)
- [ ] [Urutan Heap - lompat untuk memulai (video)](https://youtu.be/odNJmw5TOEE?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3291)
- [ ] [Urutan Heap (video)](https://www.coursera.org/learn/data-structures/lecture/hSzMO/heap-sort)
- [ ] [Membangun heap (video)](https://www.coursera.org/learn/data-structures/lecture/dwrOS/building-a-heap)
- [ ] [MIT: Heaps dan Heap Sort (video)](https://www.youtube.com/watch?v=B7hVxCmfPtM&index=4&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
- [ ] [CS 61B Kuliah 24: Antrian Prioritas (video)](https://archive.org/details/ucberkeley_webcast_yIUFT6AKBGE)
- [ ] [Linear Time BuildHeap (max-heap)](https://www.youtube.com/watch?v=MiyLo8adrWw)
- [ ] Menerapkan sebuah max-heap:
  - [ ] insert
  - [ ] sift_up - dibutuhkan untuk memasukkan
  - [ ] get_max - mengembalikan item maksimal, tanpa menghapusnya
  - [ ] get_size() - mengembalikan jumlah elemen yang disimpan
  - [ ] is_empty() - mengembalikan nilai true jika heap tidak berisi elemen
  - [ ] extract_max - mengembalikan item maksimal, menghapusnya
  - [ ] sift_down - dibutuhkan untuk extract_max
  - [ ] remove(i) - menghapus item pada indeks i
  - [ ] heapify - membuat heap dari larik elemen, dibutuhkan untuk heap_sort
  - [ ] heap_sort() - mengambil array yang tidak disortir dan mengubahnya menjadi array yang diurutkan di tempat menggunakan heap maks atau heap min

---

Selanjutnya - [Penyortiran](penyortiran.md)

---
