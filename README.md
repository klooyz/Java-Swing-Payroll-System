# Salary Calculator (Liquidación de Sueldo)

A Java Swing GUI application developed for the Object-Oriented Programming (POO) laboratory. This tool calculates an employee's net pay (Sueldo Líquido) based on their base salary, allowances, and legal deductions in Chile.

## Features

* **GUI:** User-friendly interface built with Java Swing.
* **Automatic Calculations:**
    * **Production Bonus:** Automatically calculates 10% of the base salary.
    * **Legal Deductions:** Calculates Health (Salud) and Pension (AFP) rates automatically.
* **Health System (Salud):**
    * Supports **FONASA** (Fixed 7%).
    * Supports **ISAPRE** (Variable percentage input).
* **Pension Fund (AFP):**
    * Dynamic rates based on the selected AFP (Habitat, Cuprum, Provida, etc.).
* **Result Table:** Displays a summary of earnings and deductions in a `JTable`.

## Technologies Used

* **Language:** Java (JDK 8+)
* **Framework:** Swing (JFrame, JTable, JComboBox, JTextField)
* **IDE:** NetBeans

## How to Run

1.  Clone this repository.
2.  Open the project in **NetBeans IDE**.
3.  Run the `Calculadora.java` file.
4.  Enter the Employee Name and Base Salary.
5.  Click **CALCULATE** to see the results.

---
*Developed for the OOP Laboratory - 2025*
