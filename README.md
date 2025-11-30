Anthonius Dale Fernando
TI 24 A1
312410162

---

## 1. Persiapan Awal

### Langkah:

1. Membuka text editor (VSCode).
2. Membuat folder baru dengan nama **lab10_php_oop** di dalam direktori **htdocs**.

### Screenshot:

![Screenshot Persiapan](screenshot/persiapan.png)

---

## 2. Membuat File `mobil.php`

File ini berisi contoh dasar OOP di PHP: pembuatan class, property, method, dan instance object.

### Penjelasan:

* Class `Mobil` memiliki property privat: `warna`, `merk`, `harga`.
* Konstruktor menginisialisasi nilai default.
* Method `gantiWarna()` untuk mengubah warna.
* Method `tampilWarna()` untuk menampilkan warna mobil.
* Membuat dua objek: `$a` dan `$b`.
* Mengubah dan menampilkan warna masing-masing objek.

### Screenshot:

![Screenshot mobil.php](screenshot/mobil.png)

---

## 3. Membuat Class Library `form.php`

Class ini berfungsi menghasilkan form input sederhana secara dinamis.

### Penjelasan:

* Class `Form` memiliki property untuk menyimpan konfigurasi form.
* Method `addField()` menambah field baru.
* Method `displayForm()` menampilkan form.
* File ini bersifat library dan tidak dieksekusi langsung.

### Screenshot:

![Screenshot form.php](screenshot/form.png)

---

## 4. Membuat File `form_input.php`

File ini menggunakan class `Form` dari `form.php`.

### Penjelasan:

* Melakukan `include "form.php"`.
* Membuat instance: `$form = new Form("", "Input Form")`.
* Menambahkan field: Nim, Nama, Alamat.
* Menampilkan form HTML.

### Screenshot:

![Screenshot form\_input.php](screenshot/form_input.png)

---

## 5. Membuat File `database.php`

File ini merupakan class library untuk koneksi database dan operasi CRUD sederhana.

### Fitur:

* Koneksi otomatis melalui konstruktor.
* Method `query()` untuk query bebas.
* Method `get()` untuk mengambil data.
* Method `insert()` untuk menambah data.
* Method `update()` untuk memperbarui data.
* Method `delete()` untuk menghapus data.

### Screenshot:

![Screenshot database.php](screenshot/database.png)

---

## 6. Implementasi Modularisasi

Pada tahap ini, semua komponen dipisah menjadi beberapa file:

* **mobil.php** → Contoh class dasar.
* **form.php** → Library untuk form.
* **database.php** → Library koneksi database.
* **form_input.php** → Implementasi pemanggilan class `Form`.

### Screenshot:

![Screenshot Struktur Folder](screenshot/struktur.png)

---

## 7. Repository GitHub

Semua file, screenshot, dan README.md kemudian di-commit dan push ke repository GitHub dengan nama:

**Lab10Web**

### Screenshot:

![Screenshot GitHub](screenshot/github.png)

---

## 8. Kesimpulan

Pada praktikum ini saya mempelajari:

* Konsep dasar OOP: Class, Property, Method, Object.
* Membuat class sederhana di PHP.
* Membuat class library dan menerapkannya pada file lain.
* Modularisasi kode dengan memisahkan fungsi ke dalam beberapa file.
* Dasar pembuatan class untuk koneksi database.

---

## 9. Daftar File

```
lab10_php_oop/
├── mobil.php
├── form.php
├── form_input.php
├── database.php
├── config.php
└── README.md
```

---


