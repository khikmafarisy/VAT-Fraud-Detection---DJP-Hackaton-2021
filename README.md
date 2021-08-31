# VAT-Fraud-Detection---DJP-Hackaton-2021

Link Dataset complete : https://drive.google.com/drive/folders/1rdpENWBEW2yQKxzReF09v8cpIfjX5tzf?usp=sharing


Gambaran skema algoritma yang digunakan pada hackaton DJP 2021 dengan tema VAT & Cross-Border Fraud Detection :
![image](https://user-images.githubusercontent.com/39217656/131471534-5b5bd1b1-7f84-4afb-ab3c-4ec681329ae8.png)

Pada skema ini kita menggabungkan 2 jenis algoritma ML yaitu :
1. LDA Topic Modelling yang merupakan unsupervised ML untuk mencari topic-topic abstrak yang relevan pada dataset yang berupa sekumpulan 'word documents'.
2. Isolation Forest (unsupervised ML) yang digunakan untuk menentukan datapoint yang dianggap anomali dengan asumsi contamination 5%.

