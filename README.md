# Developer-Portfolio-Gateway
**Author:** Clay Rasmussen 
**Course:** CIS352 – Intro to Enterprise Computing  
**Intro:** Welcome to my GitHub portfolio repository! I am currently
studying Computer Information Systems at Wayne State College. This repository 
serves as central directory for navigating my coursework.
---

## 📚 Table of Contents

| Project | Tech | Category |
|--------|------|---------|
| [CALC2000](#calc2000) | COBOL / JCL | Intro to Enterprise Computing |
| [UTIL2000](#util2000) | COBOL / JCL | Intro to Enterprise Computing |
| [RPT2000](#rpt2000) | COBOL / JCL | Intro to Enterprise Computing |
| [RPT3000](#rpt3000) | COBOL / JCL | Intro to Enterprise Computing |
| [RPT5000](#rpt5000) | COBOL / JCL | Intro to Enterprise Computing |
| [RPT6000](#rpt6000) | COBOL / JCL | Intro to Enterprise Computing |
| [SEQ3000](#seq3000) | COBOL / JCL | Intro to Enterprise Computing |
| [Weather Station](#weather-station) | Java | Programming Fundamentals II |
| [MathTutorV6](#mathtutorv6) | C++ | Programming Fundamentals I |

---

## CALC2000

### 📌 Summary
A COBOL batch program that calculates future investment values and demonstrates 
repeated value doubling through structured processing.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Arithmetic operations in COBOL
- Sequential execution of calculations
- Data handling in the Data Division
- Output formatting for financial results

### ⚙️ Features
- Calculates future value of an investment
- Demonstrates repeated doubling of values
- Outputs formatted results to the console

### 🚦 Status
✅ Completed

### 📷 Preview
![CALC2000 Output](assets/CALC2000.png)

### 🔗 Repository
[CALC2000](https://github.com/Clay-Rasmussen/COBOLCALC2000)

🔙 [Back to TOC](#-table-of-contents)
---

## UTIL2000

### 📌 Summary
A COBOL utility billing system that calculates and generates monthly bills for multiple customers based on their kilowatt-hour (kWh) usage.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Sequential file processing
- Arithmetic calculations for billing
- Conditional logic for rate calculations
- Data formatting for customer output
- Handling multiple customer records

### ⚙️ Features
- Processes customer electricity usage data
- Calculates monthly billing based on kWh consumption
- Generates formatted billing output
- Handles multiple customer records in a single run

### 🚦 Status
✅ Completed

### 📷 Preview
![UTIL2000 Output](assets/UTIL2000.png)

### 🔗 Repository
[UTIL2000](https://github.com/Clay-Rasmussen/CobolUtil2000)

🔙 [Back to TOC](#-table-of-contents)
---

## RPT2000

### 📌 Summary
An intermediate COBOL reporting program that processes customer financial records and generates a formatted Year-To-Date (YTD) Sales Report. This version introduces comparative analytics by calculating differences between current and previous year sales.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Sequential file processing
- Arithmetic operations using `COMPUTE` and `SUBTRACT`
- Percentage calculations with zero-division protection
- Numeric-edited formatting for financial data
- Integration with JCL for file handling

### ⚙️ Features
- Reads customer data from `CUSTMAST`
- Calculates YTD change amount and percentage
- Prevents divide-by-zero errors in calculations
- Generates formatted multi-column reports
- Produces overall company totals

### 🚦 Status
✅ Completed

### 📷 Preview
![RPT2000 Output](assets/RPT2000.png)

### 🔗 Repository
[RPT2000](https://github.com/Clay-Rasmussen/RPT2000)

🔙 [Back to TOC](#-table-of-contents)
---

## RPT3000

### 📌 Summary
An advanced COBOL reporting tool that processes customer financial records from a master file and generates a formatted multi-page Year-To-Date (YTD) Sales Report. The program includes automated branch break processing, customer-level calculations, and professional report pagination.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Sequential file processing
- Control break logic
- First-record switch handling
- Running totals and grand totals
- Financial calculations and percentage changes
- Structured report formatting
- Multi-page output pagination

### ⚙️ Features
- Reads customer financial data from `CUSTMAST`
- Detects branch changes automatically
- Prints branch-level subtotal reports
- Calculates YTD change amount and percentage
- Generates company-wide grand totals
- Adds formatted headers, timestamps, and separators

### 🚦 Status
✅ Completed

### 📷 Preview
![RPT3000 Output](assets/RPT3000.png)

### 🔗 Repository
[RPT3000](https://github.com/Clay-Rasmussen/RPT3000)

🔙 [Back to TOC](#-table-of-contents)
---

## RPT5000

### 📌 Summary
An advanced COBOL reporting system that processes customer sales data and generates a multi-level, formatted Year-To-Date (YTD) Sales Report. This version introduces two-level control break processing, enhanced decision logic using EVALUATE, and professional report pagination.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Two-level control break processing (branch & sales representative)
- EVALUATE statement for structured decision-making
- 88-level condition names for readable logic control
- Sequential file processing
- Running totals, subtotals, and grand totals
- Error-handled arithmetic using `COMPUTE`, `ROUNDED`, and `ON SIZE ERROR`
- Report pagination and formatted output

### ⚙️ Features
- Processes structured customer sales data
- Generates nested subtotal reports by branch and sales representative
- Calculates YTD change amount and percentage
- Uses EVALUATE to simplify complex logic
- Produces clean, multi-page formatted reports with headers and spacing

### 🚦 Status
✅ Completed

### 📷 Preview
![RPT5000 Output](assets/RPT5000.png)

### 🔗 Repository
[RPT5000](https://github.com/Clay-Rasmussen/RPT5000)

🔙 [Back to TOC](#-table-of-contents)
---

## RPT6000

### 📌 Summary
An advanced COBOL program focused on data formatting, table processing, and modular design. This project integrates file-driven tables, indexed lookups, and reusable copybooks to enhance flexibility, scalability, and report accuracy.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- REDEFINES and edited picture clauses for formatted output
- Packed decimal (COMP-3) data handling
- Table processing using OCCURS and INDEXED BY
- SEARCH statement for table lookups
- Sequential file processing with EOF control
- Copybooks (COPYLIB) for modular design
- Dynamic table loading from input files

### ⚙️ Features
- Formats numeric data with currency, commas, and special values (e.g., "N/A", "OVRFLW")
- Loads and processes table data from external files
- Performs indexed lookups for sales representative information
- Uses modular copybooks to simplify and reuse data structures
- Produces structured and readable report output

### 🚦 Status
✅ Completed

### 📷 Preview
![RPT6000 Output](assets/RPT6000.png)

### 🔗 Repository
[RPT6000](https://github.com/Clay-Rasmussen/RPT6000)

🔙 [Back to TOC](#-table-of-contents)
---

## SEQ3000

### 📌 Summary
A COBOL file maintenance program that processes employee master records alongside a transaction file to perform additions, deletions, and updates. The program uses a balanced-line algorithm to ensure accurate record comparison and generates both an updated master file and an error report.

### 🧰 Tech Stack
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Sequential file processing
- Balanced-line algorithm for file comparison
- Multi-file input/output handling
- Data validation and error handling
- File status checking
- Structured program flow for record maintenance

### ⚙️ Features
- Processes employee master and transaction files simultaneously
- Performs add, delete, and update operations
- Generates updated master file
- Produces error file for invalid transactions
- Handles real-world HR record scenarios

### 🚦 Status
✅ Completed

### 📷 Preview
![SEQ3000 Output](assets/SEQ3000.png)

### 🔗 Repository
[SEQ3000](https://github.com/Clay-Rasmussen/SEQ3000)

🔙 [Back to TOC](#-table-of-contents)
---

## Weather Station

### 📌 Summary
A Java application that displays real-time weather station data, including temperature, humidity, and wind speed. This project demonstrates object-oriented programming concepts and UI/data handling using instructor-provided starter code.

### 🧰 Tech Stack
* ![Amazon Corretto](https://img.shields.io/badge/Amazon_Corretto-blue?style=for-the-badge&logo=amazon-aws&logoColor=white)
* ![Java Version](https://img.shields.io/badge/Java-17-blue)
* ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Object-oriented programming (classes and objects)
- Data representation and display
- Event-driven or input-based updates (depending on implementation)
- Working with pre-built starter code

### ⚙️ Features
- Displays temperature, humidity, and wind speed
- Processes and presents weather data in a user-friendly format
- Built using structured Java application design

### 🚦 Status
✅ Completed

### 🔗 Repository
[Weather Station](https://github.com/Clay-Rasmussen/Semester2JavaFinal)

🔙 [Back to TOC](#-table-of-contents)
---

## MathTutorV6

### 📌 Summary
A C++ console-based math tutor application that generates random arithmetic problems and adjusts difficulty based on user performance. The program tracks attempts, provides feedback, and summarizes results to enhance learning.

### 🧰 Tech Stack
* ![C++](https://img.shields.io/badge/C++-blue?style=for-the-badge&logo=c%2B%2B&logoColor=white)
* ![CLion](https://img.shields.io/badge/CLion-000000?style=for-the-badge&logo=clion&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

### 🧠 Key Concepts
- Random number generation
- Conditional logic and loops
- Input validation
- Functions and modular design
- Use of vectors for storing results
- Enum usage for math operation types

### ⚙️ Features
- Generates random math problems (addition, subtraction, etc.)
- Adjusts difficulty level based on performance
- Tracks user attempts and correctness
- Provides feedback after each question
- Displays a summary report at the end

### 🚦 Status
✅ Completed

### 🔗 Repository
[MathTutorV6](https://github.com/Clay-Rasmussen/MathTutorV6)

🔙 [Back to TOC](#-table-of-contents)
---
