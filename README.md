🎬 Hybrid Movie Recommendation System

📌 Project Overview

This project implements a Hybrid Recommendation System combining:

Content-Based Filtering (TF-IDF + Cosine Similarity)

User-Based Collaborative Filtering

Weighted Hybrid Model

Built using Python and Machine Learning techniques on the MovieLens dataset.

🚀 Features

Personalized movie recommendations

Hybrid weighted scoring model

Evaluation using RMSE

Visualization of similarity scores

Clean modular architecture

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

📊 Methodology
1️⃣ Content-Based Filtering

Uses TF-IDF vectorization on movie genres.

2️⃣ Collaborative Filtering

Computes user similarity using cosine similarity.

3️⃣ Hybrid Model

Final Score:

𝑆
𝑐
𝑜
𝑟
𝑒
=
𝛼
(
𝐶
𝑜
𝑛
𝑡
𝑒
𝑛
𝑡
𝑆
𝑐
𝑜
𝑟
𝑒
)
+
𝛽
(
𝐶
𝑜
𝑙
𝑙
𝑎
𝑏
𝑜
𝑟
𝑎
𝑡
𝑖
𝑣
𝑒
𝑆
𝑐
𝑜
𝑟
𝑒
)
Score=α(ContentScore)+β(CollaborativeScore)
📈 Evaluation

RMSE (Root Mean Square Error)

Precision@K (conceptual)

Qualitative comparison

📁 Dataset

MovieLens 20M Dataset
https://grouplens.org/datasets/movielens/

👩‍💻 Author

Bhanpurawala Batul Yusuf
Maulana Mukhtar Ahmad Nadvi Technical Campus, Malegaon
