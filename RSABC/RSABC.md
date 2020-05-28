# RSABC

## Soal

I was just listening to some relaxing ASMR when a notification popped up with `this`.

## Solusi

1. Setelah mengetahui hint yang terdapat di Challenge, bisa mencari referensi pengerjaan di `TJCTF-2019 Easy as RSA`
2. Melakukan faktorisasi (mendapatkan p dan q) pada alamat `factordb.com`
```
p = 202049603951664548551555274464815496697
q =  285934543893985722871321330457714807993
```
3. Selanjutnya adalah menginputkan n, e, c serta p dan q kedalam Ruby Script:
```
$ruby main.rb
```

## Flag:

```
tjctf{BOLm1QMWi3c}
```