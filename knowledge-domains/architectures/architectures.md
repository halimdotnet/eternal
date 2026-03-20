# Architectures

## Table of Contents
  - [A. Modularity](#a-modularity)

## A. Modularity
Pengelompokan logis dari kode yang saling berkaitan. Bisa berupa sekelompok class dalam bahasa OOP, atau fungsi dalam bahasa fungsional/prosedural.

### 1. Cohesion
Mengukur seberapa erat keterkaitan antar bagian dalam sebuah modul. 

Modul yang cohesive adalah modul di mana semua bagiannya sebaiknya dikemas bersama, memisahkannya hanya akan meningkatkan coupling dan menurunkan keterbacaan.

- **Functional Cohesion** Semua bagian modul saling berkaitan dan modul berisi segalanya yang dibutuhkan untuk berfungsi
- **Sequential Cohesion** Output satu modul menjadi input modul berikutnya
- **Communicational Cohesion** Modul beroperasi pada informasi yang sama atau berkontribusi pada output yang sama
- **Procedural Cohesion** Modul harus dieksekusi dalam urutan tertentu
- **Temporal Cohesion** Modul dikelompokkan karena ketergantungan waktu (misalnya, semua inisialisasi saat startup)
- **Logical Cohesion** Data dalam modul berkaitan secara logis tapi tidak fungsional (contoh: StringUtils)
- **Coincidental Cohesion** Elemen dalam modul tidak berkaitan sama sekali selain berada dalam satu file sumber


### 2. Coupling