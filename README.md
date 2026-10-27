# Personal Expense Tracker

## 1. Project Overview

**Personal Expense Tracker** is a simple Java-based desktop application designed to help users manage and track their daily expenses. Users can add, update, delete, search, and categorize expenses. The application also calculates total expenses and generates basic expense summaries.

The main goal of this project is to develop a user-friendly expense management system while applying software engineering principles, object-oriented programming, and software design techniques.

## 2. Project Objectives

The main objectives of this project are:

- To record daily personal expenses.
- To organize expenses into different categories.
- To add, update, and delete expense records.
- To search and filter expenses.
- To calculate total expenses.
- To generate basic expense reports.
- To apply software engineering concepts throughout the development process.

## 3. Key Features

- **Add Expense:** Record an expense with its title, amount, category, date, and description.
- **Update Expense:** Modify existing expense information.
- **Delete Expense:** Remove an expense record.
- **Search Expense:** Find expenses using relevant information.
- **Filter by Category:** View expenses belonging to a specific category.
- **Calculate Total:** Calculate the total amount of recorded expenses.
- **Expense Summary:** View basic expense reports.
- **Local Data Storage:** Store expense records in a CSV file.

## 4. Technologies Used

| Component | Technology |
|---|---|
| Programming Language | Java |
| User Interface | Java Swing |
| Programming Paradigm | Object-Oriented Programming (OOP) |
| Data Storage | CSV File |
| Software Process Model | Incremental Model |
| Documentation | Markdown and LaTeX |
| Diagram Tools | PlantUML and Mermaid |

## 5. Project Structure

```text
Personal-Expense-Tracker/
│
├── README.md
│
├── src/
│   ├── Main.java
│   ├── Category.java
│   ├── Expense.java
│   ├── ExpenseManager.java
│   ├── ExpenseReport.java
│   ├── ExpenseStorage.java
│   ├── ExpenseController.java
│   └── ExpenseFrame.java
│
├── docs/
│   ├── Project_Proposal.md
│   ├── Project_Report.tex
│   └── Test_Cases.md
│
└── diagrams/
    ├── DFD_Level0.mmd
    ├── DFD_Level1.mmd
    ├── Use_Case.puml
    ├── Activity.puml
    ├── ERD.puml
    ├── Class_Diagram.puml
    ├── Object_Diagram.puml
    └── Gantt_Chart.mmd
```

## 6. System Classes

The project uses the following Java classes:

| Class | Responsibility |
|---|---|
| `Main` | Starts the application. |
| `Category` | Represents expense categories. |
| `Expense` | Represents an individual expense record. |
| `ExpenseManager` | Manages expense operations. |
| `ExpenseReport` | Calculates totals and generates summaries. |
| `ExpenseStorage` | Saves and loads expense records. |
| `ExpenseController` | Connects application logic with the interface. |
| `ExpenseFrame` | Provides the graphical user interface. |

These classes demonstrate the use of object-oriented programming principles, including classes, objects, encapsulation, and separation of responsibilities.

## 7. Software Development Process

The project follows the **Incremental Software Development Model**. The application is developed in small, manageable increments.

The planned development phases are:

1. Requirement Analysis
2. System Design
3. Implementation of Core Features
4. Graphical User Interface Development
5. Integration and Testing
6. Documentation and Final Submission

## 8. System Diagrams

The `diagrams/` directory contains the following design diagrams:

- Data Flow Diagram (DFD) — Level 0
- Data Flow Diagram (DFD) — Level 1
- Use Case Diagram
- Activity Diagram
- Entity Relationship Diagram (ERD)
- Class Diagram
- Object Diagram
- Gantt Chart

These diagrams describe the system's requirements, structure, workflow, data relationships, and project schedule.

## 9. How to Run the Project

### Requirements

- Java Development Kit (JDK) installed on your computer.
- A Java-compatible IDE, such as IntelliJ IDEA, Eclipse, or VS Code, or a terminal.

### Steps

**Step 1: Clone the repository**

```bash
git clone <your-repository-url>
```

**Step 2: Open the project**

Open the project folder in your preferred Java IDE.

**Step 3: Compile the Java files**

Open a terminal in the project directory and run:

```bash
javac -d out src/*.java
```

**Step 4: Run the application**

```bash
java -cp out Main
```

**Note:** Run these commands from the project root directory. If your IDE uses a different source-folder configuration, adjust the commands accordingly.

## 10. Data Storage

The application stores expense records locally in a CSV file named `expenses.csv`.

The file is used to save expense information so that records can be loaded again when the application starts.

The ERD represents the logical data model for the project. The current implementation uses CSV-based storage rather than a relational database.

## 11. Testing

The application should be tested to verify that its main features work correctly.

Important test cases include:

- Adding an expense with valid information.
- Updating an existing expense.
- Deleting an expense.
- Searching for an expense.
- Filtering expenses by category.
- Calculating total expenses.
- Saving and loading expense records.
- Handling invalid or missing input.

Detailed test cases are provided in `docs/Test_Cases.md`.

## 12. Expected Outcomes

After completing the project, the application is expected to:

- Provide a simple interface for managing personal expenses.
- Store and retrieve expense records locally.
- Perform basic expense calculations.
- Demonstrate the application of Java and OOP concepts.
- Demonstrate the use of software engineering models, diagrams, scheduling, and testing.

## 13. Future Improvements

Possible future enhancements include:

- Database integration using MySQL or SQLite.
- Monthly and yearly expense reports.
- Charts and graphical expense analysis.
- User authentication.
- Budget planning and spending alerts.
- Exporting reports to PDF or Excel.

## 14. Project Information

**Project Name:** Personal Expense Tracker  
**Project Type:** Individual Software Engineering Project  
**Programming Language:** Java  
**User Interface:** Java Swing  
**Development Model:** Incremental Model  
**Data Storage:** CSV File  

---

*This project is developed for academic purposes to demonstrate software engineering concepts and object-oriented programming in Java.*
