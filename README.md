# 📝 OCR PDF to Text – Romanian Language 🇷🇴

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Tesseract](https://img.shields.io/badge/Tesseract-OCR-orange.svg)](https://github.com/tesseract-ocr/tesseract)
[![Poppler](https://img.shields.io/badge/Poppler-PDF--tools-green.svg)](https://github.com/oschwartz10612/poppler-windows)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Conversie automată a fișierelor PDF în text editabil folosind OCR pentru limba română 🇷🇴.

---

## ⚡ Descriere

Acest script Python:
- Convertește PDF-uri în imagini.
- Aplică OCR folosind **Tesseract** cu suport pentru limba română.
- Returnează textul extras într-un fișier `.txt`.

---

## 🚀 Instalare completă „de la zero”

### ✅ 1. Instalează Python
Descarcă și instalează Python (minim versiunea 3.8):  
👉 [https://www.python.org/downloads/](https://www.python.org/downloads/)

🔔 Nu uita să bifezi ✅ **Add Python to PATH** la instalare.

---

### ✅ 2. Instalează Poppler
- Descarcă Poppler pentru Windows:  
  👉 [https://github.com/oschwartz10612/poppler-windows/releases/](https://github.com/oschwartz10612/poppler-windows/releases/)
- Dezarhivează și adaugă calea către folderul `bin` în variabila globală **PATH**.

📌 Ex.:  



---

### ✅ 3. Instalează Tesseract OCR
- Descarcă Tesseract de aici:  
  👉 [https://github.com/tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract)

- Instalează și notează locația, de obicei:


- Verifică dacă ai fișierul pentru limba română `ro.traineddata` în:


Dacă lipsește, îl poți descărca de aici:
👉 [https://github.com/tesseract-ocr/tessdata/blob/main/ro.traineddata](https://github.com/tesseract-ocr/tessdata/blob/main/ro.traineddata)

---

### ✅ 4. Instalează pachetele Python
În terminal (CMD, PowerShell):
```bash
pip install -r requirements.txt

pdf2image
pytesseract
Pillow



🧠 Biblioteci și programe folosite
Nume	Rol	Instalare
pdf2image	Conversie PDF → imagini	pip install pdf2image
pytesseract	OCR pe imagini cu Tesseract	pip install pytesseract
Pillow	Manipulare imagini în Python	pip install Pillow
Tesseract	Motorul OCR propriu-zis	Instalare separată
Poppler	Extrage imagini din PDF-uri	Instalare separată
