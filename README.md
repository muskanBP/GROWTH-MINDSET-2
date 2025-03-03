# GROWTH-MINDSET-2
# Growth Mindset Tracker

## 📌 Overview
The **Growth Mindset Tracker** is a Streamlit-based web application that enables users to track their mindset progress through structured steps and visual insights. The app allows users to upload various file formats, record self-assessments, and visualize their progress over time.

## 🚀 Features
- **Admin Authentication**: Secure access for the admin using a password.
- **File Upload & Processing**: Supports CSV, Excel, and JSON files, converting them to a structured format.
- **Mindset Rating System**: Users can rate themselves on key growth mindset factors.
- **Data Storage & Display**: Keeps user input data persistent during the session and displays it in a tabular format.
- **Interactive Data Visualization**: Uses Plotly to show progress over time with line charts.
- **Downloadable Reports**: Allows users to download their data as a CSV file.

## 🔑 Admin Login
To access the admin panel, use the following credentials:
```plaintext
Password: admin123
```
> ⚠️ **Important**: Change the password in the source code before deploying for better security.

## 📦 Installation & Setup
### Prerequisites
Ensure you have **Python 3.8+** installed, along with the required dependencies.

### Installation Steps
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/growth-mindset-tracker.git
   cd growth-mindset-tracker
   ```

2. **Create a virtual environment (optional but recommended)**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```sh
   streamlit run app.py
   ```

## 🛠️ Dependencies
The app requires the following Python libraries:
```plaintext
streamlit
pandas
numpy
plotly
```
Install them using:
```sh
pip install streamlit pandas numpy plotly
```

## 📊 How to Use
1. **Login as Admin**: Enter the admin password in the sidebar.
2. **Upload Data**: Upload a CSV, Excel, or JSON file containing mindset tracking data.
3. **Track Progress**: Fill in the form to assess your mindset growth.
4. **View Data**: The table updates dynamically as you add entries.
5. **Analyze Trends**: View interactive charts that visualize mindset changes over time.
6. **Download Report**: Export your data as a CSV file for further analysis.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Feel free to submit pull requests or report issues. Contributions are welcome!

## 📧 Contact
For any questions or support, reach out to **ahchandio22@gmail.com** or create an issue on GitHub.

---
🚀 **Stay consistent and grow your mindset every day!**

