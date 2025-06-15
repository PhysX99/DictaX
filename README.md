# 🔐 DictaX - Wordlist Generator by PhysX

DictaX adalah tool **wordlist generator** buatan **PhysX** Dengan hanya memasukkan nama, kata kunci, dan tanggal penting, DictaX mampu membangkitkan ribuan kemungkinan password realistis dalam sekejap.

---

## ⚙️ Fitur Unggulan
- 🎯 Kombinasi nama, kata kunci, dan tanggal secara otomatis
- 🔠 Variasi huruf besar, kecil, dan kapitalisasi
- 🔢 Angka bertahap otomatis (contoh: 123, 1234, dst.)
- 🔣 Tambahan simbol (!, @, #, $, %, &)
- 🧠 Konversi vokal ke angka (contoh: a → 4, i → 1)
- 📂 Dukungan input dari file leak password (opsional)
- 💾 Output wordlist tersimpan otomatis

---

## 📥 Cara Instalasi

### Di Termux (Android) / Linux
1. **Update & Install Python**
   ```bash
   pkg update && pkg upgrade
   pkg install python git
   git clone https://github.com/username/DictaX.git
   cd DictaX
   python DictaX.py
(Penting!) Buat folder penyimpanan wordlist
> DictaX akan menyimpan hasil wordlist ke folder: /data/data/com.termux/files/home/wordlist/
> 
Jika folder ini belum ada, buat dulu dengan:
>
> mkdir -p /data/data/com.termux/files/home/wordlist/

Jika ingin, kamu bisa menambahkan:
File leak password (misal dari OSINT hasil dump)

⚠️ Disclaimer

Tool ini hanya untuk edukasi dan legal pentesting.
Segala penyalahgunaan DictaX menjadi tanggung jawab pengguna. Gunakan dengan etika dan izin.
