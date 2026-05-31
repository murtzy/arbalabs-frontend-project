A. Teknologi yang Digunakan
Berdasarkan arahan teknis dan kebutuhan performa, platform ini akan dibangun menggunakan:
-Framework: Next.js (React) untuk arsitektur modular, skalabilitas, dan navigasi yang mulus (SPA)
-Grafis & Visualisasi: Three.js untuk pembuatan Interactive Globe 3D
-Styling: TailwindCSS untuk desain grid yang presisi dan responsif
-Animasi: Framer Motion untuk transisi sinematik antar halaman dan elemen UI
-Data Fetching: Axios atau SWR untuk integrasi langsung dengan API Copernicus


B. Detail Per Halaman & Fitur
Sistem dibagi menjadi dua pandangan utama untuk memenuhi kebutuhan audiens yang berbeda:

1. Public View (Aspirasional & Sinematik)
-Fitur: Mission Countdown System dan Orbital Visualisation (High-Impact)
-Detail Visual: Menampilkan bumi 3D interaktif yang memenuhi layar (full-screen) dengan posisi satelit yang dapat dilacak di atasnya terdapat hitung mundur peluncuran misi September 2026 yang megah
-Storytelling: Memberikan rasa antisipasi bagi masyarakat umum menjelang peluncuran

2. Professional Workspace (Monitoring & Management)
Tab A: Monitoring (Live Operations):
-Fitur: Telemetry Dashboards, AI/Edge Device Status, Event Feed, dan Orbital Tracking yang mendetail
-Detail: Desain data-dense (padat data) menggunakan sistem grid, menampilkan visualisasi orbit yang berdampingan dengan grafik telemetri dinamis untuk korelasi data

Tab B: Management (Action-Oriented):
-Fitur: Payload Upload Areas, Verification/Integrity Panels, dan Admin Interface
-Detail: Fokus pada interaksi transaksional seperti mengunggah data muatan satelit dan memverifikasi integritas AI ArbaEdge

C. Integrasi API Copernicus
Platform akan memanfaatkan Copernicus Data Space Ecosystem untuk mengisi data telemetri nyata:
-Sentinel Hub API: Mengambil data telemetri (misalnya radiasi dan suhu) dan citra satelit permukaan bumi secara real-time
-openEO: Digunakan untuk memproses dataset observasi Bumi menjadi visualisasi wawasan pada dashboard
-Traceability Service: Mengambil konsep verifikasi data Copernicus untuk diimplementasikan pada Verification Panels ArbaLabs guna membuktikan integritas AI