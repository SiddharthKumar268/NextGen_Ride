<div align="center">

# 🚍 NextGen_Ride

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=FF6B35&center=true&vCenter=true&width=700&lines=NFC-Powered+Smart+Transit;GPS+%2B+Digital+Wallet+Integration;Seamless+Student+Fare+System;Making+Travel+Smart+%26+Secure" alt="Typing SVG" />

### 💳 *NFC-based, GPS-powered student fare system with digital wallets & seamless UPI payments*

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

**Making Student Travel Seamless, Smart & Secure! 🎓**

[🚀 Get Started](#-installation--setup) • [✨ Features](#-features) • [🛠️ Tech Stack](#️-technology-stack) • [📱 How It Works](#️-how-it-works)

</div>

---

## 📖 About the Project

<img align="right" src="https://user-images.githubusercontent.com/74038190/229223156-0cbdaba9-3128-4d8e-8719-b6b4cf741b67.gif" width="300">

**NextGen_Ride** is a revolutionary **NFC-based student fare deduction system** that combines cutting-edge technology to transform public transportation for students. 

By integrating **NFC card readers**, **real-time GPS tracking**, and **digital wallet management**, we've created a seamless transit experience that eliminates manual fare handling and ensures accurate, distance-based pricing.

### 🎯 Mission
To revolutionize student transportation through automated fare collection, making every journey efficient, transparent, and hassle-free.

<br clear="right"/>

---

## 🚨 The Problem

<div align="center">

```ascii
╔══════════════════════════════════════════════════════════════╗
║        ⚠️  CHALLENGES IN STUDENT TRANSPORTATION              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  💸  Manual fare collection causing delays                  ║
║  🎫  Lost or damaged physical tickets                       ║
║  📊  Inaccurate fare calculations                           ║
║  ⏰  Time wasted in cash transactions                       ║
║  🔒  No digital payment tracking                            ║
║  📍  No distance-based fair pricing                         ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

Traditional bus fare systems rely on manual collection, leading to inefficiencies, fare disputes, and operational delays. Students need a modern, automated solution.

---

## ✅ Our Solution

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="500">
</div>

**NextGen_Ride** brings transportation into the digital age with a comprehensive automated fare system:

<table>
<tr>
<td width="50%">

### 🎯 Core Features
- 🔹 **NFC Card Integration**
- 🔹 **Real-Time GPS Tracking**
- 🔹 **Digital Wallet System**
- 🔹 **Automated Fare Calculation**

</td>
<td width="50%">

### 🚀 Key Benefits
- ⚡ **Lightning-Fast Transactions**
- 📊 **Accurate Distance-Based Pricing**
- 💰 **Cashless, Contactless Payments**
- 🎓 **Student-Friendly Interface**

</td>
</tr>
</table>

---

## ✨ Features

<div align="center">

| Feature | Description |
|---------|-------------|
| 💳 **NFC-Based Payment** | Students tap their ID cards when boarding and exiting the bus |
| 📍 **Real-Time GPS Integration** | Calculates fare accurately based on the distance traveled |
| 💰 **Digital Wallet** | Students can top up their wallet, and fares are auto-deducted |
| 🔄 **UPI Integration** | Allows easy top-ups via UPI and other payment gateways |
| 📱 **Mobile App Interface** | Check balance, top-up, and manage transactions seamlessly |
| 🤖 **Automated Fare Collection** | Eliminates manual handling and ensures fair pricing |
| 🚌 **Efficient Operations** | Reduces delays and streamlines public transport |
| 📊 **Transaction History** | Complete visibility of all travel and payment records |

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d899-44b4-b1d9-4eeccf656e44.gif" width="600">
</div>

---

## ⚙️ How It Works

<div align="center">

```mermaid
sequenceDiagram
    participant Student
    participant NFC Card
    participant Bus System
    participant GPS Module
    participant Database
    participant Wallet
    
    Student->>NFC Card: Tap In (Boarding)
    NFC Card->>Bus System: Read Card ID
    Bus System->>GPS Module: Record Boarding Location
    GPS Module-->>Database: Store Entry Point
    
    Note over Student,Database: Student Travels...
    
    Student->>NFC Card: Tap Out (Exit)
    NFC Card->>Bus System: Read Card ID Again
    Bus System->>GPS Module: Record Exit Location
    GPS Module->>Database: Calculate Distance
    Database->>Wallet: Deduct Fare
    Wallet-->>Student: Send Receipt & Update Balance
    
    Note over GPS Module: Distance-Based<br/>Fair Pricing
    Note over Wallet: Instant<br/>Transaction
```

</div>

### 🔄 Step-by-Step Process

<table>
<tr>
<td width="33%" align="center">

### 1️⃣ Tap-In
<img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="80">

Students tap their NFC ID card while entering the bus

</td>
<td width="33%" align="center">

### 2️⃣ GPS Tracking
<img src="https://user-images.githubusercontent.com/74038190/212257467-1e9a5f3a-d7b8-491c-8d52-1f4e3a5f9f3e.gif" width="80">

System records boarding location using GPS module

</td>
<td width="33%" align="center">

### 3️⃣ Tap-Out
<img src="https://user-images.githubusercontent.com/74038190/212257454-16e3712e-945a-4ca2-b238-408ad0bf87e6.gif" width="80">

Students tap their card again on exit

</td>
</tr>
<tr>
<td width="33%" align="center">

### 4️⃣ Fare Calculation
<img src="https://user-images.githubusercontent.com/74038190/212257465-7ce8d493-cac5-494e-982a-5a9deb852c4b.gif" width="80">

Distance computed via GPS coordinates

</td>
<td width="33%" align="center">

### 5️⃣ Auto-Deduction
<img src="https://user-images.githubusercontent.com/74038190/212257460-738ff738-247f-4445-a718-cdd0ca76e2db.gif" width="80">

Fare automatically deducted from digital wallet

</td>
<td width="33%" align="center">

### 6️⃣ Top-Up
<img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a5f3a-d7b8-491c-8d52-1f4e3a5f9f3e.gif" width="80">

Easy wallet recharge via UPI/payment gateway

</td>
</tr>
</table>

---

## 🏗️ System Architecture

```mermaid
flowchart TB
    subgraph Hardware["🔧 Hardware Layer"]
        A[NFC Reader]
        B[GPS Module]
        C[Bus Onboard Computer]
    end
    
    subgraph Frontend["🌐 Frontend Layer"]
        D[HTML/CSS Interface]
        E[JavaScript Logic]
        F[Mobile App UI]
    end
    
    subgraph Backend["⚙️ Backend Services"]
        G[Node.js Server]
        H[Express.js API]
        I[Payment Gateway]
    end
    
    subgraph Database["💾 Database Layer"]
        J[(Oracle DB 21c)]
        K[Student Records]
        L[Transaction Logs]
        M[Wallet Balance]
    end
    
    subgraph External["🌍 External Services"]
        N[UPI Gateway]
        O[GPS Service]
        P[SMS Notifications]
    end
    
    A --> G
    B --> G
    C --> G
    D --> H
    E --> H
    F --> H
    H --> G
    G --> J
    I --> N
    G --> O
    K --> J
    L --> J
    M --> J
    G --> P
    
    style Hardware fill:#ff6b35,stroke:#cc5529,stroke-width:3px
    style Frontend fill:#00d4ff,stroke:#0099cc,stroke-width:3px
    style Backend fill:#00ff88,stroke:#00cc66,stroke-width:3px
    style Database fill:#ff66ff,stroke:#cc44cc,stroke-width:3px
    style External fill:#ffff00,stroke:#cccc00,stroke-width:3px
```

---

## 🛠️ Technology Stack

<div align="center">

### 🌐 Frontend Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Responsive web interface with intuitive student dashboard**

### ⚙️ Backend Technologies

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

**RESTful API architecture with real-time processing**

### 💾 Database

![Oracle](https://img.shields.io/badge/Oracle_21c-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**Oracle Database 21c Express Edition for robust data management**

### 🔧 Hardware Components

![NFC](https://img.shields.io/badge/NFC_Reader-0066CC?style=for-the-badge&logo=contactless-payment&logoColor=white)
![GPS](https://img.shields.io/badge/GPS_Module-4CAF50?style=for-the-badge&logo=google-maps&logoColor=white)

**NFC Reader for card scanning & GPS Module for location tracking**

### 💳 Payment Integration

![UPI](https://img.shields.io/badge/UPI-00897B?style=for-the-badge&logo=google-pay&logoColor=white)

**Seamless UPI and payment gateway integration**

</div>

---

## 📂 Project Structure

```
NextGen_Ride/
│
├── 📁 backend/                     # Server-side application
│   ├── 🚀 server.js                # Express server entry point
│   ├── 🔐 .env                     # Environment variables
│   │
│   ├── 📁 config/                  # Configuration files
│   │   └── db.js                   # Oracle DB connection
│   │
│   ├── 📁 models/                  # Database models
│   │   ├── Student.js              # Student schema
│   │   ├── Transaction.js          # Transaction records
│   │   └── Wallet.js               # Wallet management
│   │
│   ├── 📁 routes/                  # API endpoints
│   │   ├── nfc.js                  # NFC tap in/out routes
│   │   ├── wallet.js               # Wallet operations
│   │   └── payment.js              # UPI integration
│   │
│   ├── 📁 controllers/             # Business logic
│   │   ├── fareController.js       # Fare calculation logic
│   │   └── gpsController.js        # GPS processing
│   │
│   └── 📁 middleware/              # Express middleware
│       └── auth.js                 # Authentication
│
├── 📁 frontend/                    # Client-side interface
│   ├── 🏠 index.html               # Landing page
│   ├── 📊 dashboard.html           # Student dashboard
│   ├── 💳 wallet.html              # Wallet management
│   ├── 📜 history.html             # Transaction history
│   │
│   └── 📁 assets/                  # Static resources
│       ├── 🎨 css/
│       │   └── styles.css          # Main stylesheet
│       ├── ⚡ js/
│       │   ├── main.js             # Core JavaScript
│       │   └── wallet.js           # Wallet functions
│       └── 🖼️ images/              # UI assets
│
├── 📁 hardware/                    # Hardware integration
│   ├── nfc_reader.ino              # NFC reader firmware
│   └── gps_module.ino              # GPS module code
│
├── 📁 docs/                        # Documentation
│   ├── API.md                      # API documentation
│   └── SETUP.md                    # Setup guide
│
├── 📦 package.json                 # NPM dependencies
└── 📖 README.md                    # You are here!
```

---

## 🚀 Installation & Setup

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100">
</div>

### Prerequisites

- Node.js (v14.x or higher)
- Oracle Database 21c Express Edition
- NFC Reader Hardware
- GPS Module

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/next-gen-ride.git
cd next-gen-ride
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Database

Edit `db.js` with your Oracle Database credentials:

```javascript
module.exports = {
  user: "your_username",
  password: "your_password",
  connectString: "localhost:1521/XE"
};
```

### 4️⃣ Setup Environment Variables

Create a `.env` file in the root directory:

```env
PORT=3000
DB_USER=your_db_username
DB_PASSWORD=your_db_password
DB_CONNECTION_STRING=localhost:1521/XE
UPI_API_KEY=your_upi_api_key
GPS_API_KEY=your_gps_api_key
```

### 5️⃣ Start the Server

```bash
# Production mode
node server.js

# Development mode with auto-reload
nodemon server.js
```

### 6️⃣ Access the Application

Open your browser and navigate to:

```
http://localhost:3000
```

<div align="center">

**🎉 NextGen_Ride is now running!**

</div>

---

## 📱 Screenshots

<div align="center">

### 🌐 Web Interface

<img src="https://github.com/user-attachments/assets/a90a8e8e-142d-4089-b240-40c2b562327b" width="800" alt="NextGen Ride Interface">

*Modern, intuitive student dashboard with real-time wallet balance and transaction history*

---

### ⚙️ Node.js Server Response

<img src="https://github.com/user-attachments/assets/ebec159a-d2c9-4c15-a085-ed7a3e32773b" width="800" alt="Server Response">

*Backend server processing NFC transactions and GPS data in real-time*

---

### 💾 Database Management

<img src="https://github.com/user-attachments/assets/96fe219e-61b2-4265-ba2d-532a183ea071" width="800" alt="Database Server">

*Oracle Database 21c handling student records, transactions, and wallet balances*

</div>

---

## 🔮 Future Enhancements

<div align="center">

```mermaid
timeline
    title NextGen_Ride Development Roadmap
    section Phase 1
        Q1 2025 : Core NFC System
               : GPS Integration
               : Digital Wallet Launch
    section Phase 2
        Q2 2025 : AI Fare Optimization
               : Student ID Verification
               : Mobile App Release
    section Phase 3
        Q3 2025 : Multi-Transport Integration
               : Predictive Analytics
               : Route Optimization
    section Phase 4
        Q4 2025 : Blockchain Integration
               : IoT Fleet Management
               : Smart City Integration
```

</div>

### 🎯 Planned Features

- 🤖 **AI-Based Fare Optimization** - Machine learning for dynamic pricing based on demand
- 🎓 **Student ID Verification System** - Integration with institutional databases
- 📱 **Native Mobile Apps** - iOS and Android applications with offline capability
- 🚍 **Multi-Transport Support** - Extend to trains, metros, and shared vehicles
- 🌐 **Smart City Integration** - Connect with broader urban mobility solutions
- 📊 **Advanced Analytics Dashboard** - Insights for transport authorities
- ⛓️ **Blockchain Transaction Ledger** - Enhanced security and transparency
- 🔔 **Smart Notifications** - Real-time alerts for low balance, promotions
- 🗺️ **Route Planning** - Suggest optimal routes and schedules

---

## 💡 Use Cases

<table>
<tr>
<td width="50%">

### 👨‍🎓 For Students
- ✅ Contactless, cashless payments
- ✅ Accurate distance-based fares
- ✅ Digital transaction history
- ✅ Easy wallet top-ups via UPI
- ✅ No more lost or damaged tickets

</td>
<td width="50%">

### 🚌 For Transport Operators
- ✅ Automated fare collection
- ✅ Reduced operational delays
- ✅ Real-time revenue tracking
- ✅ Eliminate cash handling
- ✅ Better route planning data

</td>
</tr>
<tr>
<td width="50%">

### 🏫 For Institutions
- ✅ Track student attendance
- ✅ Ensure student safety
- ✅ Manage transport subsidies
- ✅ Generate usage reports
- ✅ Integrated ID card system

</td>
<td width="50%">

### 🏛️ For Authorities
- ✅ Transparent fare system
- ✅ Usage analytics and insights
- ✅ Efficient resource allocation
- ✅ Environmental benefits
- ✅ Data-driven policy making

</td>
</tr>
</table>

---

## 🎓 How to Use

<div align="center">

### For Students

```mermaid
graph LR
    A[Get NFC ID Card] --> B[Install Mobile App]
    B --> C[Add Money to Wallet]
    C --> D[Tap In When Boarding]
    D --> E[Tap Out When Exiting]
    E --> F[Fare Auto-Deducted]
    F --> G[Check Transaction History]
    
    style A fill:#ff6b35
    style C fill:#00d4ff
    style F fill:#00ff88
```

</div>

1. **Register** - Link your student ID with the NextGen_Ride system
2. **Top-Up** - Add money to your digital wallet using UPI
3. **Tap-In** - Scan your NFC card when boarding the bus
4. **Travel** - Enjoy your journey worry-free
5. **Tap-Out** - Scan again when exiting
6. **Relax** - Fare is automatically calculated and deducted

---

## 🤝 Contributors

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="150" />

### 👨‍💻 Development Team

**Siddharth Goutam Kumar**  
*Lead Developer & Project Architect*

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

</div>

---

## 📧 Contact & Support

<div align="center">

### 📬 Get in Touch

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kumarsiddharth166@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)

**📮 Email:** kumarsiddharth166@gmail.com

For any queries, feature requests, or bug reports, please reach out via email or open an issue on GitHub!

</div>

---

## 🌟 Show Your Support

<div align="center">

If you find **NextGen_Ride** useful and innovative, please consider giving it a ⭐!

[![GitHub stars](https://img.shields.io/github/stars/your-username/next-gen-ride?style=social)](https://github.com/your-username/next-gen-ride/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/your-username/next-gen-ride?style=social)](https://github.com/your-username/next-gen-ride/network/members)
[![GitHub issues](https://img.shields.io/github/issues/your-username/next-gen-ride?style=social)](https://github.com/your-username/next-gen-ride/issues)

---

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

### 💡 NextGen_Ride: Making Student Travel Seamless, Smart & Secure!

**© 2025 NextGen_Ride | Revolutionizing Student Transportation**

<img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d899-44b4-b1d9-4eeccf656e44.gif" width="500">

</div>
