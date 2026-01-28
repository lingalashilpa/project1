# 📚 Online Book Store

An **Online Book Store** is a web-based application that allows users to browse, search, and purchase books online. It provides a simple and user-friendly platform for customers and an efficient management system for administrators.

---

## 🚀 Features

### 👤 User Features

* User registration and login
* Browse books by category, author, or title
* Search books using keywords
* View book details (price, description, author, ratings)
* Add books to cart
* Place orders and make payments
* View order history

### 🛠️ Admin Features

* Admin login
* Add, update, and delete books
* Manage categories and authors
* View and manage customer orders
* Monitor stock availability

---

## 🏗️ System Architecture

* **Frontend**: User interface for customers and admins
* **Backend**: Handles business logic and API requests
* **Database**: Stores user data, book details, and orders

---

## 💻 Technology Stack

* **Frontend**: HTML, CSS, JavaScript (React / Angular – optional)
* **Backend**: Python (Django / Flask) or Java (Spring Boot) or Node.js
* **Database**: MySQL / PostgreSQL / MongoDB
* **Authentication**: JWT / Session-based authentication
* **Payment Gateway**: Razorpay / Stripe / PayPal (optional)

---

## ⚙️ Installation & Setup

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/online-book-store.git
   ```

2. Navigate to the project directory

   ```bash
   cd online-book-store
   ```

3. Install dependencies

   ```bash
   npm install  # or pip install -r requirements.txt
   ```

4. Configure the database in the config file

5. Run the application

   ```bash
   npm start  # or python manage.py runserver
   ```

6. Open the browser and visit:

   ```
   http://localhost:3000
   ```

---

## 🗂️ Database Schema (Basic)

* **Users** (user_id, name, email, password, role)
* **Books** (book_id, title, author, category, price, stock)
* **Orders** (order_id, user_id, total_amount, order_date)
* **Order_Items** (order_item_id, order_id, book_id, quantity)

---

## ✅ Advantages

* Easy access to a wide range of books
* Saves time compared to physical stores
* 24/7 availability
* Efficient inventory management

---

## 🔮 Future Enhancements

* Book reviews and ratings
* Recommendation system using AI/ML
* Mobile application
* Wishlist feature
* Discount and coupon system

---

## 👩‍💻 Author

**Shilpa**
Project for academic / learning purpose




