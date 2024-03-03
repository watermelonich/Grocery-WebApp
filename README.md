# Grocery WebApp

A Grocery WebApp for to manage groceries built with Python, HTML, CSS, and JavaScript.

## Technologies Used

1. **Frontend:**
   - UI is crafted using HTML, CSS, JavaScript, and Bootstrap.

2. **Backend:**
   - Powered by Python and Flask, the backend handles the logic and data processing.
   - Flask provides a lightweight and efficient web framework, making it an excellent choice for developing web applications.

3. **Database:**
   - MySQL is utilized as the database management system, storing crucial information about orders, products, and unit of measure (uom).

## Installation Instructions

Follow these steps to set up the Grocery WebApp on your local machine:

### 1. MySQL Installation

Download and install MySQL for your operating system. For Windows, you can find the installer [here](https://dev.mysql.com/downloads/installer/).

### 2. Python Dependencies

Install the necessary Python packages by running the following command:

```bash
pip install mysql-connector-python
```

### 3. Project Structure

The project is organized into the following structure:

```
.
├── README.md
├── backend
│   ├── orders_dao.py
│   ├── products_dao.py
│   ├── server.py
│   ├── sql_connection.py
│   └── uom_dao.py
└── ui
    ├── css
    │   ├── bootstrap.min.css
    │   ├── custom.css
    │   ├── sidebar-menu.css
    │   └── style.css
    ├── images
    │   └── bg.jpg
    ├── index.html
    ├── js
    │   ├── custom
    │   │   ├── common.js
    │   │   ├── dashboard.js
    │   │   ├── manage-product.js
    │   │   └── order.js
    │   └── packages
    │       ├── bootstrap.min.js
    │       └── jquery.min.js
    ├── manage-product.html
    └── order.html
```

### 4. Run the Application

Start the server and launch the Grocery WebApp:

```bash
cd backend

python3 server.py
```

Visit [http://localhost:5000](http://localhost:5000) in your web browser to access the Grocery WebApp.
