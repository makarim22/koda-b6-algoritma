# Minitask

### membuat algoritma menambahkan keranjang di ecommerce

1. Mulai
2. masukkan nama produk dengan mengetikkan keyword tertentu
3. cari produk berdasarkan keyword yang ditulis
4. tampilkan 10 produk yang memiliki kesamaan dengan keyword
5. tampilkan informasi : ID produk, nama produk, deskripsi, gambar, dan tombol tambah keranjang
6. pilih salah satu produk untuk ditambahkan ke keranjang dengan menekan tombol tambah keranjang
7. validasi stok ke dalam database pada produk yang dipilih
8. apabila stok tersedia, tambahkan produk ke dalam keranjang
9. apabila stok tidak tersedia, tampilkan pesan, "produk tidak tersedia"
10. tanyakan kepada user apakah ingin melanjutkan checkout
11. apabila user menyatakan bersedia, lanjutkan ke tahap selanjutnya
12. lanjutkan ke tahap pembayaran
13. Selesai

```mermaid
flowchart TD
 A@{ shape: circle, label: "Start" } --> B
 B@{ shape: lean-r, label: "Input: product" } --> C
 C@{ shape: rect, label: "Keranjang += product" } --> D

 D@{ shape: diamond, label: "apakah sudah dibayar?"} -->|FALSE| E

 D -- TRUE --> F

 E@{ shape: lean-r, label: "Output: \"pesanan belum dibayar\" "} --> D

 F@{ shape: rect, label: "keranjang = null" } --> G

 G@{ shape: lean-r, label: "Output: \"Keranjang dikosongkan\" "} --> H

  H@{ shape: circle, label: "Stop" } 

```
