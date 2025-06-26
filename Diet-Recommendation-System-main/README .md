# 🥗 Diet Recommendation System using Machine Learning

## 🚀 Overview

This project is a **Diet Recommendation System** built using **Machine Learning** techniques to provide personalized dietary suggestions. It uses **K-Means Clustering** to segment users based on health features and a **Random Forest Classifier** to recommend appropriate diet plans. The application features a **FastAPI** backend, an interactive **Streamlit** frontend, and is fully containerized with **Docker** for easy deployment.

---

## ✅ Features

- 🔍 User segmentation using K-Means Clustering
- 🌿 Personalized diet prediction with Random Forest
- ⚡ Fast and interactive API powered by FastAPI
- 🖥️ User-friendly interface built with Streamlit
- 🐳 Dockerized environment for smooth deployment

---

## 🧠 ML Algorithms Used

### 1. K-Means Clustering
- Groups users based on input features (e.g., age, BMI, activity level)
- Enables cluster-wise diet recommendation logic

### 2. Random Forest Classifier
- Predicts the best-fit diet plan for users
- Trained on historical diet and health data

---

## 🧰 Tech Stack

- **Python** – core development
- **Scikit-learn** – machine learning models
- **FastAPI** – REST API framework
- **Streamlit** – frontend UI
- **Docker** – containerization
- **Pandas / NumPy / Matplotlib** – data handling and visualization

---

## 💻 How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/diet-recommendation-system.git
cd diet-recommendation-system
```

### Step 2: Run with Docker

```bash
docker-compose up --build
```

### Step 3: Access the Interfaces

- 🚀 FastAPI Docs: [http://localhost:8000/docs](http://localhost:8000/docs)
- 🖥️ Streamlit App: [http://localhost:8501](http://localhost:8501)

---

## 📁 Project Structure

```
diet-recommendation-system/
├── app/
│   ├── main.py              # FastAPI entry point
│   ├── models/              # ML models and training scripts
│   ├── utils/               # Preprocessing and utilities
│   └── data/                # Sample input/output data
├── streamlit_app/
│   └── ui.py                # Streamlit UI code
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

## 📌 Input Parameters

- Age
- Gender
- Height & Weight
- BMI
- Activity level
- Health conditions (optional)

---

## 📈 Future Enhancements

- Add support for diabetic/heart patient diet options
- Integrate food API for real-time meal suggestions
- Weekly meal plan generation and export
- User authentication and profile tracking

---

## 🧑‍💻 Author

**Your Name**  
GitHub: [@yourusername](https://github.com/yourusername)  
Email: your.email@example.com

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.