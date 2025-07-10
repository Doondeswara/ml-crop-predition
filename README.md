# 🌾 Crop Recommendation System

A Machine Learning project that predicts the most suitable crop to cultivate based on environmental and soil conditions using various supervised learning models.

---

### 📁 Project Structure

```
├── Crop_Recommendation.ipynb   # Jupyter Notebook (Google Colab)
├── requirements.txt            # Project dependencies
└── README.md                   # Project overview
```

---

### 📌 Problem Statement

Modern agriculture demands data-driven decisions. This project helps farmers identify the most suitable crop to grow based on parameters like:

- Soil nutrients (N, P, K)
- Temperature
- Humidity
- Soil pH
- Rainfall

---

### 🧪 Dataset

- **Source:** Public agricultural dataset (2200 entries)
- **Features:**
  - `N`, `P`, `K`: Soil nutrients
  - `temperature`: Environmental temperature (°C)
  - `humidity`: Relative humidity (%)
  - `ph`: Soil pH level
  - `rainfall`: Annual rainfall (mm)
- **Target:**
  - `label`: Crop type (22 classes including rice, maize, mango, cotton, etc.)

---

### 🔍 Workflow

1. **Import Libraries**
2. **Load Dataset using `pandas`**
3. **EDA (Exploratory Data Analysis)**
   - Summary stats
   - Distribution plots
   - Heatmaps & pair plots
   - Correlation analysis
4. **Data Preparation**
   - Split data into `X` (features) and `y` (target)
   - Train-test split (80:20)
5. **Model Building**
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
6. **Model Evaluation**
   - Accuracy
   - Classification report
   - Confusion matrix
7. **Model Comparison**
   - Accuracy chart
   - Bar plots
8. **Visualization**
   - N-P-K comparison between crops
   - Feature correlation heatmap

---

### 📊 Model Performance

| Model          | Accuracy (Test) |
|----------------|-----------------|
| KNN            | 97.5%           |
| Decision Tree  | 90.0%           |
| Random Forest  | 99.0% ✅        |

---

### 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`, `scikit-learn`
- **Platform:** Google Colab / Jupyter Notebook

---

### 💡 Key Learnings

- Data cleaning & EDA
- Supervised ML classification techniques
- Model tuning and comparison
- Visual storytelling using `seaborn` and `plotly`

---

### 📦 Installation

```bash
git clone https://github.com/your-username/crop-recommendation.git
cd crop-recommendation
pip install -r requirements.txt
```

> Or run the `.ipynb` notebook directly in **Google Colab**

---

### 📬 Contact

Made with ❤️ by Tammina.Doondeswara Vara Prasad

For feedback or collaboration: tamminadoondeswar@gmail.com