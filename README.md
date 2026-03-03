# 🛒 SuperMarket Billing System (C++)

A fully functional, console-based SuperMarket Billing System built using **Modern C++**.  
This project generates a professional supermarket-style bill with **multiple items, discounts, taxes, and final savings**, similar to real retail billing software.

It demonstrates clean **OOP design**, formatted bill printing using **iomanip**, and real-time **date & time** generation using `ctime`.

---

## ⭐ Features
- Add unlimited items with:
  - Item Name  
  - Quantity  
  - Price  
- Automatic Calculations:
  - Total amount  
  - 10% discount for bills above ₹1000  
  - CGST (2.5%)  
  - SGST (2.5%)  
  - Final universal 5% discount  
  - Net payable amount  
  - Total savings  
- Automatically generates:
  - Unique Bill Number  
  - Current Date & Time  
- Printed Output:
  - Clean, aligned columns  
  - Supermarket-style receipt format  

Perfect for **students, beginners, mini-projects, and portfolio GitHub repositories**.

---

## 🛠️ How to Compile & Run

### **1️⃣ Compile**
```bash
g++ SuperMarketBill.cpp -o bill
```

### **2️⃣ Run**
```bash
./bill
```

---

## 📌 Sample Output (Bill Preview)

```
===============================================================================
                             SMART MART SUPERMARKET
                                Latur, Maharashtra
===============================================================================
---------------------------------------------------------------------------------------
                            CUSTOMER BILL DETAILS
---------------------------------------------------------------------------------------
Bill No : SM20250210123015
Bill Date : 10-02-2025 12:30:15
Customer Name : Rahul
---------------------------------------------------------------------------------------
S.No   Item Name        Qty     Price      Total
---------------------------------------------------------------------------------------
1      Rice             2       50.00      100.00
2      Oil              1       150.00     150.00
3      Sugar            3       40.00      120.00
---------------------------------------------------------------------------------------
Total Amount             : ₹370.00
10% Discount             : ₹0.00
CGST (2.5%)              : ₹9.25
SGST (2.5%)              : ₹9.25
Final Discount (5%)      : ₹19.43
---------------------------------------------------------------------------------------
Net Amount               : ₹369.07
---------------------------------------------------------------------------------------
                 YOU HAVE SAVED : ₹19.43
---------------------------------------------------------------------------------------
Time : 12:30:15 PM
---------------------------------------------------------------------------------------
                    THANK YOU FOR SHOPPING WITH US!
===============================================================================

---

## 📝 Project Description (Use in GitHub & Resume)
```
A C++ console application that simulates a real supermarket billing system. 
It supports multiple items, auto-calculates discounts, GST, final amount, and prints a formatted retail-style receipt. 
Developed using object-oriented programming, dynamic arrays, and formatted output manipulation.
```

---

## 👤 Author
**Your Name : IDZz 
GitHub: your: ishwar261-oss


