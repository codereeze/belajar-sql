# Belajar Structured Query Language (SQL)

Belajar menggunakan query SQL berbasis Command Line Interface (CLI) menggunakan database MySQL. Agar query tidak error, jangan lupa untuk mengaktifkan database MySQL di control panel aplikasi Laragon atau XAMPP.

## Daftar Isi

- <a href="/001_DDL/README.md">Data Definition Language (DDL)</a>
- <a href="/002_DML/README.md">Data Manipulation Language (DML)</a>
- <a href="/003_DCL/README.md">Data Control Language (DCL)</a>
- <a href="/004_TCL/README.md">Transaction Control Language (TCL)</a>
- <a href="/005_DQL/README.md">Data Query Language (DQL)</a>
- <a href="/006_JOIN/README.md">JOIN</a>
- <a href="/007_TRIGGER/README.md">TRIGGER</a>
- <a href="/008_VIEWS/README.md">VIEWS</a>

## Get Started

Buka terminal atau CMD dan ketikan perintah:

```bash
cd C:\xampp\mysql\bin
```

Jika menggunakan Laragon, bisa gunakan perintah:

```bash
cd C:\laragon\bin\mysql\mysql-8.0.30-winx64
```

`mysql-8.0.30-winx64` adalah direktori versi MySQL saya di Laragon, sesuaikanlah dengan milik kalian.

Klik enter, kemudian masukkan perintah:

```bash
mysql -u root -p
```

Klik enter, setelah itu akan di mintai password, masukkan password jika DB MySQL kalian di password, jika tidak langsung klik enter. Jika tidak ada error maka hasilnya akan seperti dibawah ini.

<img src="/assets/img/mysql_success.png">
