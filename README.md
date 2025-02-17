# **PyShop - Simple Online Store**  

#### **Overview**  
PyShop is a **basic online shop** built with Django and Bootstrap. It dynamically displays products (fruits) with images, prices and an "Add to Cart" button.  

#### **Features**  
* List of products with images and prices  
* Responsive design with Bootstrap  
* Django-based backend for product management  
* SQLite database for storing product data

## Screenshots

### Admin Panel - Product List
![admin-prodcuts](https://github.com/user-attachments/assets/f07937a9-d4d6-4b10-9e15-2d9a3f3bcc5e)
This screen shows the list of products in the Django Admin Panel, including their prices and stock levels.

### Admin Panel - Dashboard
![admin](https://github.com/user-attachments/assets/ca86dc26-e4ec-43c2-90ff-7923fbf17aa7)

The main admin panel allows management of users, groups, products and offers.

### Product Listing Page
![products](https://github.com/user-attachments/assets/4566bd67-1e5a-4821-99b2-1744b1a0e106)
The frontend of the PyShop application displays available products with images, prices and an "Add to Cart" button.

#### **Project Structure**  
```
* PyShop  
├── 📂 products/                # Django app for handling products  
│   ├── 📂 migrations/          # Database migrations  
│   ├── 📂 templates/           # HTML templates for the products app  
│   ├── __init__.py  
│   ├── admin.py                # Admin panel settings  
│   ├── apps.py                 # App configuration  
│   ├── models.py               # Database models  
│   ├── tests.py                # Unit tests  
│   ├── urls.py                 # URL routing  
│   ├── views.py                # Logic for handling product views  
│  
├── 📂 pyshop/                  # Main Django project folder  
├── 📂 templates/               # Base HTML templates  
│   ├── base.html               # Main layout  
│  
├── db.sqlite3                  # SQLite database  
├── manage.py                   # Django CLI manager  
```

#### **Setup Instructions**  
1. **Clone the Repository**  
```sh
git clone https://github.com/MaheshNanavare/PyShop.git
cd PyShop
```
2. **Run Migrations**  
```sh
python manage.py migrate
```
3. **Run the Development Server**  
```sh
python manage.py runserver
```
4. **Access the App**  
Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

#### **Contributing**  
Feel free to fork this repository and submit pull requests with improvements.

#### **License**  
This project is licensed under the **MIT License**.
