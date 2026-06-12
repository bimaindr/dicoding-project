📘 Learning Buddy – E-Learning Adaptive
Learning Buddy adalah aplikasi e-learning adaptif berbasis chatbot yang membantu pengguna menentukan jalur belajar yang sesuai dengan kemampuan mereka melalui interaksi percakapan, tes diagnostik, dan rekomendasi kelas yang dipersonalisasi.
Mengakses chatbot Learning Buddy<img width="1349" height="680" alt="chat awal" src="https://github.com/user-attachments/assets/1f2a8108-d169-4e17-9e91-dc5c56ca2743" />


🎯 Tujuan Proyek
Membantu siswa Dicoding menghindari kebingungan dalam memilih kelas dengan menyediakan roadmap belajar yang personal, bukan pendekatan one size fits all.

🚀 Fitur Utama (MVP)
🤖 Chatbot interaktif sebagai learning companion

🧠 Tes diagnostik untuk menentukan level pengguna

🎯 Rekomendasi kelas berdasarkan hasil evaluasi

📊 Pelaporan progress belajar melalui chatbot

🔐 Autentikasi pengguna menggunakan Supabase

🧑‍💻 Teknologi yang Digunakan
Frontend: HTML, CSS, JavaScript (Single Page Application)

Backend: Python, Flask (REST API)

Database & Auth: Supabase (PostgreSQL)

🔁 Alur Penggunaan
Pengguna login

Mengikuti tes diagnostik melalui chatbot

Mendapatkan level kemampuan dan rekomendasi kelas

Menanyakan progress belajar langsung melalui chatbot

⚙️ Menjalankan Project Secara Lokal
1️⃣ Menjalankan Backend (Python – Flask)
Prerequisite:

Python ≥ 3.9

pip

Langkah:

bash:
Copy code
cd backend
python -m venv venv



Aktifkan virtual environment:
bash:
venv\Scripts\activate


Install dependency Python:
pip install -r requirements.txt

Jalankan backend:
python app.py
Backend akan berjalan di:
http://127.0.0.1:5000


2️⃣ Menjalankan Frontend (SPA)
Prerequisite:
-Node.js ≥ 18
-npm

Langkah:

bash:
npm install
Jalankan frontend:

bash
npm run dev
Atau jika menggunakan Live Server / static server:


3️⃣ Koneksi Frontend ke Backend
Pastikan frontend terhubung ke endpoint chatbot berikut:

arduino
Copy code
http://127.0.0.1:5000/chat
📌 Status Proyek
✅ >75% dari rencana proyek telah selesai
Fokus utama telah tercapai pada MVP dan demo fungsional chatbot adaptif.



