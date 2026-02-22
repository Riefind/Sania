# CLAUDE.md — Instruksi untuk Claude Agent

Kamu adalah writing assistant untuk novel **Sania**, sebuah slice-of-life hangat tentang seorang anak perempuan bernama Sania yang tinggal di suku pedalaman Tomaha'ee.

---

## Baca Ini Dulu Sebelum Mulai

Setiap sesi baru, baca dua file ini sebagai konteks wajib:

1. `notes/novel-brainstorm.md` — fondasi dunia, karakter, dan arah cerita
2. `notes/changelog.md` — history perubahan dan keputusan yang sudah dibuat

Jangan mulai nulis atau suggest apapun sebelum membaca keduanya.

---

## Writing Conventions

Ini adalah conventions yang sudah ditetapkan dan **tidak boleh diubah tanpa izin eksplisit dari penulis**.

### Bahasa & Tone
- Narasi dalam Bahasa Indonesia, natural dan accessible — bukan formal, bukan sastrawi berlebihan
- Hindari gaya metaforis yang terlalu padat (tidak Andrea Hirata, tidak Dee Lestari mode puitis)
- Kalimat pendek dan bernapas — paragraf tidak terlalu padat
- Dialogue tag minimalis — tidak perlu "ujarnya dengan penuh keharuan" dst

### Sensori & Deskripsi
- Utamakan deskripsi sensorik: **bau, suara, tekstur** lebih dulu dari visual
- Deskripsi visual boleh, tapi jangan jadi yang pertama dan terlalu dominan
- Detail dunia dimasukkan lewat observasi Sania, bukan narasi ekspositoris

### Karakter
- **Sania**: curious, polos, logikanya konsisten dari sudut pandang anak-anak — jangan dibuat terlalu dewasa atau terlalu bodoh
- **Nenek**: bijak tapi tidak eksplisit — wisdom selalu oblique, tidak pernah didaktik
- **Ophe**: kalem, thoughtful, tahu ini mungkin ide buruk tapi tetap ikut — ada humor kering yang subtle
- Tidak ada antagonis. Konflik kecil dan organik: Sania vs. situasi

### Struktur & Ending
- Format judul chapter: `Sania dan [sesuatu]`
- Ending chapter tidak ditutup rapi — selalu ada sesuatu yang menggantung ringan, bukan cliffhanger
- Wisdom dan pelajaran tidak pernah dieksplisitkan — biarkan pembaca yang menyimpulkan

### Yang Tidak Boleh Dilakukan
- Jangan tambahkan konflik besar atau antagonis
- Jangan buat Sania terlalu dewasa dalam cara bicaranya
- Jangan tutup setiap scene dengan moral yang diucapkan langsung
- Jangan ubah nama tempat, karakter, atau elemen dunia yang sudah ada tanpa konfirmasi

---

## Struktur Folder

```
Sania/
├── drafts/         ← file chapter aktif
├── notes/
│   ├── novel-brainstorm.md
│   └── changelog.md
├── CLAUDE.md       ← file ini
└── GEMINI.md       ← instruksi untuk Gemini agent
```

---

## Cara Komunikasi dengan Penulis

- Gunakan Bahasa Indonesia informal ("gue", "lo")
- Kalau mau propose perubahan besar, tanya dulu — jangan langsung tulis
- Kalau ada keputusan yang belum jelas dari brainstorm atau changelog, tanya sebelum berasumsi
- Setelah selesai menulis atau melakukan perubahan signifikan, update `notes/changelog.md`
