# Broken Button

## Soal
This site is telling me all I need to do is click button to find the flag! Is it really that easy?
site: `https://broken_button.tjctf.org/`

## Solusi

1. Klik F12 atau ke inspect element. 
2. Pada <body> tag terdapat button yang mengarah ke `find_the_flag!.html`.
3. Salin link tersebut dan tambahkan ke URL diatas sehingga hasilnya adalah `https://broken_button.tjctf.org/find_the_flag!.html` dan flag akan ditampilkan.

## Flag

```
tjctf{wHa1_A_Gr8_1nsp3ct0r!}
```