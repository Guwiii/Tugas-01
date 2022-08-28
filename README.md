# Tugas-01

Username dan Password dari setiap pengguna agar bisa masuk ke server, dilakukannya pengecekan sampai akun berhasil login.
hal yang saya dapati dari membaca dari beberapa informasi mengenai isu terkait, adalah
Password dan Username dari pengguna ketika dimasukkan ke server maka :
Username kebanyakan yang di stor ke server berbentuk plain text.
sedangkan password, akan di simpan menjadi (encrypted form) ex : 09d2daa10cda4fc72d70cea1eb801595, ketika password akan dicek, server akan menjalankan bentuk enkripsi yang sama dan melakukan pencocokan dengan original encrypted password, jika sama maka berhasil login jika tidak maka gagal.

Hal lain yang saya dapati untuk membedakan username dan password dengan menggunakan colon, diantara username dan password. 
ex : (<username> : <password>)
