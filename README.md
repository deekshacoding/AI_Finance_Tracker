# 📊 AI Finance Tracker

An intelligent **AI-powered Finance Tracker** built with **Python, Streamlit, Groq API, Pandas, and Data Analysis libraries**. This application allows users to upload **CSV** and **Excel** financial files and receive instant AI-driven insights, spending analysis, trend detection, and financial summaries.

---

## 🚀 Features

### 📂 File Upload Support

* Upload CSV files (`.csv`)
* Upload Excel files (`.xlsx`, `.xls`)
* Automatic data validation and preprocessing

### 🤖 AI-Powered Financial Analysis

* AI-generated summaries of financial data
* Income vs Expense analysis
* Spending pattern detection
* Budget recommendations
* Savings insights
* Financial health evaluation

### 📈 Interactive Dashboard

* Expense category breakdown
* Monthly spending trends
* Income growth visualization
* Interactive charts and graphs
* KPI cards for quick insights

### 🔍 Smart Analytics

* Detect unusual transactions
* Identify high-spending categories
* Track recurring expenses
* Trend forecasting
* Data-driven recommendations

### ⚡ Fast & Responsive

* Built using Streamlit
* Real-time analysis
* User-friendly interface
* Lightweight and easy to deploy

---

## 🛠️ Tech Stack

| Technology | Purpose                    |
| ---------- | -------------------------- |
| Python     | Core Programming           |
| Streamlit  | Web Application Framework  |
| Groq API   | AI-Powered Insights        |
| Pandas     | Data Processing            |
| Plotly     | Interactive Visualizations |
| NumPy      | Numerical Computations     |
| OpenPyXL   | Excel File Handling        |

---

## 📸 Application Workflow

1. Upload a CSV or Excel file.
2. The application reads and cleans the dataset.
3. Financial metrics are calculated automatically.
4. Groq AI analyzes the financial data.
5. Insights, recommendations, and visualizations are generated.
6. Users receive actionable financial intelligence.

---

## 📁 Project Structure

```bash
Finance_tracker.py
README.md
requirements.txt
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/AI-Finance-Tracker.git
cd AI-Finance-Tracker
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure Groq API Key

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Or directly configure it inside the application:

```python
from groq import Groq

client = Groq(
    api_key="YOUR_GROQ_API_KEY"
)
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```bash
http://localhost:8501
```

---

## 📊 Supported Financial Data

Example columns:

| Date       | Category  | Description    | Amount |
| ---------- | --------- | -------------- | ------ |
| 2026-01-05 | Food      | Restaurant     | 450    |
| 2026-01-06 | Salary    | Monthly Salary | 50000  |
| 2026-01-07 | Transport | Cab Fare       | 300    |

The application works best when financial data contains:

* Date
* Transaction Description
* Category
* Amount

---

## 💡 Example AI Insights

* "Your highest spending category is Food, accounting for 32% of total expenses."
* "Transportation expenses increased by 18% compared to last month."
* "You could save approximately ₹5,000 monthly by reducing discretionary spending."
* "Your income-to-expense ratio indicates healthy financial management."

---

## 🔒 Privacy & Security

* Files are processed locally during the session.
* No financial data is permanently stored.
* API requests only use required summarized information.
* Users maintain complete control of their uploaded files.

---

## 🎯 Future Enhancements

* PDF bank statement support
* Multi-file comparison
* Financial forecasting
* Goal-based budgeting
* Investment portfolio analysis
* Export AI reports as PDF
* Multi-user authentication
* Cloud deployment

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.

---

### Built with ❤️ using Python, Streamlit, Groq AI, and Data Analytics.
