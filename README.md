Anthonius Dale Fernando
TI 24 A1
312410162

---

## 1. Persiapan Awal

### Langkah:

1. Membuka text editor (VSCode).
2. Membuat folder baru dengan nama **lab10_php_oop** di dalam direktori **htdocs**.


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


---

## 3. Membuat Class Library `form.php`

Class ini berfungsi menghasilkan form input sederhana secara dinamis.

### Penjelasan:

* Class `Form` memiliki property untuk menyimpan konfigurasi form.
* Method `addField()` menambah field baru.
* Method `displayForm()` menampilkan form.
* File ini bersifat library dan tidak dieksekusi langsung.

---

## 4. Membuat File `form_input.php`

File ini menggunakan class `Form` dari `form.php`.

### Penjelasan:

* Melakukan `include "form.php"`.
* Membuat instance: `$form = new Form("", "Input Form")`.
* Menambahkan field: Nim, Nama, Alamat.
* Menampilkan form HTML.

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

---

## 6. Implementasi Modularisasi

Pada tahap ini, semua komponen dipisah menjadi beberapa file:

* **mobil.php** → Contoh class dasar.
* **form.php** → Library untuk form.
* **database.php** → Library koneksi database.
* **form_input.php** → Implementasi pemanggilan class `Form`.

---

## 7. Repository GitHub

Semua file, screenshot, dan README.md kemudian di-commit dan push ke repository GitHub dengan nama:

**Lab10Web**


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

## Screenshoot Database

<img width="849" height="895" alt="image" src="https://github.com/user-attachments/assets/bcdee3b4-a181-46a9-af99-4bd15361af2a" />
<img width="823" height="836" alt="image" src="https://github.com/user-attachments/assets/1ec4b406-f3f4-4cae-a371-ffdc9515b736" />
<img width="840" height="507" alt="image" src="https://github.com/user-attachments/assets/36ddf3a7-905c-4408-a9e3-71267380a089" />

## Screenshoot Form Input
<img width="845" height="648" alt="image" src="https://github.com/user-attachments/assets/09db21d1-9f50-4148-8937-a4dbc10c5574" />

## Sceeenshoot Form
<img width="1171" height="858" alt="image" src="https://github.com/user-attachments/assets/cf0f54e4-0069-4365-a876-c3654e34b34e" />
<img width="878" height="259" alt="image" src="https://github.com/user-attachments/assets/db43fc5f-d785-4762-9717-d91c906109d0" />

## Screenshoot Mobil
<img width="1127" height="888" alt="image" src="https://github.com/user-attachments/assets/8a08dc62-bdbe-45ea-bbd6-b64e3794fa7e" />
<img width="635" height="380" alt="image" src="https://github.com/user-attachments/assets/b4f576af-d6bf-4a29-be81-99218c68cde7" />












