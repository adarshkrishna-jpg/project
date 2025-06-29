# 🌫️ AQI Prediction Web App
A modern and minimalist Air Quality Index (AQI) Prediction web app built using Streamlit, allowing users to select a location and view predicted air quality levels based on pollutant inputs.

🚀 Features

📍 Location-based AQI prediction (e.g., Karyavattom, Kollam, Eloor)

🌐 Stylish gradient background with Google Fonts and center-aligned layout

💡 Minimalist UI with responsive and animated buttons

📊 Input support for major pollutants like PM2.5, PM10, NO₂, SO₂, CO, O₃, NH₃

📉 Predicts AQI using trained machine learning model

🌓 Light and dark theme support via config.toml

🖼️ Tech Stack

Frontend: Streamlit

Backend: Python

ML Model: Pickled .pkl model (Sklearn/Regressor-based)

Design: Custom CSS for button animations and layout styling

📦 How to Run Locally
bash
Copy code
git clone https://github.com/your-username/aqi-prediction-app.git
cd aqi-prediction-app
pip install -r requirements.txt
streamlit run run.py
Make sure your directory structure is like:

arduino
Copy code
📦finalproject/
├── run.py
├── pages/
│   ├── kollam.py
│   ├── karyavattom.py
│   └── eloor.py
├── model.pkl
├── scale.pkl
└── .streamlit/
    └── config.toml
    
🎨 UI Customization

Fonts from Google Fonts (Poppins)

Custom background using CSS

Hover effects on buttons

Fully centered layout using st.columns

📌 Sample Locations
✅ Karyavattom
✅ Kollam
✅ Eloor

Each location opens a separate prediction page with pollutant inputs and output display.

📷 Screenshots
Homepage:


![Screenshot 2025-06-26 124758](https://github.com/user-attachments/assets/cedefa12-647b-493e-9dcb-885c8dec1557)

![Screenshot 2025-06-26 124738](https://github.com/user-attachments/assets/a5ea2de7-697d-4b49-8af6-76777b3d7859)



👨‍💻 Author
ADARSH KRISHNA SM
📧 adarshkrishna.me@gmail.com
🔗 adarshkrishnaa
📁 [Portfolio Website]

📝 License
This project is licensed under the MIT License.

