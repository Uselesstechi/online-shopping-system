# online-shopping-system

# 🛍️ Online Shopping System

A console-based online shopping system simulating key functionalities of a real-world e-commerce platform. It allows users to browse products, manage carts, and place orders, with administrative support for managing inventory and users. Built with simplicity and modularity in mind.

---

## 🚀 Features

- 👤 **User Management**
  - Registration, login, and account management
- 🛍️ **Product Browsing**
  - View available items, categories, and prices
- 🛒 **Cart Operations**
  - Add/remove products, view cart, and total amount
- 📦 **Order Placement**
  - Place and track orders with summary output
- 🧑‍💼 **Admin Access**
  - Add, edit, and delete product listings
- 🧱 **Structured Codebase**
  - Organized by user/admin roles and feature-specific modules

---

## 🛠️ Tech Stack

| Component      | Technology                |
|----------------|---------------------------|
| Language       | Python 3                  |
| UI             | Command-Line Interface (CLI) |
| Data Handling  | Dictionary & List-based in-memory logic |
| Architecture   | Role-based: User/Admin    |

---

## 📁 Folder Structure

```
online-shopping-system/
├── user.py               # User-side logic
├── admin.py              # Admin-side logic
├── inventory.py          # Product storage and updates
├── cart.py               # Shopping cart features
├── order.py              # Order placement and tracking
├── main.py               # Entry point with CLI menu
└── README.md
```

---

## 🧪 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Uselesstechi/online-shopping-system.git
   cd online-shopping-system
   ```

2. **Run the main program**
   ```bash
   python main.py
   ```

3. **Follow the prompts** to log in as a user or admin, browse products, and place orders.

---

## 📊 Sample CLI Flow

```bash
Welcome to Online Shopping System!
1. Login as User
2. Login as Admin
3. Register
4. Exit

> 1

Available Products:
[1] Shoes - ₹1200
[2] Backpack - ₹800

> Add item 1 to cart
> Checkout

Order Summary:
- Shoes x1: ₹1200
Total: ₹1200
```

---

## 📦 Future Improvements

- Add persistent storage using file I/O or a database
- Integrate payment simulation
- Role-based permissions and password hashing
- Add product search and sorting
- Convert to GUI with Tkinter or web app with Flask

---

## 📜 License

feel free to contact at sohombhowmick14@gmail.com
