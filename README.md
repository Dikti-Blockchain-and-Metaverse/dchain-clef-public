## Required
- Docker v24.0
- Docker compose compose v3.7
- Geth v1.13.2
- Clef v1.13.2
- expect
- keystore

## How To Start Clef

1. Pastikan server sudah terinstall tools yang dibutuhkan.
2. Clone repository ini pada server.
3. Buat wallet baru dengan menggunakan command `geth --datadir clef account new`. Lalu isikan password wallet minimal 10 karakter.
4. Sesuaikan variabel yang ada pada file init.sh dan start.sh
5. Jalankan script `init.sh`
6. Buat container menggunakan docker compose dengan cara menjalankan command `docker compose up -d`
7. Cek apakah container berhasil dibuat dengan cara menjalankan command `docker ps`
