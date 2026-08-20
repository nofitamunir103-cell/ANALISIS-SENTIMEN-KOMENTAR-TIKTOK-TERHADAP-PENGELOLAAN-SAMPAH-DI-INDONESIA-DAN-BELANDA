
# Perbandingan Metode Naive Bayes, Support Vector Machine, dan Logistic Regression dalam Analisis Sentimen Komentar TikTok terhadap Pengelolaan Sampah di Indonesia dan Belanda

Repositori ini berisi kode program dan data penelitian skripsi mengenai analisis sentimen komentar TikTok terhadap pengelolaan sampah di Indonesia dan Belanda, dengan membandingkan tiga algoritma klasifikasi: Naive Bayes, Support Vector Machine, dan Logistic Regression.

## Penulis
**Nofita Munir** (1222001019)  
Program Studi Informatika, Fakultas Teknik  
Universitas Bakrie

## Isi Repositori
- `Analisis_Sentimen_Nofita.ipynb` — Notebook Google Colab berisi seluruh proses penelitian
- `data_labeling.xlsx` — Data akhir hasil pelabelan sentimen

## Tahapan Penelitian
1. **Pengumpulan Data** — komentar dari tujuh unggahan TikTok dikumpulkan menggunakan Apify
2. **Penerjemahan** — komentar berbahasa Belanda diterjemahkan ke Bahasa Indonesia
3. **Preprocessing** — cleaning, case folding, normalization, tokenizing, stopword removal, dan stemming
4. **Pelabelan** — pendekatan rule-based menggunakan InSet Lexicon, dilengkapi aturan negasi dan penanganan sarkasme
5. **Pembobotan** — transformasi teks menjadi fitur numerik menggunakan TF-IDF
6. **Klasifikasi** — Naive Bayes, Support Vector Machine, dan Logistic Regression
7. **Evaluasi** — confusion matrix dengan metrik accuracy, precision, recall, dan F1-score

## Hasil
Pada perbandingan kinerja model, Logistic Regression memperoleh hasil terbaik dengan akurasi 75,91%, diikuti Support Vector Machine sebesar 74,62% dan Naive Bayes sebesar 71,83%.

## Tools
- Google Colab
- Python (pandas, scikit-learn, Sastrawi)
- Apify (scraping data TikTok)
- InSet Lexicon (pelabelan sentimen)
