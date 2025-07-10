# 📓 Jurnal Harian

- Tanggal: 10 july 2025

- Yang Dipelajari/Dicoba: memahami NLM 

- Apa yang Berhasil:

- Apa yang Gagal/Harus Diperbaiki:

- Rencana Esok Hari:

# Transkrip

## Apa itu NLM
NLM digunakan unutk memproses dan menafsikan bahasa alami.yang diindentifikasi melalaui pola statiska dan banyakanuya inputran text. NLM berfungsi agar mesin memahami bahasa manusia

Komponen NLM
- Word Embending
- RNNS
- Attention Mechanism

## Word Embedding
melakukan representasi dari kata menuju vektor, dimana kata yang memiliki makna yang berdekatan memiliki nilai vektor yang sama.
tujuan dari NLM adalah agar jarak antar kata di ruang vektor mencerminakan hubgungan antar kata tersebut
sebagai contoh, terdapat dua kalimat 
"africa is beautiful" dan "Europe is beautiful"
karena "afrika" dan "Europe" sama-sama benua, kata tersebut diletakkan di ruang vektor yang berdekatann
yang menjadi kata kuncinya adalah, makna dari kaya yang berdekatan bukan perhurufnya. kata "is" dan "beautiful" tidak diletakkan di ruang vektor yang sama karna keduanya tidak memiliki hubungan yang cukup dekat (Secara Makna).

teknik popular yang biasa digunakan pada word embedding adalah
- Word2vec 
- GloVe
Word2Vec memahami berdasarkan pola kemunculan suatu kata dalam corpus. sedangkan GloVe menggunakan pendekatan membandingkan antara faktor global matrix dengna local conteks


