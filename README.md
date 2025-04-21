# 🚗 Vehicle Rental System

A Windows Forms application built using **C# and .NET Framework**, designed for managing a simple vehicle rental service. Users can rent vehicles, return them, and view rental history using a clean and intuitive graphical interface.

---

## 📌 Features

- Rent a vehicle by providing user and vehicle details
- Return rented vehicles with date tracking
- View rental history of all vehicles and customers
- Factorial, prime number, and factorial series calculator
- User input validation using RequiredFieldValidator equivalent logic
- Connected to a **SQL Server** database for persistent data management

---

## 🛠 Technologies Used

- C#
- Windows Forms (WinForms)
- .NET Framework
- Microsoft SQL Server
- ADO.NET for database interaction
- Visual Studio IDE

---

## 💻 UI Overview

- `MainForm.cs` – Navigation to different forms
- `RentalForm.cs` – Rent a new vehicle
- `ReturnForm.cs` – Return a rented vehicle
- `RentalHistoryForm.cs` – View rental history
- `MathUtilitiesForm.cs` – Factorial, Prime & Series calculation
- `ValidationForm.cs` – User input validation demo

---

## 🗃 Database Design

**Database Name**: `VehicleRentalDB`

**Tables**:
- `Rentals`
  - `RentalID` (int, PK)
  - `CustomerName` (varchar)
  - `VehicleName` (varchar)
  - `RentalDate` (datetime)

- `Returns`
  - `ReturnID` (int, PK)
  - `RentalID` (int, FK)
  - `ReturnDate` (datetime)

---

## 🧪 Sample Screenshots

| Rent Vehicle | Return Vehicle | Rental History |
|--------------|----------------|----------------|
| ![Rent](screenshots/rent_vehicle.png) | ![Return](screenshots/return_vehicle.png) | ![History](screenshots/rental_history.png) |

---

## 🚀 Getting Started

1. Clone this repository using GitHub Desktop or:
   ```bash
   git clone https://github.com/your-username/VehicleRentalSystem.git

📄 License

This project is open-source and available under the [MIT License](LICENSE).
