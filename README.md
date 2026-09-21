# Market Intelligence Simulator

### TAM • SAM • SOM Market Analysis & Venture Management Platform

🔗 **Live Demo:** https://delightful-fenglisu-7cf81e.netlify.app/

---

##  Project Overview

**Market Intelligence Simulator** is an interactive web-based business analysis application designed to help students, entrepreneurs, and aspiring product managers evaluate market opportunities using the **TAM, SAM, and SOM** market-sizing framework.

The application allows users to enter business and market assumptions and automatically calculate:

* **TAM — Total Addressable Market**
* **SAM — Serviceable Addressable Market**
* **SOM — Serviceable Obtainable Market**
* **SOM Share**

Users can also maintain a history of their market calculations and download analysis data for further use.

---

##  Project Objectives

The main objectives of this project are to:

* Simplify market-size calculations.
* Provide an interactive TAM, SAM, and SOM analysis tool.
* Help users evaluate potential business opportunities.
* Allow ventures to maintain their business and team information.
* Provide an admin interface for managing registered ventures and users.
* Record previous market analysis calculations.
* Allow users to export market analysis data.
* Provide a simple and responsive interface for business analysis.

---

##  Key Features

## 1. TAM, SAM & SOM Calculator

Users can enter:

* Business/Product Name
* Market Area
* Total Potential Customers
* Annual Revenue per Customer
* SAM Percentage
* SOM Percentage

The simulator automatically calculates the market opportunity and displays the results in an easy-to-understand dashboard.

###  2. Market Size Visualization

The dashboard displays:

* TAM
* SAM
* SOM
* SOM Share
* Estimated customer counts
* Market opportunity bars

This provides a quick visual representation of the relationship between TAM, SAM, and SOM.

###  3. Venture Registration

New users can create a venture account by providing:

* Venture name
* Primary user name
* Email
* Password
* City
* Number of team members

The application supports **2 or 3 members per venture**.

###  4. Team Management

Users can add their venture team members and maintain venture information such as:

* Venture name
* Team members
* Category
* Email
* City

The project supports a maximum of three members for a venture.

###  5. User & Admin Login

The application provides separate experiences for:

**Users**
* Access their venture
* Perform market analysis
* View their venture information

**Administrators**

* Access the users database
* View registered ventures
* View team members
* Search user records
* Download user information

The interface includes role-based visibility for the users/ventures section.

###  6. Market Analysis History

Every market-size calculation can be recorded in the analysis history.

The analysis table stores:

* Date
* Business
* Market Area
* Customers
* Price per Customer
* SAM %
* SOM %
* TAM
* SAM
* SOM

Users can also clear the stored analysis records.

###  7. Data Export

The simulator provides multiple export options, including:

* Market Analysis CSV
* Market Report
* User Database CSV
* User Database JSON

This makes the analysis data easier to use outside the application.

###  8. Multiple Market Areas

Users can perform analysis for different market areas, including:

* Maharashtra
* India
* Global
* Custom Region

Custom regions can also be entered manually.

## 9. Responsive Interface

The interface is designed to adapt to different screen sizes, including desktop, tablet, and mobile layouts.

---

#  How TAM, SAM & SOM Are Calculated

The simulator uses the following calculation logic:

### TAM

**Total Addressable Market**

```text
TAM = Total Potential Customers × Annual Revenue per Customer
```

### SAM

**Serviceable Addressable Market**

```text
SAM Customers = Total Customers × SAM %
```

```text
SAM = SAM Customers × Annual Revenue per Customer
```

### SOM

**Serviceable Obtainable Market**

```text
SOM Customers = SAM Customers × SOM %
```

```text
SOM = SOM Customers × Annual Revenue per Customer
```

The application calculates these values dynamically based on the assumptions entered by the user.

---

##  Application Modules

The application contains four primary sections:

| Module                  | Purpose                              |
| ----------------------- | ------------------------------------ |
|  Market Analysis      | Calculate TAM, SAM and SOM           |
| Analysis             | View previous market calculations    |
|  All Users & Ventures | Admin-only user and venture database |
|  My Venture           | Manage venture and team information  |

---

##  Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Data Storage

* Browser LocalStorage

### Hosting

* Netlify

### Development Approach

* Single-page web application
* Client-side calculations
* Client-side data management
* Responsive UI

The project stores users and market analysis records using browser `localStorage`.

---

##  Project Structure

```text
market-intelligence-simulator/
│
├── market_intelligence_simulator.html
├── README.md
└── screenshots/
    ├── dashboard.png
    ├── market-analysis.png
    ├── venture-management.png
    └── admin-dashboard.png
```

---

##  How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/market-intelligence-simulator.git
```

### 2. Open the project

Navigate to the project folder:

```bash
cd market-intelligence-simulator
```

### 3. Run the application

Since this is a client-side HTML application, you can simply open:

```text
market_intelligence_simulator.html
```

in your browser.

Alternatively, use **VS Code Live Server** for a better development experience.

---

##  Live Demo

The project is hosted on Netlify and can be accessed here:

 **https://delightful-fenglisu-7cf81e.netlify.app/**

---

##  Example Use Case

A venture can enter:

```text
Product: SignBridge
Market: Maharashtra
Potential Customers: 473,271
Annual Revenue per Customer: ₹1,200
SAM: 30%
SOM: 5%
```

The simulator then calculates the corresponding TAM, SAM, and SOM values and presents the results through the dashboard.

This can help a student or entrepreneur understand the potential size of a market before developing a business strategy.

---

##  Academic / MBA Application

This project can be used for:

* MBA Product Management projects
* Business Analytics projects
* Entrepreneurship projects
* Startup ideation
* Market research exercises
* PBL projects
* Venture evaluation
* Market sizing exercises

It demonstrates how business assumptions can be converted into quantitative market-size estimates.

---

##  Business Value

The simulator helps transform basic market assumptions into structured business insights.

### Input

```text
Customers
     ↓
Revenue / Customer
     ↓
SAM %
     ↓
SOM %
```

### Analysis

```text
Market Assumptions
        ↓
TAM Calculation
        ↓
SAM Calculation
        ↓
SOM Calculation
```

### Output

```text
Market Opportunity
        ↓
Business Insight
        ↓
Venture Evaluation
```

---

##  Future Enhancements

Potential future improvements include:

* Backend database integration
* Secure authentication
* Cloud-based user accounts
* Advanced market forecasting
* Interactive charts and graphs
* Competitor analysis
* Industry benchmarking
* Automated market research
* AI-powered market insights
* PDF report generation
* Advanced dashboard analytics
* Multi-user cloud access
* Real-time market data integration

---

##  Project Note

This project is currently a **prototype/simulation application**. User and analysis information is stored in browser `localStorage`, so it is intended primarily for demonstration, academic, and prototype purposes rather than production-grade secure data management.

---

##  Author

**Ritu**

MBA | Product Management & Business Analytics

### Areas of Interest

* Product Management
* Business Analytics
* Data Analysis
* Market Research
* Entrepreneurship
* Technology & Innovation

---

##  Project

If you find this project useful for learning about market sizing, TAM, SAM and SOM analysis, feel free to explore the repository and try the live demo.

🔗 **Live Application:**
https://delightful-fenglisu-7cf81e.netlify.app/

---
