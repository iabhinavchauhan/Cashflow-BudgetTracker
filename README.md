# Cash Flow Budget Tracker

A modern and easy-to-use **Cash Flow Budget Tracker** that helps users manage their salary, track daily expenses, monitor their remaining balance, and maintain better control over their personal finances.

**Live Demo:** https://cashflowbudgettracker.netlify.app/


## Overview

**Cash Flow Budget Tracker** is a lightweight personal finance management web application designed to make expense tracking simple and intuitive.

The application allows users to:

* Enter their total salary/income
* Add multiple expenses
* Specify expense names and amounts
* Automatically track the remaining balance
* Monitor how much of their budget is left
* Get a warning when the remaining budget becomes critically low
* Switch between light and dark themes
* Download a PDF report of their financial information

The interface focuses on simplicity, making it suitable for students, employees, freelancers, and anyone who wants a quick overview of their monthly cash flow.

---

## Features

### Salary Management

Enter your total salary or available income and use it as the starting point for your budget calculation.

### Expense Tracking

Add individual expenses by entering:

* Expense Name
* Expense Amount

Multiple expenses can be tracked to get a clearer picture of spending.

### Automatic Balance Calculation

The application automatically calculates the remaining balance based on:

```text
Remaining Balance = Total Salary - Total Expenses
```

This allows users to instantly understand how much money is still available.

### Low Budget Alert

The application provides a **Budget Low** warning when the remaining budget falls below 10%.

### Dark / Light Mode

A theme toggle is available to switch between light and dark viewing modes, making the application more comfortable to use in different environments.

### PDF Report

Users can generate and download a PDF report containing their budget information.

The report can be useful for:

* Personal financial records
* Monthly expense tracking
* Budget reviews
* Saving financial information for later reference

### Responsive Interface

The application is designed to provide a clean experience across:

* Desktop
* Laptop
* Mobile
* Tablet

---

## 🖥️ Application Interface

The main interface contains:

1. **Cash Flow Budget Tracker Header**
2. **Theme Toggle**
3. **Total Salary Input**
4. **Expense Name Input**
5. **Expense Amount Input**
6. **Add Expense Button**
7. **Remaining Balance Display**
8. **Budget Warning**
9. **PDF Report Download Button**

---

## 🧮 How It Works

The application follows a simple budgeting workflow.

### Step 1 — Enter Salary

Enter your total salary or available income.

Example:

```text
Salary = $5,000
```

### Step 2 — Add Expenses

Add individual expenses.

Example:

```text
Rent       = $1,500
Food       = $500
Transport  = $300
Shopping   = $400
```

### Step 3 — Calculate Remaining Balance

The application calculates the total expenses and subtracts them from the salary.

```text
Total Salary = $5,000

Total Expenses = $2,700

Remaining Balance = $5,000 - $2,700

Remaining Balance = $2,300
```

### Step 4 — Monitor Budget

The remaining balance is continuously updated as expenses are added.

If the remaining budget becomes less than 10% of the original salary, the application displays a low-budget warning.

### Step 5 — Generate Report

Users can download their budget information as a PDF report for future reference.

---

## 📊 Budget Calculation

The core calculation can be represented as:

```text
Total Expenses = Expense 1 + Expense 2 + Expense 3 + ... + Expense N
```

Then:

```text
Remaining Balance = Total Salary - Total Expenses
```

The remaining percentage can be represented as:

```text
Remaining Percentage =
(Remaining Balance / Total Salary) × 100
```

The low-budget condition is:

```text
If Remaining Percentage < 10%

Show:
⚠️ Budget Low!
```

---

## 🛠️ Tech Stack

The project is built using modern web technologies.

### Frontend

* HTML5
* CSS3
* JavaScript
* Responsive Web Design

### UI

* Modern responsive interface
* Light/Dark theme
* Form-based expense management
* User-friendly controls

### Reporting

* PDF report generation

### Deployment

* Netlify

---

## 📁 Project Structure

A typical project structure can be organized as:

```text
cash-flow-budget-tracker/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── assets/
│   ├── images/
│   └── icons/
│
├── README.md
│
└── LICENSE
```

> The exact structure may vary depending on the source implementation.

---

## 🚀 Getting Started

To run the project locally, follow these steps.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cash-flow-budget-tracker.git
```

### 2. Navigate to the Project

```bash
cd cash-flow-budget-tracker
```

### 3. Open the Project

If it is a static HTML/CSS/JavaScript project, you can simply open:

```text
index.html
```

in your browser.

Alternatively, you can use the **Live Server** extension in VS Code.

---

## 💻 Running with VS Code

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. The application will open in your browser.

---

## 🌐 Live Demo

Try the application here:

**https://cashflowbudgettracker.netlify.app/**

---

## 🎯 Use Cases

This application can be useful for:

### 👨‍🎓 Students

Track monthly pocket money and daily spending.

### 👨‍💻 Professionals

Monitor salary and recurring monthly expenses.

### 🧑‍💼 Freelancers

Keep track of income and project-related spending.

### 🏠 Personal Finance

Maintain a simple overview of available cash.

### 📅 Monthly Budget Planning

Compare income against planned expenses.

---

## 🔮 Future Improvements

The project can be extended with several advanced features.

### 📈 Expense Analytics

Add charts and graphs to visualize spending patterns.

Possible categories:

* Food
* Rent
* Transportation
* Shopping
* Entertainment
* Bills
* Healthcare
* Other

### 💾 Local Storage

Store budget data in the browser so users don't lose their information after refreshing the page.

### 📅 Monthly Budget History

Allow users to maintain budgets for different months.

Example:

```text
January 2026
February 2026
March 2026
April 2026
```

### 🔐 User Authentication

Add authentication so users can securely save their financial information.

### ☁️ Cloud Database

A backend could be added to store user budgets securely in the cloud.

Possible technologies:

```text
Node.js
Express.js
MongoDB
JWT
```

### 📊 Advanced Dashboard

A future dashboard could display:

```text
Total Income
Total Expenses
Remaining Balance
Savings
Highest Expense
Monthly Spending
Expense Categories
```

### 🔔 Budget Notifications

Users could receive notifications when:

* Budget reaches 50%
* Budget reaches 25%
* Budget reaches 10%
* Budget is exceeded

### 📱 PWA Support

The application could be converted into a Progressive Web App so users can install it on mobile devices.

---

## 🔒 Privacy

The application is intended for personal budgeting and expense tracking.

Users should avoid entering highly sensitive financial information such as:

* Bank account passwords
* Card PINs
* OTPs
* Banking credentials

---

## ⚡ Performance

The project is designed to provide:

* Fast loading
* Lightweight interaction
* Simple navigation
* Responsive layouts
---
## 🎨 UI/UX Goals

The application follows several usability principles:

* Simple navigation
* Clear financial information
* Easily readable balance information
* Responsive design
* Accessible controls
* Light/Dark theme support

---

## 🧪 Example

Suppose a user enters:

```text
Total Salary: $10,000
```

Then adds:

```text
Rent:        $3,000
Food:        $1,000
Transport:   $500
Shopping:    $750
Bills:       $1,000
```

The calculation becomes:

```text
Total Salary
= $10,000

Total Expenses
= $6,250

Remaining Balance
= $3,750
```

Therefore:

```text
Remaining Percentage
= ($3,750 / $10,000) × 100

= 37.5%
```

Since 37.5% is greater than 10%, the budget is not considered critically low.

---

## 📸 Screenshots

You can add screenshots of your application here:

```md
![Dashboard](./screenshots/dashboard.png)

![Dark Mode](./screenshots/dark-mode.png)

![Budget Report](./screenshots/report.png)
```

Recommended screenshots:

* Main dashboard
* Salary input
* Expense tracking
* Low budget warning
* Dark mode
* Generated PDF report

---

## 📌 Project Highlights

* 💰 Personal budget management
* 🧾 Expense tracking
* 📊 Automatic calculations
* ⚠️ Low-budget detection
* 🌙 Dark/Light mode
* 📄 PDF report generation
* 📱 Responsive design
* ⚡ Lightweight application
* 🎨 Clean modern UI
* 🌐 Deployed on Netlify

---

## 🧠 What I Learned

Building this project helped strengthen practical development skills including:

* DOM manipulation
* JavaScript event handling
* Form handling
* Dynamic UI updates
* Mathematical calculations
* State management concepts
* Responsive CSS
* Theme switching
* Client-side data processing
* PDF generation
* User experience design
* Deployment using Netlify

---

## 🚀 Deployment

The project is deployed using **Netlify**.

Live application:

https://cashflowbudgettracker.netlify.app/

For deployment, the project can also be hosted using platforms such as:

* Netlify
* Vercel
* GitHub Pages

---

## 🤝 Contributing

Contributions are welcome!

If you want to improve this project:

### 1. Fork the repository

```bash
git fork
```

### 2. Clone your fork

```bash
git clone https://github.com/your-username/cash-flow-budget-tracker.git
```

### 3. Create a new branch

```bash
git checkout -b feature/improvement
```

### 4. Make your changes

Improve the UI, functionality, performance, or documentation.

### 5. Commit your changes

```bash
git add .
git commit -m "Add new budget feature"
```

### 6. Push your branch

```bash
git push origin feature/improvement
```

### 7. Create a Pull Request

Submit your changes for review.

---

## 📄 License

This project is available for educational and personal use.

You can add an MIT License to the repository if you want to allow others to freely use and modify the project.

---

## 👨‍💻 Author

### Abhinav Chauhan

**Frontend / MERN Stack Developer**

I build modern, responsive and user-focused web applications using technologies such as React.js, JavaScript, Tailwind CSS, Node.js, Express.js and MongoDB.

### 🔗 Connect With Me

* 💼 LinkedIn: https://linkedin.com/in/iabhinavchauhan
* 🐙 GitHub: https://github.com/iabhinavchauhan
* 📧 Email: [iabhinavchauhan.ac@gmail.com](mailto:iabhinavchauhan.ac@gmail.com)

---

## ⭐ Support

If you found this project useful or interesting:

⭐ **Star this repository**

🍴 **Fork the project**

📢 **Share it with other developers**

💡 **Suggest improvements**

---

## 📌 Project Status

```text
🟢 Active
```

The project is currently available online and can be further extended with advanced budgeting, analytics, authentication, database integration, and financial insights.

---

## 💰 Cash Flow Budget Tracker

> **Track your income. Manage your expenses. Understand your cash flow.**

**Live Demo:**
https://cashflowbudgettracker.netlify.app/

⭐ If you like the project, don't forget to **star the repository!**
