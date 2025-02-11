# Garage Management System - C# OOP Project  

This project is a **Garage Management System** developed in **C#** using **Object-Oriented Programming (OOP) principles**.  
The system is designed to manage a garage that handles different types of vehicles, supporting both fuel-based and electric vehicles.  
The project consists of a **business logic layer** and a **console-based user interface**.

## 🚀 Features  

✔ **Vehicle Management** – Supports multiple vehicle types with unique attributes.  
✔ **Garage Operations** – Track vehicle status (*In Repair, Repaired, Paid*).  
✔ **Energy Management** – Refuel fuel-based vehicles and charge electric vehicles.  
✔ **Tire Maintenance** – Inflate tires up to their maximum pressure.  
✔ **User-Friendly Console UI** – Allows easy interaction with the system.  

## 🛠 Technologies Used  

- **C#**  
- **.NET Framework**  
- **Object-Oriented Programming (OOP)**  
- **Exception Handling**  
- **Collections (List, Dictionary, Enum)**  
- **Class Library (DLL)**  

## 📌 System Structure  

The system is divided into **two main projects**:  

1️⃣ **Ex03.GarageLogic** (Class Library - Business Logic)  
   - Contains the core logic for managing vehicles, owners, and garage operations.  
   - Implements **inheritance and polymorphism** for vehicle types.  
   - Uses **Collections** (List, Dictionary) to store vehicle data efficiently.  
   - Handles exceptions for invalid operations (e.g., refueling with the wrong fuel type).  

2️⃣ **Ex03.ConsoleUI** (Console Application - User Interface)  
   - Handles user input and interaction with the garage system.  
   - Calls the logic layer without directly handling business rules.  
   - Allows adding vehicles, checking statuses, refueling/charging, and inflating tires.  

## 📌 Garage Functionalities  

✔ **Register a Vehicle** – Add new vehicles or update the status of existing ones.  
✔ **View All Vehicles** – Display license plates with filtering by status.  
✔ **Change Vehicle Status** – Update a vehicle's garage status (*In Repair, Repaired, Paid*).  
✔ **Inflate Tires** – Inflate all tires to their maximum pressure.  
✔ **Refuel Vehicles** – Add fuel while ensuring the correct type and within tank capacity.  
✔ **Charge Electric Vehicles** – Add battery charge time without exceeding max capacity.  
✔ **Retrieve Vehicle Details** – Display all relevant details for a given license plate.  
