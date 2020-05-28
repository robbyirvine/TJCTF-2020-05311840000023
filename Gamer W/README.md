# Gamer W

## Soal

Can you figure out how to [cheat](https://gamer_w.tjctf.org/) the system? Grab his hat to prove your victory!

## Solusi

1. Untuk menyelesaikan soal ini, diperlukan chrome extension **Cetus**. Cetus dimanfaatkan untuk memanipulasi game tersebut. 
2. Masuk ke dalam shop. Ubah value dari gold itu sendiri. Search menggunakan Cetus dengan comparison operator **EQ** dan value type **f32**. 
3. Akan didapatkan kode untuk gold adalah `0x02111f3c`. 
4. Kemudian bookmark dan ubah value goldnya menjadi banyak untuk membeli semua yang ada di shop. 
5. Level 1 akan melawan 1 monster hijau. Bisa diselesaikan tanpa menggunakan cheat apapun.
6. Level 2 akan melawan 3 monster hijau. Bisa diselesaikan tanpa menggunakan cheat apapun.
7. Level 3 akan muncul Boss monster. Bisa diselesaikan tanpa menggunakan cheat apapun.
8. Level 4 akan muncul Boss yang memiliki senjata yang dapat menembak banyak peluru hijau sekaligus Diselesaikan dengan menggunakan cheat.
9. Gunakan Cetus untuk mengubah total hp dari player. Kode untuk hp pemain adalah: `0x2112f1c`. Bookmark dan ubah valuenya menjadi banyak supaya tidak bisa mati saat terkena tembakan.
10. Level 5 akan muncul Boss yang memiliki `Life Potion` yang membuat lifenya regenerasi jika terkena serangan. Gunakan Cheat untuk mengubah hp dari bossnya. Kode untuk hp boss tersebut adalah: `0x2112e4c`.
11. Bookmark, freeze, dan ubah valuenya menjadi 0. 

## Flag

```
tjctf{c3tus_del3tus_ur_m3ms_g0ne}
```