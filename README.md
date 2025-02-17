### **PyShop - Simple Online Store**  

#### **Overview**  
PyShop is a **basic online shop** built with Django and Bootstrap. It dynamically displays products (fruits) with images, prices and an "Add to Cart" button.  

#### **Features**  
* List of products with images and prices  
* Responsive design with Bootstrap  
* Django-based backend for product management  
* SQLite database for storing product data  

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
2. **Create a Virtual Environment & Install Dependencies**  
```sh
python -m venv venv
source venv/bin/activate    # On macOS/Linux
venv\Scripts\activate       # On Windows
pip install -r requirements.txt
```
3. **Run Migrations**  
```sh
python manage.py migrate
```
4. **Run the Development Server**  
```sh
python manage.py runserver
```
5. **Access the App**  
Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

#### **Contributing**  
Feel free to fork this repository and submit pull requests with improvements.

#### **License**  
This project is licensed under the **MIT License**.
