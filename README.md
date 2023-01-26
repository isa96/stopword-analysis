# stopword-analysis
Stopword Analysis on Text Mining - With dataset from Kaggle: https://www.kaggle.com/nltkdata/web-text-corpus

**Conclusion**: 
Dari percobaan studi kasus ini didapatkan bahwa, 
map yang dihasilkan dari tiap metode baik menggunakan nltk, mi & zipf law rendah, 
hal ini dikarenakan corpus yang digunakan memiliki jumlah kata yang sedikit di setiap dokumennya. 
dan jika dilihat dari hasil evaluasi menggunakan precision@k, maka metode yang terbaik yang digunakan untuk menentukan stopword adalah 
nltk dan mutual information, karena jika dilihat dari grafik, kecenderungan query yang memiliki tingkat precision@k yang rendah kebanyakan 
ada jika menggunakan metode zipf law, hal ini diakibatkan karena beberapa query memiliki dokumen relevant yang sedikit, 
dari jumlah yang ditentukan yaitu lima dokumen teratas, berdasarkan nilai cossim dengan query yang dipilih.
