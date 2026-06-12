<<<<<<< HEAD
💰 Personal Finance Tracker (Flask + SQLite)

A modern, full-stack Personal Finance Tracker Web Application built using Flask, SQLite, and a stylish frontend. This app helps users manage expenses, track savings, and gain intelligent financial insights.

🚀 Features
🔐 User Authentication
Secure login & registration system
Password hashing using Flask security tools
User-specific data isolation (user_id)

💸 Expense Management (CRUD)
Add, view, and delete expenses
Categorized expense tracking:
Grocery
Rent
Food / Dining
Gold / Assets
Insurance
Cash Savings
Medical
Others

📊 Financial Dashboard
Monthly overview:
Salary 💼
Total Spending 💸
Investments 📈
Savings 💰
Recent transactions display
Category-wise expense summary using:
SUM()
GROUP BY

📈 Interactive Visualization
Donut-style circular chart for:
Spending vs Investing vs Remaining balance
Fully responsive and dynamic UI

🧠 Smart Financial Advice
Alerts if:
Spending exceeds salary
Savings drop below 20%
Positive reinforcement for:
Investments (Gold, Assets)
Medical expenses

📅 Monthly Tracking Logic
Filters expenses using SQLite:
strftime('%Y-%m', date_created)
Ensures only current month data is analyzed

📁 CSV Auto Export
Every transaction is automatically saved to:
expenses.csv
Acts as a real-time backup

💱 Currency Support
Fully adapted for Indian Rupees (₹)

🎨 UI/UX Design
Glassmorphism styling ✨
Smooth animations
Gradient themes
Clean and modern layout

🛠️ Tech Stack
Backend: Flask
Database: SQLite
Frontend: HTML, CSS
Language: Python

📂 Project Structure
project/
│
├── app.py
├── database.db
├── expenses.csv
│
├── templates/
│   ├── index.html
│   └── add.html
│
├── static/
│   └── style.css
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/finance-tracker.git
cd finance-tracker

2️⃣ Create Virtual Environment (Optional)
python -m venv venv
venv\Scripts\activate   # Windows

3️⃣ Install Dependencies
pip install flask

4️⃣ Run Application
python app.py

5️⃣ Open in Browser
http://localhost:5000

🧪 Validation

✔ Flask server successfully initialized
✔ Database auto-created (database.db)
✔ Web app running on local server
✔ CRUD operations verified
✔ Monthly analytics working correctly

🔒 Security Notes
Passwords are securely hashed
User data is isolated
Avoid pushing .env or sensitive data

📌 Future Improvements
Edit/update expense feature
Graphs using Chart.js
Mobile responsiveness improvements
Deployment (Render / Railway)

👨‍💻 Author

Raman Singh

⭐ Support

If you like this project:

Star ⭐ the repo
Fork 🍴 and improve it
Share 💡 ideas
=======
# Personal-Finance-Tracker-Flask-SQLite-
A modern financial tracking web app using Flask, SQLite, and dynamic UI that enables users to manage expenses, analyze spending patterns, track savings, and receive intelligent financial advice with secure user authentication.
>>>>>>> c8ebb760f87b4b2bf5dbe281ca32d2fb2df75c0f
