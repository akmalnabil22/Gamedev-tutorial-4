Untuk pembuatan level 2, prosesnya kurang lebih sama dengan pembuatan level 1  
1. Membuat scene `Level2`
2. Menambah tilemap dan melukis level
3. Menambah `Player` yang sudah dibuat sebelumnya
4. Menggunakan scene `AreaTrigger` untuk menambah kondisi menang dan kalah  
5. Membuat spawner yang menajatuhkan objek `Saw` sama seperti objek `Fish` pada level sebelumnya  


Beberapa modifikasi yang ditambahkan  
1. Setelah memenangkan level 1, player akan langsung berpindah ke level 2
2. Jika player jatuh maka akan dianggap kalah dan memunculkan `LoseScreen`
2. `LoseScreen` dan `WinScreen` bisa diklik untuk kembali ke level 1.