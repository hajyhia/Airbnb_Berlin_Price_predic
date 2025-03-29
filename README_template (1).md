# 🧠 Price Prediction of Berlin Airbnb accommodation

Airbnb is a global online marketplace that connects people looking for accommodations with hosts who have spaces to rent. It operates through both a website and a mobile application, making it easy for travelers to find short-term rentals, vacation homes, and even experiences offered by locals. 
Airbnb enables people to rent out their properties, apartments, or even shared spaces to travelers looking for accommodation. It operates through a website (www.airbnb.com) and a mobile app

## Key Features of Airbnb
- Search and Booking – Users can search for accommodations based on location, price, type, and amenities.
- Filters and Categories – Listings are categorized by type (e.g., entire home, private room, shared room).
- Reviews and Ratings – Travelers can check ratings and reviews from previous guests.
- Secure Payments – Airbnb provides a secure payment system to protect both guests and hosts.

## Project Goal
The objective of this project is to predict the price of accommodations based on a summary of available features.

---

## 📂 Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 Overview

This dataset provides detailed information on Airbnb listings in Berlin, including reviewer ratings and guest comments. It enables exploration of property characteristics, host profiles, and guest experiences in the German capital.

This project aims to to predict the price of accommodations based on a summary of available features.  
It uses Python and various machine learning libraries to _(summary of methodology or techniques used)_.

**Problem Type:** Regression 

**Main Objective:** Predict Airbnb rental prices based on property Accomodates, location, Room Type and Property Type and more features.

---

## 🏗️ Project Structure

```
project-name/
│
├── content/            # Raw and processed datasets
├── notebooks/          # Jupyter notebooks for EDA and model development
├── models/             # Trained models and serialized files
├── src/                # Core scripts: preprocessing, training, evaluation
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── pyproject.toml      # Project dependencies and settings
|__ poetry.lock         
```

---
## 🚀 Getting Started

Instructions to get a copy of the project running locally.

### Prerequisites

- Download [Airbnb Berlin.csv](https://www.kaggle.com/datasets/thedevastator/berlin-airbnb-ratings-how-hosts-measure-up/data)
- Intsall python
  
## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/hajyhia/Airbnb_Berlin_Price_predic.git
cd Airbnb_Berlin_Price_predic
```

Create a virtual environment and install dependencies:
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 🚀 Usage

Run data preprocessing:
```bash
python src/preprocess.py
```

Train the model:
```bash
python src/train.py
```

Evaluate performance:
```bash
python src/evaluate.py
```

---

## 🧪 Model Details

- **Algorithm(s):** Linear Regression, Random Forest, XGBoost, etc.
- **Evaluation Metrics:** RMSE, MAE, R² Score
- **Features Used:** "Guests Included","Room Type","Bedrooms","Accomodates","Cleanliness Rating","Location Rating","Value Rating","Property Type Reduced","Distance From Center","Reviews","Beds","Host Since From Now"

---

## 📊 Results

Summary of model performance:  
- Validation RMSE: xxx  
- Test R² Score: xxx

Optional: Add graphs, confusion matrix, or screenshots here.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
