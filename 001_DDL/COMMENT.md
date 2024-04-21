## COMMENT

- #### Comment: Table

```bash
ALTER TABLE nama_tabel COMMENT = 'Ini adalah table untuk menyimpan data user';
```

- #### Comment: Column

```bash
ALTER TABLE nama_tabel MODIFY COLUMN nama_kolom tipe_data_kolom COMMENT 'Kolom ini menyimpan kode transaksi pembayaran';
```

- #### Comment: Schema

```bash
SELECT SCHEMA_NAME, SCHEMA_COMMENT FROM information_schema.SCHEMATA WHERE SCHEMA_NAME = 'nama_skema';
```
Selanjutnya:
```bash
UPDATE information_schema.SCHEMATA SET SCHEMA_COMMENT = 'Skema ini digunakan untuk mengelola data transaksi' WHERE SCHEMA_NAME = 'nama_skema';
```

