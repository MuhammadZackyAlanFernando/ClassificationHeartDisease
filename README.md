# 🫀 Heart Disease Classification

Proyek klasifikasi penyakit jantung menggunakan Machine Learning di Google Colab.

## 📊 Dataset
- **Sumber**: [UCI Heart Disease Dataset / Kaggle]
- **Jumlah Sampel**: 303
- **Fitur**: 
| Feature  | Description | Example Values |
|:-----|:-----|:------|
| **age** | Age in years | 29, 45, 60 |
| **sex** | 1 = male; 0 = female | 0, 1  |
| **cp**  | Chest pain type | 0: Typical angina (chest pain), 1: Atypical angina (chest pain not related to heart), 2: Non-anginal pain (typically esophageal spasms (non heart related), 3: Asymptomatic (chest pain not showing signs of disease) |
| **trestbps** | Resting blood pressure (in mm Hg on admission to the hospital)  | 120, 140, 150 |
| **chol** | Serum cholesterol in mg/dl | 180, 220, 250 |
| **fbs** | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) | 0, 1 |
| **restecg** | Resting electrocardiographic results | 0: Nothing to note, 1: ST-T Wave abnormality, 2: Left ventricular hypertrophy  |
| **thalach** | Maximum heart rate achieved | 160, 180, 190 |
| **exang**  | Exercise induced angina (1 = yes; 0 = no) | 0, 1 |
| **oldpeak**  | ST depression (heart potentially not getting enough oxygen) induced by exercise relative to rest | 0.5, 1.0, 2.0  |
| **slope** | The slope of the peak exercise ST segment | 0: Upsloping, 1: Flatsloping, 2: Downsloping |
| **ca** | Number of major vessels (0-3) colored by fluoroscopy | 0, 1, 2, 3 |
| **thal** | Thalium stress result  | 1: Normal, 3: Normal, 6: Fixed defect, 7: Reversible defect |
| **target** | Have disease or not (1 = yes; 0 = no) | 0, 1 |
- **Target**: 0 = Tidak ada penyakit, 1 = Ada penyakit

## 🚀 Cara Menggunakan

### 1. Buka di Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/heart-disease-classification/blob/main/notebooks/Heart_Disease_Classification_Full.ipynb)

### 2. Clone Repository
```python
!git clone https://github.com/username/heart-disease-classification.git
%cd heart-disease-classification
```

### 3. Install Dependencies
```python
!pip install -r requirements.txt
```

### 4. Mount Google Drive (opsional)
```python
from google.colab import drive
drive.mount('/content/drive')
```

### 5. Jalankan Notebook
Ikuti langkah-langkah di notebook secara berurutan.

## 📈 Hasil Model

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | XX% | XX% | XX% | XX% |
| Random Forest | XX% | XX% | XX% | XX% |
| KNN | XX% | XX% | XX% | XX% |

**Model Terbaik**: [Nama Model] dengan akurasi XX%

## 🛠️ Teknologi
- Python 3.10
- Google Colab
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- XGBoost / LightGBM

## 📁 Struktur Notebook

### Notebook Utama (Heart_Disease_Classification_Full.ipynb)
1. **Setup & Import Libraries**
2. **Load Data**
3. **Exploratory Data Analysis (EDA)**
4. **Data Preprocessing**
5. **Feature Engineering**
6. **Model Training**
7. **Model Evaluation**
8. **Hyperparameter Tuning**
9. **Save Model**
10. **Prediksi Data Baru**

## 🔗 Link Penting
- [Notebook Colab](https://colab.research.google.com/github/username/repo)
- [Dataset Kaggle]([link-dataset](https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fsumaiyatasmeem%2Fheart-disease-classification-dataset))
- [Dataset UCI](https://www.google.com/url?q=https%3A%2F%2Farchive.ics.uci.edu%2Fml%2Fdatasets%2Fheart%2BDisease)
- [Dokumentasi](docs/)

## 👤 Author
**[Nama Anda]**
- GitHub: [@username](https://github.com/username)
- LinkedIn: [Profile](https://linkedin.com/in/username)

## 📝 Lisensi
MIT License
