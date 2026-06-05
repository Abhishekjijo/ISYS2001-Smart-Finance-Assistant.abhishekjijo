# Developer Diary – Smart Finance Assistant

## Evidence Package 1 – Transaction Data Cleaning

### Context
I wanted to create a function that could load CSV transaction data and clean the Amount column for financial analysis.

### Reflection
AI assistance helped generate an initial implementation using Pandas. During development I encountered indentation and formatting issues which required debugging and testing. After making corrections, the function successfully loaded transaction data and converted financial values into numeric format.

---

## Evidence Package 2 – Spending Analysis

### Context
I wanted to calculate total spending and identify major spending categories from transaction data.

### Reflection
AI assistance suggested using Pandas filtering and grouping operations. This helped calculate total spending and category totals efficiently. Testing with sample transaction data confirmed that the calculations were producing reasonable results.

---

## Evidence Package 3 – Financial Recommendations

### Context
I wanted to generate simple financial recommendations based on spending behaviour.

### Reflection
AI assistance helped generate a recommendation function that identifies the highest spending category and provides budgeting advice. I tested the recommendations using sample data and confirmed that the output was clear and readable.

---

## Evidence Package 4 – Savings Calculator

### Context
I wanted to create a tool that estimates how long it will take a user to reach a savings goal.

### Reflection
AI assistance helped create the calculation logic and validation checks. Testing showed that the calculator produced sensible estimates for different savings scenarios.

---

## Evidence Package 5 – Gradio Interface Integration

### Context
I wanted to integrate the individual project components into a single user-friendly application.

### Reflection
AI assistance helped connect the data analysis functions, savings calculator, and chatbot into one interface. Testing confirmed that users could upload transaction data, calculate savings goals, and receive financial advice through a single application.

---

## Overall Reflection

This project helped me understand how Python, Pandas, Gradio, and AI-assisted development can be combined to solve a practical business problem. I learned how to process financial data, generate useful insights, build a simple user interface, and test different components of an application. AI was useful for generating initial code, explaining errors, and helping me debug problems, but I still needed to test, review, and modify the code to ensure it worked correctly.
