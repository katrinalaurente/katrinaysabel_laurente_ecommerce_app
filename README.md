# IS312 Activity 4: E-Commerce App
This project was created for Activity 4 in the IS 312 course. It shows how to build a RESTful API using Python to manage products and customer orders. The application connects to a SQLite database to handle CRUD operations (Create, Read, Update, and Delete) and sends data back in JSON format, which can be tested using tools like Postman.

# Framework Used 
**Flask** - A small and simple Python tool used to build websites quickly without needing complex settings.

# How to Run the Application Locally
1. Open PyCharm and create a new project named **LaurenteKatrina_ecommerce_app**.
2. **Install Flask** and other needed tools by running this command in your terminal: _pip install flask flask-sqlalchemy marshmallow_
3. Under the project directory, create a new Python file named **app.py**.
4. **Copy the code** from [LaurenteKatrina_Hello_World/app.py](LaurenteKatrina_Hello_World/app.py) and paste it into your local `app.py`.
5. Run the program.
6. Enter the server URL (usually [http://127.0.0.1:5000/](http://127.0.0.1:5000)) and add /products or /orders at the end to see the data.
7. Use different buttons in Postman (like GET or POST) to check if the data is being saved correctly.

# Application Testing Tool
**Postman** is a tool used to send requests to the server to check if the API is working properly.

**How to Setup Postman**
1. Go to the official Postman website to download and install the app.
2. Open the app and create a free account.
3. Once the Flask server is running in PyCharm, type your local URL into Postman to start testing your products and orders.
