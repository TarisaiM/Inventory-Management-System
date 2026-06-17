
# Inventory Management System

## Case Study / Problem

A company is growing quickly, from 10 employees to 100 employees across different offices and labs. It uses various types of equipment such as smart devices, industrial machines, and powerful computers for development and data analysis.

As the company grows, it becomes challenging to manage and track all its equipment.

### Problems faced:

* There is no central system to track equipment.
* Employees waste time searching for equipment instead of doing their work.
* It is difficult to know which equipment is being used and how often.
* The company cannot plan properly for future equipment needs.
* Some equipment gets lost or misplaced.
* This causes delays and possible financial losses.

## Project Goal

The task is to build an **Inventory Tracking System** that helps the company manage equipment in a simple and efficient way.

The system uses:

* **Oracle APEX** for the main database and web application
* **Python** for integration and employee-side tools

##System Components

1. Oracle APEX (Main System)

This will be the central prototype.

It will:
* Allow admins to add new equipment
* Update and manage equipment quantities
* Track which employee is using which equipment
* Allow equipment check-out and check-in
* Generate reports for equipment usage
* Provide an admin dashboard/interface

### 2. Python Application (Employee Side)

This is a simple application used by employees.

It will:

* Connect to the Oracle APEX system using APIs
* Show employees their:

  * Current borrowed equipment
  * Past equipment usage history
* Allow employees to return equipment by entering a Booking ID
* Use QR codes linked to employee IDs to confirm equipment check-in

## Summary
This system will help the company:
* Track all equipment in one place
* Reduce lost or missing items
* Save time for employees
* Improve planning and resource use
* Support company growth in an organized way



