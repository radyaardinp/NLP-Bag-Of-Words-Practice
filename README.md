# **Text Classification using Bag-of-Words**  

## **Overview**  
Proyek ini bertujuan untuk melakukan klasifikasi teks berdasarkan Bag-of-Words (BoW) dengan tiga kategori utama: **Kesehatan, Olahraga, dan Keuangan**. Model akan dilatih menggunakan teks/artikel dari masing-masing topik, kemudian digunakan untuk mengklasifikasikan teks baru ke dalam kategori yang paling relevan.  

## **Workflow**  
1. Dataset Preparation 
   - Mengumpulkan tiga artikel sebagai data pelatihan dengan kategori Kesehatan, Olahraga, dan Keuangan.  
   - Melakukan preprocessing teks (lowercasing, tokenization, stopword removal, dll.).  

2. Feature Extraction (Bag-of-Words Vectorization) 
   - Mengonversi teks menjadi representasi numerik menggunakan Bag-of-Words.  
   - Menghitung vektor BoW untuk setiap kategori.  

3. Text Classification
   - Menggunakan model sederhana untuk mengklasifikasikan teks berdasarkan **BoW**.  
   - Menguji model dengan teks berikut:  
     > *"Cristiano Ronaldo came off the bench to earn Manchester United a hard-fought 2-1 victory at Everton in the Premier League on Sunday, taking his career goal tally to 700 in the process..."*  
   - Menentukan kategori yang paling relevan (Olahraga).  

## **Tools & Libraries**  
- **Python** (Google Colab, Jupyter Notebook)  
- **Libraries**: `NumPy`, `Pandas`, `Scikit-learn`, `NLTK`, `Matplotlib`  

## **Results & Insights**  
- Model berhasil mengklasifikasikan teks dengan pendekatan Bag-of-Words.  
- Visualisasi vektor kata dan distribusi fitur antar kategori.  
- Potensi peningkatan dengan metode lain seperti TF-IDF atau Word Embeddings.  

## **How to Use**  
1. Clone repository:  
   ```bash
   git clone https://github.com/your-username/NLP-Bag-Of-Word-Practice.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook untuk eksplorasi dan training model.  

---

