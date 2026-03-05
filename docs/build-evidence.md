# Build Evidence

This section provides supporting evidence for how the Penny Smart prototype was built and validated.

---

# 1. Working Demo

A functional prototype of the Penny Smart application can be accessed below:

https://stop-stain-04589424.figma.site

The prototype demonstrates the core user journey including:

- User onboarding
- Dashboard overview
- Savings goal creation
- Budget management
- Transaction tracking

---

# 2. Architecture Overview

Since this project is currently a prototype, the system architecture is designed as a **frontend-focused application with mock data storage**.

Simple Architecture Flow:

User → Web Interface → Application Logic → Local Data Storage

Explanation:

- The user interacts with the application interface.
- Application logic processes transactions, budgets, and savings goals.
- Data is stored locally (mock storage) to simulate persistence.
- The dashboard visualizes the financial data.

Architecture Components:

Frontend Layer
- User interface
- Dashboard
- Financial visualization

Application Logic Layer
- Transaction handling
- Budget calculations
- Savings tracking

Data Layer
- Mock data storage
- Simulated financial records

---

# 3. API / Data Approach

Since the application is currently a prototype, it uses **mock data rather than a live backend API**.

Data handled in the application includes:

- User profile data
- Wallet balance
- Transaction records
- Budget categories
- Savings goals

Example Data Model:

User
- user_id
- name
- email

Transaction
- transaction_id
- type (income / expense)
- category
- amount
- date

SavingsGoal
- goal_id
- goal_name
- target_amount
- current_amount
- deadline

In a production environment, these data models would be managed through a backend API connected to a database.

---

# 4. Testing Evidence

Basic testing was conducted to ensure that the prototype supports the intended user flows.

## Test Plan

Key scenarios tested:

1. User onboarding flow
2. Creating a savings goal
3. Adding a transaction
4. Viewing dashboard updates
5. Budget tracking functionality

---

## Test Results

| Test Scenario | Expected Result | Outcome |
|---------------|----------------|--------|
| User onboarding | User successfully enters the app | Passed |
| Add transaction | Transaction appears in history | Passed |
| Create savings goal | Goal appears in savings section | Passed |
| Budget tracking | Spending reflects in budget | Passed |
| Dashboard view | Financial summary updates | Passed |

---

# 5. Known Limitations / Technical Debt

As this project is currently an MVP prototype, several limitations exist.

Current Limitations:

- No backend integration
- Data persistence is simulated
- No real bank account integration
- Limited financial analytics
- No user authentication security layer

Future Improvements:

- Backend API integration
- Secure authentication system
- Real-time financial analytics
- Bank account connectivity
- Advanced budgeting insights

---

# Summary

The Penny Smart prototype demonstrates the core financial management experience through a functional prototype, mock data architecture, and validated user flows.

Future development phases will focus on expanding backend infrastructure, improving financial insights, and integrating external financial services.
