# 📘 INF209 Basis Data — Week 05

## Building the SmartEdu Schema

Interactive Learning Module  
**INF209 — Basis Data**  
Program Studi Informatika  
Universitas Pembangunan Jaya

---

## 🚀 Start Interactive Learning

👉 **[OPEN WEEK 05 — BUILDING THE SMARTEDU SCHEMA](https://rinynoor.github.io/Interactive-Learning-Week-05/inf209-week05-building-smartedu-schema.html)**

Klik tombol di atas untuk membuka **Interactive Learning Week 05**
langsung sebagai halaman web.

---

## 📖 About This Module

Week 05 membahas implementasi relational schema **SmartEdu**
menjadi struktur database menggunakan **Oracle SQL DDL**.

Learning journey:

**ERD → Relational Schema → DDL → Constraints → Verification → Debugging → ALTER TABLE**

---

## 🎯 Learning Outcomes

Setelah menyelesaikan module ini, mahasiswa mampu:

- Menerjemahkan ERD menjadi relational tables.
- Menentukan table creation order berdasarkan dependency.
- Menggunakan Oracle SQL DDL.
- Membuat tabel menggunakan `CREATE TABLE`.
- Menentukan Primary Key dan Foreign Key.
- Menggunakan `NOT NULL`, `UNIQUE`, dan `CHECK`.
- Memverifikasi table structure dan constraints.
- Melakukan debugging terhadap DDL.
- Memodifikasi struktur database menggunakan `ALTER TABLE`.

---

## 🗄️ SmartEdu Schema

SmartEdu terdiri dari:

- `STUDENT`
- `LECTURER`
- `COURSE`
- `SEMESTER`
- `CLASS`
- `ENROLLMENT`

### Recommended Creation Order

`STUDENT / LECTURER / COURSE / SEMESTER → CLASS → ENROLLMENT`

---

## 🟠 Database Platform

Praktikum menggunakan **Oracle SQL**.

Sebelum membuat database objects, mahasiswa harus:

**CHECK → UNDERSTAND → CREATE/ALTER → VERIFY**

Jangan langsung menggunakan `DROP TABLE` atau `TRUNCATE TABLE`
ketika menemukan object yang sudah ada.

---

## 🧪 Week 05 Laboratory

### Building the SmartEdu Schema

Mahasiswa akan:

1. Menentukan table creation order.
2. Membuat enam SmartEdu tables.
3. Mendefinisikan PK, FK, dan constraints.
4. Menjalankan DDL pada Oracle.
5. Memverifikasi struktur database.
6. Menganalisis dan memperbaiki DDL error.
7. Melakukan satu perubahan menggunakan `ALTER TABLE`.

---

## 📤 Submission

### SQL Script

`smartedu_ddl_NIM.sql`

### Laboratory Report

`Week05_NIM_Nama.pdf`

Report berisi:

- Table creation order
- Evidence eksekusi
- Structure verification
- Constraint verification
- Error, cause, dan correction
- `ALTER TABLE`
- Short reflection

---

## 📊 Assessment

| Component | Weight |
|---|---:|
| Table structure & data types | 20% |
| Primary Key & Foreign Key | 25% |
| Constraints | 20% |
| Runnable SQL script | 20% |
| Evidence & report | 15% |

---

## 🔜 Next Week

**Week 06 — Connecting Data with SQL JOIN**

`Tables → PK/FK → Relationships → SQL JOIN → Information`

---

**INF209 — Basis Data**  
Program Studi Informatika  
Universitas Pembangunan Jaya
