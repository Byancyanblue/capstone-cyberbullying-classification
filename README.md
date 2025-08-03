---

# 🧠💬 Klasifikasi Komentar Cyberbullying dengan IBM Granite

## 🚀 Project Overview

Cyberbullying adalah salah satu ancaman paling nyata di dunia digital saat ini. Proyek ini menghadirkan solusi berbasis **AI Generatif (LLM)** untuk mendeteksi dan memahami komentar-komentar yang mengandung unsur bullying di media sosial berbahasa Indonesia.

Dengan memanfaatkan **model IBM Granite**, proyek ini secara otomatis:

* Mengklasifikasikan komentar sebagai **"Bullying"** atau **"Bukan Bullying"**
* Merangkum komentar secara singkat namun bermakna
* Memberikan insight awal tentang pola-pola komentar negatif yang sering muncul

🎯 **Tujuan utama:** Membantu moderator, peneliti, dan organisasi sosial dalam mengenali potensi cyberbullying dengan lebih cepat dan efisien.

---

## 📂 Dataset

🔗 **Raw Dataset Source**:
[Cyberbullying Indonesia Dataset - Hugging Face](https://huggingface.co/datasets/kairaamilanii/cyberbullying-indonesia)

* Bahasa: Indonesia
* Jumlah data: 650 komentar
* Label: Bullying dan Bukan Bullying
* Format: CSV

---

## 🔍 Insight & Findings

✅ Komentar bullying cenderung memiliki panjang kalimat yang **lebih pendek**, menunjukkan kecenderungan ekspresi langsung atau kasar.
✅ **Distribusi kategori cukup seimbang** antara Bullying dan Non-Bullying, cocok untuk model klasifikasi.
✅ **Kesalahan klasifikasi** terjadi terutama pada komentar yang ambigu atau sarkastik, mengindikasikan kebutuhan terhadap prompt atau fine-tuning yang lebih tajam.
✅ **Ringkasan AI** membantu mempercepat pemahaman komentar kompleks dalam satu kalimat utama.

📊 Hasil awal menunjukkan bahwa AI dapat menjadi alat bantu ampuh dalam proses moderasi dan riset komentar negatif secara real time.

---

## 🤖 How AI Supports This Project

### 🔧 Tools & Models Used:

* **LLM**: IBM Granite 13B Chat v2 (via Vertex AI)
* **Language**: Python (Jupyter Notebook)
* **Libraries**: Pandas, scikit-learn, Matplotlib, Seaborn

### 🔍 AI Usage in Action:

| Aktivitas                 | Deskripsi                                                                    |
| ------------------------- | ---------------------------------------------------------------------------- |
| ✂️ Summarization          | Komentar diringkas menjadi 1 kalimat padat untuk cepat dipahami.             |
| 🧠 Classification         | AI mengklasifikasi komentar sebagai *Bullying* atau *Bukan Bullying*.        |
| 📊 Analisis & Visualisasi | Distribusi, perbandingan panjang komentar, dan confusion matrix ditampilkan. |

### 🧪 Prompting Strategy:

* Prompt yang paling efektif bersifat **spesifik** dan **satu tugas per prompt**
* Pemisahan antara prompt untuk ringkasan dan klasifikasi meningkatkan konsistensi output

---

## 📌 Key Takeaways

💡 **AI meningkatkan efisiensi analisis komentar sosial media** dengan mengurangi beban kerja manual dan mempercepat insight extraction.
💡 Insight yang diperoleh bisa membantu dalam membangun sistem deteksi bullying berbasis LLM, atau memperkuat metode klasifikasi tradisional lewat feature engineering tambahan.

📢 **Rekomendasi selanjutnya**:

* Lakukan evaluasi model secara menyeluruh pada seluruh dataset (bukan hanya sampel)
* Pertimbangkan fine-tuning atau penggunaan model lokal jika privasi dan efisiensi menjadi prioritas
* Integrasikan sistem ini ke dalam workflow moderasi sosial media atau aplikasi edukatif

---

> "AI doesn't just classify — it empowers us to understand, act, and protect."

---
