# n8n Docker Development

Docker Compose setup untuk menjalankan n8n sebagai local development environment.

Setup ini menggunakan Docker Compose dengan persistent storage dan external Docker network agar n8n dapat berkomunikasi dengan container lain yang berada pada network yang sama.

## Tech Stack

- n8n
- Docker
- Docker Compose
- SQLite

## Requirements

Pastikan sudah terinstall:

- Docker
- Docker Compose

Cek instalasi:

```bash
docker --version
docker compose version