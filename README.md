<h1> Twitter-Sentiment-Analysis---NLP </h1>

## Overview

<p>Tweet-tweet yang digunakan pada project ini adalah tweet-tweet yang berhubungan dengan kata : AlbertEinstein. Project ini bertujuan untuk menganalisa sentimen pada kata AlbertEinstein di twitter. Kemudian pada akhirnya, ada sedikit modeling. Dimana saya menggunakan MultinominalNaiveBayes.</p>

## Results

### Words Cloud

![GitHub Logo](/images/1.png)

Dari gambar di atas, dapat dilihat kontribusi-kontribusi Einstein di dunia fisika, seperti misalnya relativitas umum dan lubang hitam. Terlihat juga ada kata Hawking dan Brian Greene di atas, dua fisikawan yang saya sangat kagumi. Menarik bisa melihat ada kata 'confirm' di atas, mungkin ini berhubungan dengan penemuan beberapa tahun yang lalu tentang gelombang gravitasi.

### Sentiment Analysis

![GitHub Logo](/images/2.png)


Kebanyakan tweet-tweet di dataset ini adalah tweet-tweet yang positive.

### Evaluation Metrics

Evaluasi metrik yang akan ditunjukkan adalah <b>Accuracy dan F1-Score (Macro-Average), dan ini hasilnya:

| Classifier | Accuracy | F1-Macro Score |
| :---: | :---: | :---: |
| `Multinominal Naive Bayes` | 0.80 | 0.80 |

Pada saat melakukan <i>sanity check</i>, sayangnya model tidak melakukannya dengan baik. Harus dilakukan pencarian hyperparameter tuning yang lebih baik atau melakukan pencarian model lainnya, selain Multinominal Naive Bayes. Namun karena tujuan dari project ini lebih mengarah ke sentiment analysis, jadi saya berhenti di model Naive Bayes.



