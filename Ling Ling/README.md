# Ling Ling

## Soal

Who made this [meme](https://static.tjctf.org/d25fe79e6276ed73a0f7009294e28c035437d7c7ffe2f46285e9eb5ac94b6bec_meme.png)? [I made this meme](https://www.reddit.com/r/lingling40hrs/comments/gam2if/this_popped_in_my_mind_as_i_was_playing_it_and_i/)! unless.....

## Solusi

1. Mengunduh gambar, kemudian dapat dilihat bahwa gambar tersebut adalah meme dengan not balok `Chopins Third Ballade`. Dari soal dapat diketahui yang dicari adalah pembuat dari meme tersebut. 
2. Untuk mendapatkan data tersebut dapat menggunakan `exiftool` dan grep pada `terminal`. 
```
$ exiftool meme.png | grep Artist
```
3. Setelah itu akan muncul langsung Artist/pembuat dari meme tersebut.

## Flag

```
tjctf{ch0p1n_fl4gs}
```