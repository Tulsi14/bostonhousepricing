# Boston House Pricing Prediction 

This is an end-to-end Machine Learning project that predicts house prices in Boston based on various socio-economic and geographical features. The project implements a **Linear Regression** model and is served via a web interface.

---

## 📂 Project Structure

| File Name | Description |
| :--- | :--- |
| `app.py` | The main FastAPI/Flask application to handle web requests and model predictions. |
| `Linear Regression ML Implementation.ipynb` | Jupyter Notebook containing data analysis, feature engineering, and model training logic. |
| `regmodel.pkl` | The serialized (pickled) trained Linear Regression model. |
| `scaling.pkl` | Pickled StandardScaler object used to scale input data before prediction. |
| `home.html` | Front-end UI template for user interaction. |
| `requirements.txt` | List of Python dependencies required to run the project. |
| `.gitignore` | Specifies files to be ignored by Git (like venv or temporary files). |

---

## 🛠️ Tech Stack
- **Language:** Python 3.8+
- **Machine Learning:** Scikit-Learn, Pandas, NumPy
- **Algorithm:** Linear Regression
- **Web Framework:** Flask / FastAPI
- **Model Serialization:** Pickle

---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Tulsi14/bostonhousepricing.git](https://github.com/Tulsi14/bostonhousepricing.git)
   cd bostonhousepricing
