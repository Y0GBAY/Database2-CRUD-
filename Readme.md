# Catatan Command

Belajar CRUD (Create Update Delete)

Untuk semua data 
```psql
SELECT * FROM user;
SELECT * FROM public.user;
```

Untuk Menambahkan data
```psql
INSERT INTO public.user (nama, saldo) VALUES ('Yoga Bayu', 0);
```

Untuk Update data
```psql
UPDATE public.user SET saldo=10000 WHERE id=1;
```

Untuk Menghapus Data
```psql
DELETE FROM public.user WHERE id=1;
```
