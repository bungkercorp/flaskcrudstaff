# flaskcrudstaff
Untuk mencoba image docker ini silakan jalankan:
$ docker build -t bungkerstaff .

dan untuk menjalankan container bisa menggunakan id atau pun name:

$ docker run -d -p 5000:5000 bungkerstaff

Sekarang coba kita check docker kita sudah jalan apa belum dengan perintah : 
$ docker ps -a

Cool! nah kalau jalan coba kembali cek di localhost dengan port 5000 ! localhost:5000…
