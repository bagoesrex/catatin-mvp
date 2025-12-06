# JasaKu

JasaKu adalah aplikasi manajemen pemasukan untuk pemilik usaha jasa berbasis AI Chat.

Tujuan:

- Mempermudah pencatatan transaksi jasa
- Menghapus kebutuhan form manual
- Memberikan laporan otomatis kepada pemilik jasa

Target User:

- Pemilik jasa individu
  (Servis, desain, dll)

## Fitur JasaKu

- Chat AI untuk mencatat pemasukan
- Riwayat transaksi
- Pencatatan pengeluaran
- Laporan harian, mingguan, bulanan
- Grafik pendapatan
- Dashboard sederhana

## User Flow

1. User membuka website
2. Register sebagai pemilik jasa
3. Login
4. Langsung masuk dashboard
5. Gunakan Chat AI untuk mencatat transaksi
6. Melihat laporan pemasukan

## Frontend Techstack

- NextJS (App Router)
- TypeScript
- Tailwind CSS
- Shadcn UI
- Tanstack Query
- Chart.js / Recharts

## Backend Techstack

- NestJS
- TypeScript
- Prisma ORM
- MySQL

## AI Integration

- OpenAI / Gemini / LLM API
- Kolosal API
- Natural Language Processing (NLP)

## Authentication

- JWT (JSON Web Token)
- Bcrypt password hashing

## AI Feature

User cukup mengetik seperti:

"Catat jasa desain logo 300 ribu hari ini"

AI akan:

- Mengambil nominal
- Membuat title otomatis
- Menyimpan ke database
- Memberikan konfirmasi kembali
