# Sentiment-Analysis-on-Political-Tweets
Proyek ini mengklasifikasikan opini publik di Twitter menjadi sentimen positif, negatif, atau netral menggunakan Natural Language Processing (NLP) dan Machine Learning. Data tweet diekstraksi, dibersihkan, lalu dianalisis untuk memvisualisasikan tren sentimen dan membuat model untuk dapat melakukan klasifikasi sentimen.

## Ringkasan Singkat
- **Dataset**: 1.815 tweet terkait debat Pilpres 2019, distribusi kelas seimbang.
- **Representasi**: TF-IDF (baseline), FastText embedding (DL/Transformer).
- **Model**: Logistic Regression, SVM, Naive Bayes, Random Forest, LSTM, Hybrid CNN+LSTM, IndoBERT.
- **Metrik**: Akurasi, Precision, Recall, F1 per kelas.
- **Hasil inti**: LR dan NB stabil; RF overfit; IndoBERT dan LR unggul di validasi, namun masih ada kebingungan negatif↔positif dan drift netral→positif.
- **Isu utama**: Overfitting dini pada model sekuens dan transformer; fitur polaritas kuat dan penanganan negasi/ironi masih terbatas.

