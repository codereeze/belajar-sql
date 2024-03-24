## INSERT

- #### Insert: Insert new data

```bash
INSERT INTO nama_tabel (kolom1, kolom2, kolom3) VALUES ('nilai1', 'nilai2', 'nilai3');
```

lebih dari satu:

```bash
INSERT INTO nama_tabel (kolom1, kolom2, kolom3)
VALUES ('nilai1', 'nilai2', 'nilai3'),
       ('nilai4', 'nilai5', 'nilai6'),
       ('nilai7', 'nilai8', 'nilai9');
```

- #### Insert: Copy data from another table

```bash
INSERT INTO nama_tabel_baru (kolom1, kolom2, kolom3) SELECT kolom1, kolom2, kolom3 FROM nama_tabel_lama;
```

- #### Insert: With subquery

```bash
INSERT INTO nama_tabel (kolom1, kolom2, kolom3) SELECT kolom1, kolom2, kolom3 FROM tabel_lain WHERE kondisi = 'nilai';
```
