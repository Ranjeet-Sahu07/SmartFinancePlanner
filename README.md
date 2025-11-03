# 🏦 SmartFinancePlanner

**A Modern JavaFX-Based Personal Finance Management Desktop Application**

---

## 📋 Project Overview

SmartFinancePlanner is a comprehensive desktop application built with JavaFX that empowers users to take control of their personal finances. With an intuitive dashboard-style interface, users can calculate EMIs, plan SIPs, estimate Fixed Deposit returns, track expenses, and visualize their financial data through interactive charts.

---

## ✨ Key Features

### 🚀 **Active Features (Fully Functional)**

1. **EMI Calculator**
   - Calculate Equated Monthly Installments for loans
   - Input: Principal amount, interest rate, tenure
   - Output: Monthly EMI, total interest payable, total payment

2. **SIP Calculator**
   - Plan your Systematic Investment Plan returns
   - Input: Monthly investment, expected return rate, investment period
   - Output: Maturity amount with projected growth

3. **Fixed Deposit Calculator**
   - Estimate FD maturity amounts
   - Input: Principal, interest rate, time period, compounding frequency
   - Output: Maturity value with interest breakdown

4. **Expense Tracker**
   - Add and categorize daily expenses
   - View comprehensive monthly reports
   - Export expense data to CSV format
   - Visual expense distribution analysis

5. **Dashboard**
   - Summary cards displaying key financial metrics
   - Interactive PieChart for expense distribution
   - LineChart showing investment growth trends
   - Real-time updates of financial data

### 🔮 **Coming Soon Features**

- 🤖 AI Financial Advisor
- 📈 Real-Time Investment Tracker
- 📱 Mobile App Companion
- 🔔 Smart Notifications
- 💸 Tax & Inflation Tools
- 🪙 Crypto Tracker
- ☁️ Cloud Sync
- 📊 Financial Health Score
- 💳 Loan Comparison Tool
- 🌍 ESG / Green Investment Insights

---

## 🛠️ Tech Stack

- **Language:** Java 17+
- **UI Framework:** JavaFX with FXML and CSS
- **Build Tool:** Apache Maven
- **Charts Library:** JavaFX Charts (PieChart, BarChart, LineChart)
- **Optional UI Enhancement:** JFoenix (Material Design)
- **IDE Support:** IntelliJ IDEA, Eclipse, VS Code

---

## 📁 Folder Structure

```
SmartFinancePlanner/
├── src/
│   ├── main/java/com/financeplanner/
│   │   ├── Main.java
│   │   ├── controllers/
│   │   │   ├── DashboardController.java
│   │   │   ├── CalculatorController.java
│   │   │   ├── ExpenseController.java
│   │   │   └── ComingSoonController.java
│   │   ├── models/
│   │   └── utils/
│   └── main/resources/
│       ├── ui/
│       │   ├── dashboard.fxml
│       │   ├── calculators.fxml
│       │   ├── expenses.fxml
│       │   └── comingsoon.fxml
│       ├── styles/style.css
│       └── images/logo.png
├── pom.xml
├── README.md
├── tools_and_steps.txt
└── ui_design_plan.txt
```

---

## 🎨 UI Design Highlights

### Color Palette
- **Primary:** #2E86DE (Professional Blue)
- **Accent:** #00B894 (Success Green)
- **Background:** #F8F9FA (Clean Light)

### Design Elements
- **Typography:** Poppins / Roboto fonts
- **Buttons:** Rounded corners with hover animations and shadow effects
- **Charts:** Pastel color themes for better readability
- **Layout:** Modern sidebar navigation with responsive content area

### UI Components
- Header bar with app title, date/time display, and profile icon
- Sidebar navigation: Dashboard | Calculators | Expenses | Reports | Coming Soon
- Interactive summary cards with live data
- Tabbed calculator interface for easy switching
- TableView for expense management
- Modal dialogs for "Coming Soon" features

---

## 🚀 Setup & Installation

### Prerequisites
- Java 17 or higher installed
- Apache Maven installed
- Git installed

### Steps to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Ranjeet-Sahu07/SmartFinancePlanner.git
   ```

2. **Navigate to Project Directory**
   ```bash
   cd SmartFinancePlanner
   ```

3. **Build the Project**
   ```bash
   mvn clean compile
   ```

4. **Run the Application**
   ```bash
   mvn exec:java
   ```

---

## 📸 Screenshots

*Screenshots will be added as features are implemented*

- Dashboard Overview
- EMI Calculator
- SIP Calculator
- FD Calculator
- Expense Tracker
- Coming Soon Features

---

## 📚 Documentation

- **tools_and_steps.txt** - Detailed setup instructions, dependencies, and build commands
- **ui_design_plan.txt** - Comprehensive UI structure, alignment guidelines, and design specifications

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

---

## 📄 License

This project is open source and available for educational and personal use.

---

## 👨‍💻 Author

**Ranjeet Sahu**

---

## 🌟 Roadmap

- [x] Project initialization
- [x] Basic folder structure
- [ ] Implement EMI Calculator
- [ ] Implement SIP Calculator
- [ ] Implement FD Calculator
- [ ] Build Expense Tracker
- [ ] Create Dashboard with charts
- [ ] Add Coming Soon features toggle
- [ ] Implement CSV export functionality
- [ ] Add comprehensive testing
- [ ] Deploy and document

---

**Version:** 1.0.0-SNAPSHOT  
**Last Updated:** November 2025
