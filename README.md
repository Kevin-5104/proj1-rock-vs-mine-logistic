# 🎯 Rock vs Mine Prediction using Logistic Regression

This project is a simple binary classification model to distinguish between **rock** and **mine** objects based on sonar signal data. It uses **Logistic Regression**, a fundamental algorithm in machine learning, to train and test the model on labeled data.

---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository - [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs+rocks)
- **Features**: 60 numerical values representing sonar signal energy
- **Target**: 
  - `R` for Rock
  - `M` for Mine

---

## 🧠 Model Used

- **Algorithm**: Logistic Regression
- **Purpose**: Binary classification (Rock vs Mine)
- **Libraries**: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 📈 Performance

| Metric              | Score      |
|---------------------|------------|
| **Training Accuracy** | 83.42%     |
| **Testing Accuracy**  | 76.19%     |

---

rock-vs-mine-logistic/
├── rock_vs_mine_logistic.ipynb # Main Jupyter Notebook
├── sonar.csv # Dataset file (optional)
├── README.md # Project description
└── requirements.txt # Required packages


---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/rock-vs-mine-logistic.git


Install dependencies:

pip install -r requirements.txt


Run the notebook:

Open rock_vs_mine_logistic.ipynb using Jupyter Notebook or Google Colab

Run all cells to see data exploration, model training, and evaluation

📌 Key Concepts Covered

Data preprocessing

Label encoding

Train-test splitting

Logistic regression training

Accuracy evaluation

Confusion matrix and classification report

📚 Requirements

Python 3.x

scikit-learn

pandas

numpy

matplotlib

seaborn

(You can install them using the provided requirements.txt)

📌 Results

The logistic regression model demonstrates decent performance on a relatively small and noisy dataset, showcasing the basic pipeline of preprocessing → training → evaluation in supervised ML.

📫 Contact

Feel free to reach out or fork/star the repo if you find it useful!

📝 License

This project is licensed under the MIT License
.


