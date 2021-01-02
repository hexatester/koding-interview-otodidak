# Graphs

Graf (Graphs) dapat digunakan untuk merepresentasikan banyak masalah dalam ilmu komputer, jadi bagian ini panjang, seperti pohon dan penyortiran.

- Catatan:

  - Ada 4 cara dasar untuk merepresentasikan Graf dalam memori:
    - objek dan pointer
    - matriks kedekatan (adjacency matrix)
    - daftar kedekatan (adjacency list)
    - peta kedekatan (adjacency map)
  - Biasakan diri Anda dengan setiap representasi beserta pro & kontranya
  - BFS dan DFS - mengetahui kompleksitas komputasi mereka, trade off mereka, dan bagaimana menerapkannya dalam kode nyata
  - Saat ditanya pertanyaan, cari solusi berbasis Graf terlebih dahulu, lalu lanjutkan jika tidak ada

- [ ] MIT (video):

  - [ ] [Breadth-First Search](https://www.youtube.com/watch?v=s-CYnVz-uh4&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=13)
  - [ ] [Depth-First Search](https://www.youtube.com/watch?v=AfSk24UTFS8&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=14)

- [ ] Kuliah Skiena - pengantar yang bagus:

  - [ ] [CSE373 2012 - Lecture 11 - Graphs Struktur Data (video)](https://www.youtube.com/watch?v=OiXxhDrFruw&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=11)
  - [ ] [CSE373 2012 - Lecture 12 - Breadth-First Search (video)](https://www.youtube.com/watch?v=g5vF8jscteo&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=12)
  - [ ] [CSE373 2012 - Lecture 13 - Algoritma Graph (video)](https://www.youtube.com/watch?v=S23W6eTcqdY&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=13)
  - [ ] [CSE373 2012 - Lecture 14 - Algoritma Graph (con't) (video)](https://www.youtube.com/watch?v=WitPBKGV0HY&index=14&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
  - [ ] [CSE373 2012 - Lecture 15 - Algoritma Graph (con't 2) (video)](https://www.youtube.com/watch?v=ia1L30l7OIg&index=15&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
  - [ ] [CSE373 2012 - Lecture 16 - Algoritma Graph (con't 3) (video)](https://www.youtube.com/watch?v=jgDOQq6iWy8&index=16&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)

- [ ] Graphs (ulasan dan lainnya):

  - [ ] [6.006 Masalah Jalur Terpendek Sumber Tunggal (video)](https://www.youtube.com/watch?v=Aa2sqUhIn-E&index=15&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
  - [ ] [6.006 Dijkstra (video)](https://www.youtube.com/watch?v=2E7MmKv0Y24&index=16&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
  - [ ] [6.006 Bellman-Ford (video)](https://www.youtube.com/watch?v=ozsuci5pIso&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=17)
  - [ ] [6.006 Mempercepat Dijkstra (video)](https://www.youtube.com/watch?v=CHvQ3q_gJ7E&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=18)
  - [ ] [Aduni: Algoritma Graphs I - Sortasi Topologi, Pohon Rentang Minimum, Algoritma Prim - Kuliah 6 (video)](https://www.youtube.com/watch?v=i_AQT_XfvD8&index=6&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
  - [ ] [Aduni: Algoritma Graphs II - DFS, BFS, Algoritma Kruskal, Struktur Data Union Find - Kuliah 7 (video)](https://www.youtube.com/watch?v=ufj5_bppBsA&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=7)
  - [ ] [Aduni: Algoritma Graphs III: Jalur Terpendek - Kuliah 8 (video)](https://www.youtube.com/watch?v=DiedsPsMKXc&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=8)
  - [ ] [Aduni: Algoritma Graphs IV: Pengantar algoritma geometris - Kuliah 9 (video)](https://www.youtube.com/watch?v=XIAQRlNkJAw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=9)
  - [ ] ~~[CS 61B 2014 (mulai dari 58:09) (video)](https://youtu.be/dgjX4HdMI-Q?list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&t=3489)~~
  - [ ] [CS 61B 2014: Graphs berbobot (video)](https://archive.org/details/ucberkeley_webcast_zFbq8vOZ_0k)
  - [ ] [Algoritma Serakah: Minimum Spanning Tree (video)](https://www.youtube.com/watch?v=tKwnms5iRBU&index=16&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
  - [ ] [Komponen yang Sangat Terhubung Algoritma Graphs Algoritma Kosaraju (video)](https://www.youtube.com/watch?v=RpgcYiky7uw)

- Kursus Coursera Penuh:

  - [ ] [Algoritma pada Graphs (video)](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome)

- Saya akan menerapkan:
  - [ ] DFS dengan daftar kedekatan (rekursif)
  - [ ] DFS dengan daftar adjacency (iteratif dengan stack)
  - [ ] DFS dengan matriks adjacency (rekursif)
  - [ ] DFS dengan matriks adjacency (iteratif dengan stack)
  - [ ] BFS dengan daftar kedekatan
  - [ ] BFS dengan matriks adjacency
  - [ ] jalur terpendek sumber tunggal (Dijkstra)
  - [ ] pohon rentang minimum
  - Algoritme berbasis DFS (lihat video Aduni di atas):
    - [ ] periksa siklus (diperlukan untuk pengurutan topologi, karena kami akan memeriksa siklus sebelum memulai)
    - [ ] sortir topologi
    - [ ] menghitung komponen yang terhubung dalam graf
    - [ ] daftar komponen yang sangat terhubung
    - [ ] periksa graf bipartit

Selanjutnya - [Bahkan Lebih Banyak Pengetahuan](bahkan-lebih-banyak-pengetahuan.md)
