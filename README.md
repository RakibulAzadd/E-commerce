 # 🛒 Ecommerce Management System

An Ecommerce Management System built with **Python**, **Django**, **SQLite**, and styled with **Bootstrap**. This project provides a full-stack web solution for managing products, orders, users, and transactions.

---

## 📄 Description

The Ecommerce Management System is a comprehensive web application designed to facilitate seamless online shopping experiences and efficient backend management. Built using Django as the core framework, it includes essential features such as product listing, shopping cart functionality, order processing, and a secure admin dashboard for managing users, inventory, and transactions. The responsive Bootstrap front end ensures compatibility across devices, while SQLite provides a lightweight, easily manageable database solution. This system is ideal for learning full-stack development or deploying a small to medium-scale ecommerce platform.

---

## 🚀 Features

- 🧑‍💼 Admin Dashboard
- 🛍️ Product Management (CRUD)
- 📦 Order Management
- 👥 User Registration & Authentication
- 🛒 Shopping Cart
- 💳 Checkout & Payment Simulation
- 📊 Basic Sales Analytics
- 💡 Responsive UI using Bootstrap

---

## 🛠 Tech Stack

- **Backend:** Python, Django
- **Database:** SQLite
- **Frontend:** HTML, CSS, Bootstrap
- **Authentication:** Django Auth
- **Templates:** Django Template Language (DTL)

---

## 📁 Project Structure

```
ecommerce/
├── ecommerce/         # Project settings
├── store/             # Main app (products, orders, cart)
├── templates/         # HTML templates
├── static/            # Static files (CSS, JS, images)
├── db.sqlite3         # SQLite database
└── manage.py          # Django management script
```

---

## ⚙️ Installation

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/ecommerce-management-system.git
cd ecommerce-management-system
```

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Apply migrations**

```bash
python manage.py migrate
```

5. **Create a superuser (admin)**

```bash
python manage.py createsuperuser
```

6. **Run the server**

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` to access the app.

---

## 🔐 Admin Panel

- URL: `http://127.0.0.1:8000/admin/`
- Login using the superuser credentials created earlier.

---

## 📸 Screenshots

> [App Front page](./static/media/category/ss.png)
---


## 🤝 Contributing

Contributions are welcome! Please fork the repository and open a pull request.

---

## 📬 Contact

For questions or collaboration:
- GitHub: [Ecommerce](https://github.com/RakibulAzadd/E-commerce.git)
- Email: rakibul@gmail.com

