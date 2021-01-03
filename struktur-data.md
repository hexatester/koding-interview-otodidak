# Struktur Data

## Arrays

- Menerapkan vektor yang mengubah ukuran secara otomatis.
- [ ] Deskripsi:
  - [Array (video)](https://www.coursera.org/lecture/data-structures/arrays-OsBSF)
  - [UC Berkeley CS61B - Array Linear dan Multi-Dim (video)](https://archive.org/details/ucberkeley_webcast_Wp8oiO_CZZE) (Mulailah menonton dari 15m 32s)
  - [Array Dinamis (video)](https://www.coursera.org/lecture/data-structures/dynamic-arrays-EwbnV)
  - [Array Bergerigi (video)](https://www.youtube.com/watch?v=1jtrQqYpt7g)
- [ ] Menerapkan vektor (array yang bisa berubah dengan ukuran otomatis):
  - [ ] Berlatih coding menggunakan array dan pointer, dan matematika pointer untuk melompat ke indeks daripada menggunakan pengindeksan.
  - [ ] Array data mentah baru dengan memori yang dialokasikan
    - dapat mengalokasikan array int di bawah tenda, hanya saja tidak menggunakan fitur-fiturnya
    - start dengan 16, atau jika angka awal lebih besar, gunakan pangkat 2 - 16, 32, 64, 128
  - [ ] size() - jumlah item
  - [ ] capacity() - jumlah barang yang bisa ditampungnya
  - [ ] is_empty()
  - [ ] at(index) - mengembalikan item pada indeks tertentu, meledak jika indeks di luar batas
  - [ ] push(item)
  - [ ] insert(index, item) - menyisipkan item pada indeks, menggeser nilai indeks dan elemen tambahan ke kanan
  - [ ] prepend(item) - dapat menggunakan sisipan di atas pada indeks 0
  - [ ] pop() - hapus dari akhir, nilai kembali
  - [ ] delete(index) - hapus item pada indeks, menggeser semua elemen tertinggal ke kiri
  - [ ] remove(item) - mencari nilai dan menghapus indeks yang menahannya (meskipun di banyak tempat)
  - [ ] find(item) - mencari nilai dan mengembalikan indeks pertama dengan nilai itu, -1 jika tidak ditemukan
  - [ ] resize(new_capacity) // fungsi pribadi
    - saat Anda mencapai kapasitas, ubah ukurannya menjadi dua kali lipat
    - saat memunculkan item, jika ukurannya 1/4 dari kapasitas, ubah ukurannya menjadi setengah
- [ ] Waktu
  - O(1) untuk menambah/menghapus di akhir (diamortisasi untuk alokasi untuk lebih banyak ruang), indeks, atau pembaruan
  - O(n) untuk memasukkan/menghapus di tempat lain
- [ ] Ruang
  - berdekatan dalam memori, jadi kedekatan membantu kinerja
  - ruang yang dibutuhkan = (kapasitas array, yaitu >= n)\*ukuran item, tetapi meskipun 2n, tetap O(n)

## Linked Lists

- [ ] Deskripsi:
  - [ ] [Singly Linked Lists (video)](https://www.coursera.org/lecture/data-structures/singly-linked-lists-kHhgK)
  - [ ] [CS 61B - Linked Lists 1 (video)](https://archive.org/details/ucberkeley_webcast_htzJdKoEmO0)
  - [ ] [CS 61B - Linked Lists 2 (video)](https://archive.org/details/ucberkeley_webcast_-c4I3gFYe3w)
- [ ] [Kode C (video)](https://www.youtube.com/watch?v=QN6FPiD0Gzo) - bukan keseluruhan video, hanya bagian tentang struct Node dan alokasi memori
- [ ] Linked List vs Array:
  - [Daftar Linked List Vs Array (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-linked-lists-vs-arrays-rjBs9)
  - [Di Dunia Nyata Linked List Vs Array (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/in-the-real-world-lists-vs-arrays-QUaUd)
- [ ] [mengapa Anda harus menghindari linked list (video)](https://www.youtube.com/watch?v=YQs6IC-vgmo)
- [ ] Gotcha: Anda perlu pengetahuan pointer ke pointer:
      (untuk saat Anda meneruskan pointer ke fungsi yang dapat mengubah alamat tempat pointer itu menunjuk)
      Halaman ini hanya untuk memahami pointer ke pointer. Saya tidak merekomendasikan gaya traversal daftar ini. Keterbacaan dan pemeliharaan menderita karena kepintaran.
  - [Pointer ke Pointer](https://www.eskimo.com/~scs/cclass/int/sx8.html)
- [ ] Implementasikan (saya lakukan dengan tail pointer & tanpa):
  - [ ] size() - mengembalikan jumlah elemen data dalam daftar
  - [ ] empty() - bool mengembalikan nilai true jika kosong
  - [ ] value_at(index) - mengembalikan nilai item ke-n (mulai dari 0 untuk yang pertama)
  - [ ] push_front(value) - menambahkan item ke depan daftar
  - [ ] pop_front() - hapus item depan dan kembalikan nilainya
  - [ ] push_back(value) - menambahkan item di akhir
  - [ ] pop_back() - menghapus item akhir dan mengembalikan nilainya
  - [ ] front() - dapatkan nilai barang depan
  - [ ] back() - dapatkan nilai item akhir
  - [ ] insert(index, value) - masukkan nilai pada indeks, maka item saat ini pada indeks tersebut ditunjuk oleh item baru pada indeks
  - [ ] erase(index) - menghapus node pada indeks tertentu
  - [ ] value_n_from_end(n) - mengembalikan nilai node pada posisi ke-n dari akhir daftar
  - [ ] reverse() - membalikkan daftar
  - [ ] remove_value(value) - menghapus item pertama dalam daftar dengan nilai ini
- [ ] Doubly-linked List
  - [Deskripsi (video)](https://www.coursera.org/lecture/data-structures/doubly-linked-lists-jpGKD)
  - Tidak perlu diimplementasikan

## Stack

- [ ] [Stack (video)](https://www.coursera.org/lecture/data-structures/stacks-UdKzQ)
- [ ] Tidak akan diterapkan. Implementasi dengan array itu sepele

## Queue

- Queue (Antrean)
- [ ] [Queue (video)](https://www.coursera.org/lecture/data-structures/queues-EShpq)
- [ ] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
- [ ] Implementasikan menggunakan linked-list, dengan tail pointer:
  - enqueue(value) - menambah nilai pada posisi di ekor
  - dequeue() - mengembalikan nilai dan menghapus elemen yang paling baru ditambahkan (depan)
  - empty()
- [ ] Menerapkan menggunakan array berukuran tetap:
  - enqueue(value) - menambahkan item di akhir penyimpanan yang tersedia
  - dequeue() - mengembalikan nilai dan menghapus elemen yang paling baru ditambahkan
  - empty()
  - full()
- [ ] Biaya:
  - implementasi yang buruk menggunakan daftar tertaut di mana Anda mengantre di bagian depan
    dan antrean di bagian ekor akan menjadi O(n) karena Anda memerlukan elemen di sebelah terakhir,
    menyebabkan traversal penuh setiap dequeue
  - enqueue: O(1) (diamortisasi, daftar tertaut dan larik [probing])
  - dequeue: O(1) (daftar dan larik tertaut)
  - empty: O(1) (daftar dan larik tertaut)

## Hash table

- [ ] Video:

  - [ ] [Hashing dengan Chaining (video)](https://www.youtube.com/watch?v=0M_kIqhwbFo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=8)
  - [ ] [Penggandaan Table, Karp-Rabin (video)](https://www.youtube.com/watch?v=BRO7mVIFt08&index=9&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
  - [ ] [Open Addressing, Hashing Kriptografi (video)](https://www.youtube.com/watch?v=rvdJDijO2Ro&index=10&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
  - [ ] [PyCon 2010: The Mighty Dictionary (video)](https://www.youtube.com/watch?v=C4Kc8xzcA68)
  - [ ] [(Lanjutan) Pengacakan: Universal & Hashing Sempurna (video)](https://www.youtube.com/watch?v=z0lJ2k0sl1g&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=11)
  - [ ] [(Lanjutan) Hash sempurna (video)](https://www.youtube.com/watch?v=N0COwN14gt0&list=PL2B4EEwhKD-NbwZ4ezj7gyc_3yNrojKM9&index=4)

- [ ] Kursus Online:

  - [ ] [Tabel Hash Inti (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-hash-tables-m7UuP)
  - [ ] [Struktur Data (video)](https://www.coursera.org/learn/data-structures/home/week/4)
  - [ ] [Masalah Buku Telepon (video)](https://www.coursera.org/lecture/data-structures/phone-book-problem-NYZZP)
  - [ ] tabel hash terdistribusi:
    - [Unggahan Instan dan Pengoptimalan Penyimpanan Di Dropbox (video)](https://www.coursera.org/lecture/data-structures/instant-uploads-and-storage-optimization-in-dropbox-DvaIb)
    - [Tabel Hash Terdistribusi (video)](https://www.coursera.org/lecture/data-structures/distributed-hash-tables-tvH8H)

- [ ] Implementasikan dengan array menggunakan probing linier
  - hash(k, m) - m adalah ukuran tabel hash
  - add(key, value) - jika kunci sudah ada, perbarui nilai
  - exists(key)
  - get(key)
  - remove(key)

---

Selanjutnya - [Lebih Banyak Pengetahuan](lebih-banyak-pengetahuan.md)

---
