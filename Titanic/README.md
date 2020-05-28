# Titanic

## Soal

I wrapped tjctf{} around the lowercase version of a word said in the 1997 film "Titanic" and created an MD5 hash of it: `e246dbab7ae3a6ed41749e20518fcecd`.

## Solusi

1. Yang kita ketahui adalah hash MD5 tersebut berasal dari script film "Titanic". Setiap katanya dibuat lowercase dan di tambahi dengan tjctf{}. 
2. Copy script film Titanic terlebih dahulu di [sini](http://sites.inka.de/humpty/titanic/script.html). 
3. Dengan bantuan visual studio code, ubah semua menjadi lowercase, hapus `.` `,` `:` `/` , ubah spasi menjadi `enter` dan tambahkan `"tjctf{}"` di setiap barisnya.
4. Gunakan hashcat pada terminal dengan command sebagai berikut :
```
hashcat -m 0 -a 0 e246dbab7ae3a6ed41749e20518fcecd titanic.txt --force --show
```
5. `Titanic.txt` adalah script dari film "Titanic" yang sudah diubah. Tekan enter dan hasil akan langsung muncul.

## Flag

```
tjctf{ismay's}
```