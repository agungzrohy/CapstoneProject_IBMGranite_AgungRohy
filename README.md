# Mendeteksi Berita Hoaks Menggunakan AI IBM Granite By AgungRohy

Mendeteksi Berita Hoaks Menggunakan AI IBM Granite
📖 Ringkasan Proyek
Proyek ini adalah sebuah sistem cerdas untuk mengklasifikasikan artikel berita sebagai REAL atau FAKE secara otomatis. Daripada melatih model machine learning dari nol, proyek ini memanfaatkan kemampuan zero-shot learning dari IBM Granite, sebuah Large Language Model (LLM), untuk menganalisis dan meringkas teks berita dengan akurasi tinggi melalui prompt engineering.

📊 Dataset
Nama: Fake and Real News Dataset

Sumber: Kaggle (Publik)

Link: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

🛠️ Teknologi yang Digunakan
Bahasa Pemrograman: Python

Lingkungan: Google Colab

Library Utama: Pandas, Scikit-learn

Model AI: IBM Granite (ibm-granite/granite-3.3-8b-instruct)

Platform API: Replicate

⚙️ Proses Analisis
Persiapan Data: Dataset berita dari Kaggle diunduh, dibersihkan, dan disiapkan untuk analisis.

Prompt Engineering: Instruksi (prompt) yang jelas dirancang untuk memerintahkan AI melakukan dua tugas utama:

Klasifikasi: Menentukan apakah berita itu REAL atau FAKE.

Peringkasan: Membuat rangkuman netral dari isi berita.

Eksekusi via API: Setiap artikel dikirim ke model IBM Granite melalui API untuk diproses.

Evaluasi: Hasil prediksi dievaluasi menggunakan metrik standar seperti akurasi, presisi, dan recall untuk mengukur performa.

✨ Fitur Utama
Klasifikasi Akurat: Mampu membedakan berita REAL dan FAKE dengan akurasi tinggi tanpa perlu fine-tuning.

Peringkasan Otomatis: Menghasilkan ringkasan abstrak (bukan sekadar salin-tempel kalimat) untuk membantu verifikasi cepat.

Implementasi Cepat: Menggunakan pendekatan zero-shot yang menghemat waktu dan sumber daya komputasi.

🚀 Hasil & Rekomendasi
Kesimpulan: Model IBM Granite terbukti sangat efektif untuk tugas klasifikasi berita hoaks, mencapai akurasi yang sangat baik pada data sampel.

Rekomendasi: Sistem ini dapat dikembangkan lebih lanjut menjadi plugin browser atau API layanan mikro untuk menyediakan verifikasi fakta secara real-time.
