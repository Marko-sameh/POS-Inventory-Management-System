# 🚀 POS & Inventory Management System

A custom-built Point of Sale (POS) and Inventory Management System developed in Java, designed for small to medium-sized businesses. This project combines a modern, responsive desktop interface with powerful backend capabilities for seamless inventory control and sales processing.

## 📽️ Demo Video
Watch the system in action 👉 [Insert your YouTube or Google Drive link here]

---

## 💡 Key Features

- 🧾 **Real-time Sales Transactions**  
  Streamlined POS interface for fast and accurate sales operations.

- 📦 **Inventory Tracking**  
  Monitor stock levels, product batches, and expiration dates with precision.

- 📊 **Customizable Reports**  
  Generate professional invoices and reports using **Jasper Reports**.

- 🛡️ **Secure Database Management**  
  Integrated with **MySQL/phpMyAdmin** for reliable data storage.

- 📁 **Export Options**  
  Export reports to PDF and Excel formats.

- 🔁 **Fractional Quantities Support**  
  Supports managing both main (carton) and sub-units (packs/bags).

- 🧠 **Smart Calculations**  
  Auto-calculate shipping weights, expiration status, and transaction totals.

---

## 🛠️ Technologies Used

- **Java (JDK 13)**
- **Java Swing (GUI)**
- **JasperReports**
- **MySQL + phpMyAdmin**
- **Apache POI**
- **Launch4j/JSmooth** for EXE packaging

---

## 📂 Project Structure

```bash
├── src/
│   ├── gui/              # All GUI components
│   ├── db/               # Database connection and queries
│   ├── reports/          # Jasper report templates
│   ├── models/           # Product, Sale, Inventory classes
│   └── utils/            # Utility classes
├── resources/
│   ├── images/           # UI icons and assets
│   ├── jasper/           # Compiled .jasper report files
│   └── sql/              # SQL dump to setup the database
└── README.md
