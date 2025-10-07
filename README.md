**Batch Payroll System
Overview

The Batch Payroll System automates the payroll process for different types of employees—hourly, salaried, and commissioned—by calculating payments, deductions, and handling paycheck distribution. This system ensures accurate and timely payroll management by integrating various use cases that interact with different actors.

Use Case Diagram

Actors

Hourly Employee: Submits time cards to log hours worked.

Commissioned Employee: Submits sales receipts for commission-based payments.

Salaried Employee: Receives fixed salary payments.

Payroll Administrator: Initiates the daily payroll process.

Union: Provides charges or dues applicable to employees.

Paymaster: Responsible for paycheck distribution and processing.

Use Cases

Submit Time Card: Hourly employees submit their work hours.

Submit Sales Receipt: Commissioned employees submit their sales information.

Run Daily Payroll Process: Payroll administrator triggers the payroll run.

Process Hourly Pay: Calculates pay for hourly employees based on submitted time cards and overtime.

Process Commission Pay: Calculates pay based on commission for sales.

Process Salary Pay: Processes fixed salary payments for salaried employees.

Calculate Overtime: Extended task used during hourly pay calculations to add overtime.

Apply Deductions: Deducts union dues or other charges from pay.

Mail Paycheck: Sends the paycheck to the employee by mail.

Process Direct Deposit: Deposits salary directly into employees' bank accounts.

Hold Paycheck for Pickup: Allows employees to pick up their paychecks in person.

Relationships

The Payroll Administrator initiates the Run Daily Payroll Process, which includes all payment processing.

The payment process for hourly, commissioned, and salaried employees includes calculating pay, applying deductions, and handling paycheck distribution.

Calculate Overtime extends the hourly pay process, as it is applicable only when overtime is worked.

The Union actor provides deductions that apply during the payroll process.

The Paymaster manages the paycheck distribution either by mailing, direct deposit, or holding for pickup.

Purpose

This diagram models the key processes involved in batch payroll management, ensuring all types of employees are paid accurately while considering deductions and different payment methods. It highlights the interaction between actors and system functions, ensuring smooth payroll operations.**
