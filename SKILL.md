# SKILL.md — Custom Skills untuk Claude Agent

---

## /nulis

**Trigger:** `/nulis`

**Deskripsi:** Lanjutkan menulis novel Sania dari titik terakhir.

**Behavior:**

1. **Baca konteks wajib terlebih dahulu:**
   - `notes/novel-brainstorm.md` — fondasi dunia dan karakter
   - `notes/changelog.md` — history keputusan dan titik terakhir pengerjaan

2. **Tanya penulis sebelum mulai:**
   - Chapter berapa yang mau dilanjutkan atau dikerjakan?
   - Ada arah, scene, atau elemen spesifik yang mau dimasukkan?
   - Ada constraint khusus untuk sesi ini?

3. **Tulis berdasarkan jawaban penulis**, dengan ketat mengikuti writing conventions di `CLAUDE.md`:
   - Tone hangat, bahasa natural
   - Sensorik dulu (bau, suara, tekstur)
   - Karakter konsisten dengan yang sudah ditetapkan
   - Tidak ada moral eksplisit, tidak ada antagonis

4. **Update `notes/changelog.md` setiap kali ada perubahan**, bukan hanya di akhir sesi:
   - Setiap kali nulis atau revisi bagian chapter → langsung catat di changelog
   - Setiap kali ada keputusan baru (karakter, elemen dunia, struktur) → langsung catat
   - Setiap kali menimpa draft → catat apa yang berubah dan kenapa
   - Format: tambahkan di bawah tanggal hari ini (buat entry tanggal baru kalau belum ada)

5. **Simpan ke file draft:**
   - Tulis langsung ke file draft yang sesuai di `drafts/`
   - Konfirmasi ke penulis sebelum menimpa jika ada perubahan struktural besar

**Yang tidak boleh dilakukan tanpa izin eksplisit:**
- Mengubah nama karakter, tempat, atau elemen dunia yang sudah ada
- Mengubah tone atau gaya bahasa
- Menambah plot besar atau konflik yang tidak organik
- Menimpa draft tanpa konfirmasi jika ada perubahan struktural besar
