# localtunnel
Localtunnel  memberi url unik yang dapat diakses publik yang  mem-proxy semua permintaan ke server web yang berjalan secara lokal.


Instal Localtunnel secara global (memerlukan NodeJS) agar dapat diakses di mana saja:

$ npm install -g localtunnel
Mulai server web pada beberapa port lokal (misalnya http://localhost:8000) dan gunakan antarmuka baris perintah untuk meminta terowongan ke server lokal:

$ lt --port 8000
Mendapatkan url, misalnya https://flkajsfljas.loca.lt, yang dapat di bagikan dengan siapa pun selama instance lokal tetap aktif. Setiap permintaan akan dialihkan ke layanan lokal di port yang ditentukan.
