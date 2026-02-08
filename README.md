# Kart E-Commerce Django

**A full-stack eCommerce web application built using Django, showcasing product browsing, cart management, and order handling.**

This repository implements a basic online shopping platform using **Python and Django** with essential eCommerce features such as user authentication, product catalog, cart system, and order processing.

---

## 🛍️ Project Overview

This project is a **Django-based eCommerce platform** that allows users to:
- Browse through categories and products
- Add products to a cart
- Manage cart contents
- Register and login as a user
- Proceed to checkout

It demonstrates a full novice-to-intermediate understanding of **web application development with Django**, including data models, templates, forms, session-based cart handling, and user management. :contentReference[oaicite:1]{index=1}

---

## 🧠 Key Features

- **User Authentication:** Login and signup functionality  
- **Product Browsing:** View products categorized by categories  
- **Shopping Cart:** Add, update, and remove items in the cart  
- **Order Management:** Track and place orders  
- **Admin Panel:** Manage products and categories via Django admin

---

## 🧰 Tech Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS, JavaScript  
- **Templates:** Django Templating Engine  
- **Database:** SQLite (default Django DB)  
- **Static Assets:** CSS and JavaScript for UI interactions

---

## 📁 Project Structure

📦 kart-ecommerce-django
├── accounts/ # User authentication app

├── carts/ # Shopping cart logic

├── category/ # Category management app

├── store/ # Product store app

├── templates/ # HTML templates

├── static/ # Static files (CSS, JS, images)

├── manage.py # Django entrypoint

├── requirements.txt

└── README.md

## 🚀 Installation & Setup

Follow these steps to run the project locally:

### 1. **Clone the repository**

    ```bash git clone https://github.com/Jiya112005/kart-ecommerce-django.git
        cd kart-ecommerce-django

### 2. **Creating Virtual Environment**

        python -m venv venv
# Windows

        venv\Scripts\activate

# macOS/Linux

        source venv/bin/activate

### 3. **Install dependencies**

        pip install -r requirements.txt

### 4. **Apply migrations**
      
      python manage.py makemigrations
      python manage.py migrate

### 5. **Create superuser (for admin)**
    
      python manage.py createsuperuser

### 6. **Run the development server**
      
      python manage.py runserver


### Open your browser and visit:

      http://127.0.0.1:8000/

