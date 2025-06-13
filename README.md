<h1 style="font-size: 70px; font-weight: bold;">
  <img src="static/BostonLogo2.png" alt="Logo" style="height: 80px; vertical-align: middle; margin-right: 20px;">
  Boston House Price Predictor
</h1>

## 📌 Project Overview:
![Boston House Price Prediction image](https://github.com/user-attachments/assets/3c8bc59b-f56d-4d7f-978c-1f596bf9ae5d)

A Web appplication project that uses machine learning to predict Boston house prices based on various features like crime rate, number of rooms, and property tax. It’s built with Flask for the web interface and Scikit-learn for predictive modeling.
Built by [Sitesh Gupta](https://github.com/Siteshgupta123)

----------------------
## Demo:
**Try the web app here:** 
- https://boston-house-price-predicton.onrender.com/

---------------------
## Features:
✨ **Interactive Form**  
- Input 13 neighborhood characteristics
- Real-time validation
- Tooltips explaining each field

📊 **Instant Predictions**  
- Clear results display
- BK effect calculation shown separately
- Attractive price highlighting

🎨 **Beautiful UI**  
- Boston-themed background
- Responsive design (works on mobile/desktop)
- Animated confetti celebration
----------------
### 📦 Installation:
Step 1: Clone the Repository
```git clone https://github.com/Siteshgupta123/Boston-House-Price-Predicton.git
cd Boston-House-Price-Predicton
```
Step 2: Install Dependencies
```
pip install -r requirements.txt
```
Step 3: Run the Flask App
```
python app.py
```
Step 4 : Open in browser:
Your app should now be running at: 
```
http://127.0.0.1:5000
```
Step 5: Fill the form and Click "Predict"

-------------
## 📊 How It Works
### 1️⃣ Enter House Features:
Try these inputs to verify it works:
- CRIM: 0.21
- ZN: 18
- INDUS: 2.31
- CHAS: 0
- NOX: 0.53
- RM: 6.57
- AGE: 65.2
- DIS: 4.09
- RAD: 1
- TAX: 296
- PTRATIO: 15.3
- LSTAT: 4.98
- BK: 3.63
### 2️⃣ Model Predicts Price:
The trained model processes input features and predicts the house price.
### 3️⃣ Display Prediction:
The web app displays the predicted price with a user-friendly interface.
- **You should see:**
  - BK Effect: -9000.00
  - Predicted Price: $58,880.00
------------------------------

## Key Files:
| File                | Purpose                                |
|---------------------|----------------------------------------|
| `index.html`        | Main UI (HTML/CSS/JS)                  |
| `app.py`           | Flask backend server                   |
| `static/`          | Images, logos, and icons               |
| `templates/`       | HTML templates for Flask               |

## 📜 File Structure:
```
Boston-House-Price-Predicton/
│── app.py               # Flask backend
│── requirements.txt      # Dependencies
│── templates/
│   └── index.html       # Frontend UI
│── static/
│   └── BostonLogo2.png  # Logo image
│── house_price_prediction.pkl # Trained ML model
```
-----------------------------

## Contributing:
1.Fork the project.
2.Create your feature branch.
```
git checkout -b feature/AmazingFeature
```
3.Commit changes.
```
git commit -m 'Add amazing feature'
```
4.Push to branch.
```
git push origin feature/AmazingFeature
```
5.Open a Pull Request

--------------------------------
## Thank You! 💙

Thanks for checking out my project! If you found it useful, please consider:  
[![GitHub stars](https://github.com/Siteshgupta123/Boston-House-Price-Predicton)](https://github.com/Siteshgupta123)  
⭐ **Starring** the repo  
🐛 **Reporting** issues  
🛠 **Contributing** improvements  

Coded with ❤️ by **Sitesh Gupta**  
🔗 www.linkedin.com/in/guptasitesh | 💌 Email-guptasitesh05@email.com

