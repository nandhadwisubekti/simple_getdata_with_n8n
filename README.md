# simple getdata with n8n
Workflow sederhana untuk get data divisi menggunakan n8n, postgre, dan docker.

Panduan lengkap untuk menjalankan **n8n** (workflow automation) dan **PostgreSQL** menggunakan Docker Compose.

---

## 📦 Komponen

- **n8n** – Otomatisasi workflow open-source
- **PostgreSQL** – Database untuk menyimpan data n8n
- **pgAdmin** – UI untuk mengelola PostgreSQL

---

## 📁 Struktur File
n8n-docker/
├── docker-compose.yml
└── simple_getdata_with_n8n.json
└── README.md

▶️ Langkah 2: Jalankan
Di terminal, arahkan ke folder proyek dan jalankan:

docker-compose up -d

🌐 Akses Layanan
Layanan	URL	Keterangan
n8n	http://localhost:5678	Workflow automation


🔗 Tambahkan koneksi database di pgAdmin:
Host: postgres-db
Port: 5432
Username: postgres
Password: admin123
Database: n8n

## Jalankan WorkFlow 
- Create Workflow
- import from file : simple_getdata_with_n8n.json

