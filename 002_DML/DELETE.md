## DELETE

- #### Delete: One line

```bash
DELETE FROM nama_tabel WHERE kondisi = 'nilai';
```

- #### Delete: All data

```bash
DELETE FROM nama_tabel;
```

- #### Delete: With subquery

```bash
DELETE FROM nama_tabel WHERE id IN (SELECT id FROM tabel_lain WHERE kondisi = 'nilai');
```

- #### Delete: Duplicated data

```bash
DELETE FROM nama_tabel WHERE id NOT IN (SELECT MIN(id) FROM nama_tabel GROUP BY kolom);
```
