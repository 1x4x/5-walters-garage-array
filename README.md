# 🚗 Walters Garage 🛠️

Welcome to Walters Garage, a small C# console application for managing a garage full of different vehicle types. This project demonstrates object-oriented programming with inheritance, validation, searching, and vehicle storage.

## ✨ Features

- 🚙 Support for multiple vehicle types:
  - Car
  - Motorcycle
  - Airplane
  - Bus
  - Boat
- 🅿️ Park and remove vehicles from a garage
- 🔎 Search by registration number or other vehicle properties
- 📊 Count vehicles by type
- 🧮 Track total capacity and available spaces
- ✅ Prevent duplicate registration numbers and invalid input

## 🏗️ Project Structure

```text
5-walters-garage-array/
├── Garage/
│   ├── Airplane.cs
│   ├── Boat.cs
│   ├── Bus.cs
│   ├── Car.cs
│   ├── Garage.cs
│   ├── Garage.csproj
│   ├── Garage.sln
│   ├── Motorcycle.cs
│   ├── Program.cs
│   └── Vehicle.cs
├── .gitignore
├── README.md
└── LICENSE (if added later)
```

## 🧩 Core Design

The application is built around a base `Vehicle` class and a `Garage` class:

- `Vehicle` stores shared properties such as registration number, color, and wheel count
- Each vehicle subclass adds specialized values like engine size, seat count, or boat length
- `Garage` manages the collection and validates parking rules

## ▶️ Run the Application

From the repository root, run:

```bash
dotnet run --project Garage/Garage.csproj
```

You can also open the solution file and run it in your IDE.

## 🎯 Example Menu Options

The console app includes options to:

- 🚗 Park a vehicle
- 🚚 Remove a vehicle
- 📋 List all parked vehicles
- 📈 Show counts by vehicle type
- 🔍 Search by registration number
- 🧪 Search by vehicle characteristics
- 🚪 View free parking spaces

## 🧪 Technologies Used

- C#
- .NET 9
- Console application

## 🏁 Summary

Walters Garage is a simple but practical example of garage management built using object-oriented programming principles in C#.
