# Mengenal Nano,Vim dan Neovim

Dalam lingkungan terminal, terdapat tiga editor teks yang sering digunakan, yaitu Nano, Vim, dan Neovim. Masing-masing editor ini memiliki keunikan dalam pendekatan mereka terhadap pengeditan teks.

Nano dianggap sebagai pilihan yang paling ramah bagi pengguna baru. Dengan antarmuka yang sederhana dan panduan perintah yang jelas di bagian bawah layar, Nano menyajikan pengalaman pengeditan teks yang familiar dan mudah dipahami.

Vim, di sisi lain, sering dianggap sebagai editor teks yang lebih kuat namun memiliki kurva pembelajaran yang lebih tinggi. Dengan beragam fitur canggih dan fleksibilitas yang tinggi, Vim menawarkan pengalaman pengeditan teks yang cepat dan efisien bagi pengguna yang sudah terbiasa dengan perintahnya.

Terakhir, Neovim adalah varian dari Vim yang bertujuan untuk meningkatkan fungsionalitas dan kestabilan. Dengan fokus pada inovasi dan performa, Neovim menarik bagi pengguna yang menginginkan pengalaman pengeditan teks yang modern dan efisien.

Pertama kita akan membuat file dan kemudian kita akan mencoba melakukan program python sederhana dengan melakukan nano,vim dan nvim.

mulai dari membuka terminal linux , lalu ketik :

    nvim mahasiswa.txt

disini kita akan menggunakan neovim atau nvim.

ini akan membuka file jika ada dan jika tidak maka akan membuat file baru secara otomatis

![mahasiswa txt](https://github.com/FahriAl-Hafiz/Code-editor-Terminal/assets/126375451/3ca445b7-b443-4aed-a09b-b99edba83726)

didalam nya akan sedikit membingungkan pada awalnya , karena nvim dan vim menggunakan 'mode'.

jika untuk mengetik kita harus menekan huruf 'i' untuk masuk ke mode insert , lalu ada 'v' untuk visual dan di mode biasa tekan ':w' untuk save dan ':wq' untuk write and quit atau save dan keluar.

kemudian kita akan menggunakan nano untuk membuat program python berupa kalkulator , ketik diterminal :

    sudo nano kalkulator_nano.py

sama seperti nvim , jika file nya sudah ada maka nano akan membuka filenya ,jika tidak ada maka otomatis terbuat file baru.

tidak seperti nvim dan vim , nano tergolong sangat simpel .

didalam nano masukan kode program kalkulator.

![kalkulator_nano](https://github.com/FahriAl-Hafiz/Code-editor-Terminal/assets/126375451/dc0788e3-e27b-4288-93d3-233738f05c8a)

jika sudah , tekan ctrl + x untuk keluar dan pilih Yes untuk mensave file.

lalu untuk vim kita akan membuat ulang program kalkulator . masukan perintah di terminal :

    vi kalkulator_vim.py

buat kode di dalam vim , dengan pengaturan yang sama degan neovim.

jika sudah tekan ':wq' untuk save dan quit.

untuk menjalankan file python yang baru saja dibuat kita akan menggunakan perintah 'python'.

pastikan kita berada di directory file .py terseebut lalu ketik :

    python kalkulator_vim.py
    
![python_vim](https://github.com/FahriAl-Hafiz/Code-editor-Terminal/assets/126375451/f51d87ec-9b09-447c-88f2-80aaf07968a8)

Dengan begitu, kami harap artikel ini memberikan gambaran yang jelas tentang tiga editor teks yang sering digunakan di terminal: Nano, Vim, dan Neovim. Tak peduli pilihan Anda, setiap editor memiliki keunikan dan kelebihannya sendiri. Seiring dengan eksplorasi Anda dalam dunia pengeditan teks, kami juga mengundang Anda untuk terus mempelajari fitur-fitur baru dan menemukan yang terbaik sesuai dengan kebutuhan Anda. Terima kasih telah membaca



