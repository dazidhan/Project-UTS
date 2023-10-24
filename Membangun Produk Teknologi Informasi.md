## 1.1 Latar Belakang

Latar belakang pembuatan aplikasi ini berkaitan dengan masalah umum dan hal kecil yang sering dihadapi oleh banyak orang, yaitu pembagian tagihan yang adil dan mudah

## 1.2. Deksripsi Teknologi Informasi

Aplikasi "Split Bill" adalah sebuah alat yang dibuat untuk memudahkan pengguna dalam membagi biaya atau tagihan dengan teman atau keluarga mereka secara adil dan tanpa repot

## 1.3. Branding

Pada tahap ini kita mengeksplorasi branding dari sistem yang dibuat. Branding meliputi:
•	Merk: sharebills
•	Tagline: membagi tagihan, bukan persahabatan
•	Campaign: membuat aplikasi yang membuat penggunanya mudah membagi tagihan mereka, dengan cepat dan adil

Target user:
- Usia 18+
- Seorang yang ingin membagi tagihan dengan adil dan cepat
- Seorang yang tidak ingin ribet
  
User experience theme:
- Mudah
- Sederhana
- Warna: dominan white and black 

Inspirasi desain:


## 2. User Story

bla | bla | bla | bla
---|---|---|---
bla | bla | bla | ⭐⭐⭐⭐⭐

## 3. Struktur Data

Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 

```mermaid
erDiagram
    PENGGUNA {
      String nama_lengkap
      int nomor_telepon
      string email
      string password
    }
    PENGGUNA ||--o{ TAGIHAN : membuat
    TAGIHAN ||--o{ TAGIHAN : membalas 
    TAGIHAN {
      String Pengguna
      int total_tagihan
      datetime waktu_tagihan
      String judul_tagihan 
      String pengguna_lain
      int tagihan_perorang
    }
```

## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)

## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

Bisa load image 
![Contoh](https://fastly.picsum.photos/id/318/536/354.jpg?hmac=Ixy-wle80nudIR_cmnF1iY2y6rMUH7_9sk-BP1fTpM8)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
