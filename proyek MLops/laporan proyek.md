# Submission 1: Proyek Sentiment- Analysis
Nama: Azhar Zuhro

Username dicoding: azharzuhro


| | Deskripsi |
| ----------- | ----------- |
| Dataset | [sentiment_analiysis.csv](https://www.kaggle.com/datasets/dineshpiyasamara/sentiment-analysis-dataset) |
| Masalah | Analisis sentimen menggunakan pemrosesan bahasa alami dan teknik pembelajaran mesin untuk menganalisis nada emosional atau sentimen di balik sebuah teks. Ini melibatkan mengidentifikasi dan mengkategorikan pendapat yang diungkapkan dalam teks sebagai positif, negatif, atau netral |
| Solusi machine learning | lewat masalah ini dengan machine learning bisa membedakan dan mengidentifikasi pendaat yang di ungkapkan itu positif atau negatif |
| Metode pengolahan | dalam metode pengolahan ini saya pisah data tersebut menjadi dua yaitu untuk data pelatihan 80 dan untuk data evaluasi menjadi 20, setelah itu data akan menuju tahap validasi dan setelah itu di kirim ke endpoit |
| Arsitektur model | Model yang dibangun cukup sederhana hanya  terdiri dari layer Embedding dan  layer Dense sebagai hidden layer, terus saya pada output layer menggunakan Sigmoid karena dalam kasus ini adalah _binary classification_.|
| Metrik evaluasi | saya menggunakan metrik klasifikasi seperti ExampleCount, AUC, FalsePositives, TruePositives, FalseNegatives,TrueNegatives dan BinaryAccuracy  |
| Performa model | untuk Evaluasi model yang di dapatkan yaitu AUC sebesar  73%, kemudian example_count: 78,false Negatives: 18, False Positive: 21, True Negative 19, True Positive: 20, 
dan dengan BinaryAccuracy: 0.9716, loss: 0.0897 |
| Web app | (http://103.190.215.87:8501/v1/models/cc-model/metadata)|
| Monitoring | untuk monitoring saaya menggunakan  Prometheus dan Grafana untuk performa sudah lumayan bagus tapi perlu di tingkatkan |
