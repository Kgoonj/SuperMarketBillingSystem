# 🛒 Supermarket Billing System (C++ Console Application)

This is a **Supermarket Billing System** built in C++ that simulates a complete billing and product management environment. It includes features for both administrators and buyers, such as inventory management, discount handling, stock updates, online purchasing with QR code simulation, and receipt generation.

---

## 💡 Features

### 👨‍💼 Admin Panel
- Add new products with details like category, stock, and expiry date
- Edit product information
- Delete products
- View all products
- Filter products by category
- Update product stock

### 🛍️ Buyer Panel
- Buy products from the physical market or place online orders
- View product list with details
- Pay via cash or simulated online QR payment
- Receipt generation with discount calculation
- Delivery option for online orders

---

## 📁 File Structure

- `SupermarketFinal.cpp` – Main C++ file containing the entire application logic
- `database.txt` – Product database (auto-created if not present)

---

## 🧠 Concepts Used

- File handling (`fstream`) for persistent product storage
- Object-oriented programming (`class shopping`)
- Vectors for dynamic cart handling
- ASCII UI using standard console output
- Simple QR code simulation for payment
- Time/date management for expiry dates

---

## 🚀 Getting Started

### 🧰 Requirements

- C++ compiler (g++, clang, etc.)

### 🔧 How to Compile and Run

```bash
g++ SupermarketFinal.cpp -o supermarket
./supermarket
