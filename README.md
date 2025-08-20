1. Capstone Project - Analisis Tren Saham & Sentimen Pasar untuk Investor Pemula

2. Project Overview
  Capstone project ini bertujuan membantu investor pemula memahami tren pasar saham Indonesia dengan pendekatan yang sederhana namun berbasis data. Banyak investor pemula kesulitan karena data finansial biasanya disajikan dalam bentuk angka kompleks dan berita panjang yang sulit dicerna.
    -Permasalahan utama:
Bagaimana investor pemula bisa cepat memahami tren harga saham tanpa harus menganalisis grafik rumit?
Bagaimana mereka bisa tahu “suasana pasar” (sentimen) tanpa membaca ratusan artikel berita?
    -Solusi yang ditawarkan:
Menggabungkan analisis tren saham (BBCA, BBRI, TLKM, IHSG) dengan sentimen analysis dari berita investasi, kemudian menyajikannya dalam bentuk insight singkat menggunakan AI (IBM Granite). Dengan begitu, investor pemula tidak hanya melihat angka, tapi juga mendapatkan gambaran arah pasar dan rekomendasi yang lebih mudah dipahami.

3. Raw Dataset
-https://colab.research.google.com/drive/1pi01pQ3iL8FLP-_rutOZJqrehCcWyt0p?usp=sharing
-https://drive.google.com/drive/folders/1TGqhFHe6MENTze6TjjwFRY5D3qMNT1AX?usp=drive_link

4. Analysis Process
  -Pengumpulan Data
Harga saham harian BBCA, BBRI, TLKM, dan IHSG periode 2020–2025. Kumpulan berita finansial periode 2020–2025.
  -Preprocessing & Explorasi Data
Membersihkan data harga saham, mengatasi missing value. Menyusun tren harga per bulan agar lebih mudah dibaca. Mengubah teks berita ke format yang bisa dianalisis AI.
  -Analisis Tren Saham
Melihat kenaikan/penurunan harga bulanan. Membandingkan volatilitas saham bluechip (BBCA, BBRI) dengan indeks IHSG. Menarik pola umum (misalnya: BBCA lebih stabil, BBRI lebih fluktuatif).
  -Analisis Sentimen Berita
Menggunakan teknik sentiment analysis sederhana untuk menilai apakah berita bernuansa positif, negatif, atau netral. Misalnya: “Bank digital berkembang pesat” → sentimen positif.
  -AI Summarization dengan IBM Granite 
AI dipakai untuk meringkas berita finansial panjang menjadi insight singkat. Contoh: Daripada membaca 10 artikel tentang perbankan, AI merangkum jadi 2 kalimat utama.

5. Insight & Findings
-Saham BBCA menunjukkan kestabilan lebih tinggi dibanding BBRI dalam periode analisis. Cocok untuk investor pemula yang cenderung menghindari risiko tinggi.
-Saham BBRI lebih fluktuatif, dengan beberapa periode kenaikan signifikan. Bisa menarik bagi investor pemula yang ingin belajar memahami risiko.
-IHSG dapat dijadikan indikator umum arah pasar. Saat IHSG melemah, mayoritas saham ikut turun.
-Berita finansial berpengaruh pada sentimen pasar:
  #Berita positif terkait digitalisasi perbankan mendorong optimisme.
  #Berita negatif terkait regulasi atau inflasi menekan harga saham.
-AI summarization membuat berita panjang lebih mudah dipahami, misalnya ringkasan 2–3 kalimat tentang kondisi sektor perbankan bulan ini.

6. Conclusion & Recommendation
Berdasarkan analisis, beberapa rekomendasi untuk investor pemula adalah:
-Fokus pada saham bluechip (seperti BBCA & BBRI) karena volatilitas lebih rendah dibanding saham second liner.
-Gunakan sentimen berita sebagai pelengkap analisis harga. Jika berita mayoritas positif, potensi kenaikan lebih besar.
-Gunakan AI insight sebagai panduan awal, tetapi tetap kombinasikan dengan analisis pribadi sebelum membeli.
-Mulailah dengan jumlah investasi kecil sambil belajar membaca pola pasar.

7. AI Support Explanation
-AI (IBM Granite) meringkas berita menjadi insight singkat, sehingga investor pemula tidak kewalahan.
-AI membantu memberi label positif/negatif/netral pada berita.
-Investor pemula bisa menghemat waktu, mendapatkan gambaran pasar dengan cepat, dan membuat keputusan lebih percaya diri.
-Dengan demikian, AI bukan menggantikan investor, tapi memberi alat bantu pintar agar pemula bisa memulai investasi dengan informasi yang lebih jelas.
