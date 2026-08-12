# RetroLens 🖐️✨

Portal filter real-time pakai gerakan tangan, dibikin pake Python + MediaPipe.

Bentangin dua tangan buat buka portal, area di dalamnya kena filter (dual-tone, thermal, sketch, glitch, dll). Ganti filter tinggal pinch jempol-kelingking.

---

## 🇮🇩 Indonesia

**Install** (Python 3.8–3.11):
```bash
# WAJIB menggunakan Python 3.8-3.11 
py -3.11 --version # Windows
python3.11 --version # Linux/macOS
```

```bash
# Direkomendasikan untuk pakai Python VEnv
python3.11 -m venv .venv # Linux/macOS
py -3.11 -m venv .venv # Windows

# Aktivasi venv
source ./.venv/bin/activate     # Linux/macOS
source .\.venv\bin\activate.ps1 # Windows Powershell
source .\.venv\bin\activate.bat # WIndows CMD

# Install Dependensi
pip install -r requirements.txt
```
⚠️ Pengguna Apple Silicon: jangan upgrade mediapipe dari versi yang di-pin (`0.10.9`) — versi baru ada bug di chip ARM Mac.

**Jalankan:**
```bash
python3 Retrolens.py   # Mac/Linux
python Retrolens.py    # Windows
```

**Kontrol:**
- Bentangin 2 tangan → buka portal
- Pinch jempol dengan kelingking → ganti filter
- Kepal 2 tangan / tombol `C` → toggle mode 2D/3D
- `N`/`P` → filter berikutnya/sebelumnya, `S` → screenshot, `Q` → keluar

Dibikin sambil belajar OpenCV + MediaPipe.

---

## 🇬🇧 English

**Install** (Python 3.8–3.11):
```bash
# MUST use Python 3.8-3.11 
py -3.11 --version # Windows
python3.11 --version # Linux/macOS
```

```bash
# Recommended to use Python VEnv
python3.11 -m venv .venv # Linux/macOS
py -3.11 -m venv .venv # Windows

# Activate venv
source ./.venv/bin/activate     # Linux/macOS
source .\.venv\bin\activate.ps1 # Windows Powershell
source .\.venv\bin\activate.bat # WIndows CMD

# Install Dependencies
pip install -r requirements.txt
```
 ⚠️ Apple Silicon users: don't upgrade mediapipe past the pinned version (`0.10.9`) — newer releases are buggy on ARM Macs.

**Run:**
```bash
python3 Retrolens.py   # Mac/Linux
python Retrolens.py    # Windows
```

**Controls:**
- Spread both hands → open portal
- Pinch thumb + pinky → switch filter
- Fist both hands / press `C` → toggle 2D/3D mode
- `N`/`P` → next/previous filter, `S` → screenshot, `Q` → quit

Built while learning OpenCV + MediaPipe.

---

MIT License

- Dibuat original oleh https://github.com/Syahdanfx/Retrolens
- Di-fork oleh https://github/com/Irsyad-gh/Retrolens
