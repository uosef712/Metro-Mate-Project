  # MetroMate: Cairo Metro Management System

A comprehensive console-based metro management system simulating Cairo's metro network with user authentication,
subscription management, ride planning, and administrative controls.

## Features

### 👥 User Features
- **Registration & Authentication** - Secure login system with user roles
- **Subscription Management** - Multiple plan types (Student, Public Monthly/Yearly, Wallet Cards)
- **Ride Planning** - Interactive station selection with visual journey simulation
- **Balance Management** - Wallet system with recharge capabilities
- **Ride History** - Detailed tracking of all journeys with timestamps
- **Personal Information Management** - Update profile details easily

### ⚙️ Admin Features
- **User Management** - View, edit, and manage user accounts
- **Subscription Plan Management** - Configure pricing for all subscription tiers
- **Station Management** - Add, remove, and edit metro stations across all lines
- **Fare Management** - Dynamic pricing configuration for different stages
- **Ride Analytics** - Comprehensive view of all user journeys
- **System Configuration** - Set current date and manage system parameters

## 🗺️ Metro Network

The system includes all three lines of Cairo Metro:

- **Line 1 (Blue)** - 35 stations from New Marg to Helwan
- **Line 2 (Red)** - 20 stations from Shubra Al-Khaimah to El-Monib  
- **Line 3 (Green)** - 29 stations from Rod Elfarag to Adly Mansour

With intelligent inter-line transfer handling at key interchange stations:
- Al-Shohadaa (Lines 1 & 2)
- Nasser (Lines 1 & 3) 
- Attaba (Lines 2 & 3)

## Installation & Usage

### Prerequisites
- Windows OS (uses Windows.h for console operations)
- C++ Compiler (supporting C++17 standard)

### Compilation

**System Structure**
MetroMate/
├── User Management
│   ├── Registration/Login System
│   ├── Profile Management
│   └── Balance Handling
├── Subscription System
│   ├── Student Subscriptions
│   ├── Public (Monthly/Yearly) Subscriptions
│   └── Wallet Cards
├── Ride Management
│   ├── Station Selection
│   ├── Route Calculation
│   ├── Fare Calculation
│   └── Journey Simulation
├── Admin Portal
│   ├── User Management
│   ├── Station Management
│   ├── Pricing Control
│   └── Analytics
└── Data Persistence
    ├── User Data
    ├── Ride History
    └── System Configuration
    
    ```bash
g++ metro.cpp -o MetroMate.exe -std=c++17
