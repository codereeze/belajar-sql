## ALTER QUERY

- #### Alter Table: Menambah kolom baru

```bash
ALTER TABLE nama_tabel ADD nama_kolom tipe_data;
```

lebih dari satu:

```bash
ALTER TABLE nama_tabel ADD nama_kolom1 TipeData1, ADD nama_kolom2 TipeData2;
```

- #### Alter Table: Mengubah tipe data kolom

```bash
ALTER TABLE nama_tabel MODIFY nama_kolom tipe_data_baru;
```

- #### Alter Table: Menghapus kolom

```bash
ALTER TABLE nama_tabel DROP COLUMN nama_kolom;
```

- #### Alter Table: Menambah constraint
  Dapat digunakan untuk (PRIMARY/FOREIGN/UNIQUE) KEY.

```bash
ALTER TABLE nama_tabel ADD CONSTRAINT nama_constraint PRIMARY KEY (nama_kolom);
```

- #### Alter Table: Menghapus constraint

```bash
ALTER TABLE nama_tabel DROP CONSTRAINT nama_constraint;
```

- #### Alter Table: Menambah index

```bash
ALTER TABLE nama_tabel ADD INDEX nama_index (nama_kolom);
```

- #### Alter Table: Menghapus index

```bash
ALTER TABLE nama_tabel DROP INDEX nama_index;
```
