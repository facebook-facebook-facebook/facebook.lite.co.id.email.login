Buat atau pindahkan file index.html ke dalam direktori my_web_project. Anda bisa menambahkan konten HTML di dalamnya atau menggunakan contoh sederhana seperti berikut:
html
Copy code



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Web</title>
</head>
<body>
    <h1>Halo dari Web Server!</h1>
    <p>Selamat datang di contoh web sederhana.</p>
</body>
</html>





Langkah 3: Menjalankan Web Server Lokal
Jalankan web server lokal seperti yang telah dijelaskan sebelumnya. Misalnya, menggunakan Python 3:

bash
Copy code

python3 -m http.server 8000  ATAU  python -m http.server 8000

Langkah 4: Menjalankan Ngrok
Buka terminal atau command prompt baru.
Jalankan ngrok untuk meneruskan port web server lokal:
bash
Copy code

ngrok http 8000 JIKA DI LINUX   ./ngrok http 8000


Langkah 5: Mengakses Web Server via Ngrok
Setelah menjalankan ngrok, Anda akan melihat dua URL: satu dengan http dan satu lagi dengan https.

Contoh URL yang diberikan oleh ngrok:

bash
Copy code
Forwarding                    http://abcdef123456.ngrok.io -> http://localhost:8000
Anda bisa mengakses web server lokal Anda melalui URL http://abcdef123456.ngrok.io di browser Anda.

Dengan demikian, Anda telah menjalankan file HTML (misalnya index.html) dari direktori proyek Anda menggunakan web server lokal dan ngrok untuk membuatnya dapat diakses secara publik.