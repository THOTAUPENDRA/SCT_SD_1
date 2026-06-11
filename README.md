 🌡️ Temperature Converter

A simple **Temperature Converter Web Application** built using **Python and Streamlit**. This application allows users to convert temperatures between **Celsius, Fahrenheit, and Kelvin** with an easy-to-use interactive interface.

## 🚀 Features

- Convert temperatures between:
  - Celsius to Fahrenheit
  - Celsius to Kelvin
  - Fahrenheit to Celsius
  - Fahrenheit to Kelvin
  - Kelvin to Celsius
  - Kelvin to Fahrenheit
- User-friendly Streamlit interface
- Instant conversion results
- Supports decimal temperature values

## 🛠️ Technologies Used

- Python
- Streamlit

## 📂 Project Structure


Temperature-Converter/
│
├── app.py
└── README.md


## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/temperature-converter.git
Step 2: Open Project Folder
cd temperature-converter
Step 3: Install Required Package
pip install streamlit
▶️ Run the Application

Run the following command:

streamlit run app.py

The application will open in your default web browser.

📌 How to Use
Enter the temperature value.
Select the original temperature unit from the From dropdown.
Select the conversion unit from the To dropdown.
View the converted result instantly.
🧮 Conversion Formulas
Celsius to Fahrenheit
°F = (°C × 9/5) + 32
Fahrenheit to Celsius
°C = (°F - 32) × 5/9
Celsius to Kelvin
K = °C + 273.15
Kelvin to Celsius
°C = K - 273.15
💻 Application Code Overview

The program:

Takes temperature input using st.number_input()
Uses dropdown menus with st.selectbox() for unit selection
Converts values through the convert_temperature() function
Displays the final result using Streamlit components
📸 Screenshot

Add your application screenshot here.

🤝 Contributing

Contributions are welcome.

Steps:

Fork the repository
Create a new branch
Make improvements
Submit a pull request
📄 License

This project is open-source and available under the MIT License.
