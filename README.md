# Data Siswa Baru SMP ABBS 2026/2027

**Viewer publik** data PPS 2026/2027 — menampilkan daftar siswa baru per program.

🌐 **URL:** https://siswabarusmpabbs.vercel.app

## Cara Kerja

- Halaman ini **fetch data.json** langsung dari repo utama [`smpabbs/pps-pembagian-kelas`](https://github.com/smpabbs/pps-pembagian-kelas) via **raw.githubusercontent.com**
- Setiap refresh menampilkan **data terbaru** — tidak perlu deploy ulang
- **Read-only** — view publik, edit dilakukan di [pps2627.vercel.app](https://pps2627.vercel.app)

## Fitur

- ✅ Tabel per program (ICT-L/P, TCP-L/P, VCP-L/P)
- ✅ Search by nama / asal sekolah
- ✅ Filter per program
- ✅ Auto sync dengan data terbaru dari repo utama

## Teknologi

- HTML + CSS + JavaScript (vanilla)
- GitHub Raw API untuk data
- Vercel untuk hosting
