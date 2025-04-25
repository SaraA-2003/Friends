# Friends Motors

**Friends Motors** is a full-stack Car Dealership Management System that provides a complete solution for browsing, booking, and managing cars. It includes a MySQL database, a responsive website, and Python-based backend logic to support user and employee operations.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python  
- **Database:** MySQL  

## Features

### 🔹 User Interface
- Browse available cars with images and details
- Review the most recent cars
- Allow users to log in and book a visit to see the car
- Allow users to view their booking details

### 🔹 Employee Interface (Manager & Salesperson)

#### Salesperson Interface
- Salesperson can log in with their assigned ID and username
- View and manage tables containing:
  - Customer bookings
  - Transactions and booking details
  - Available cars for purchase or rent
- Ability to filter, add, remove, and update data
- Ability to log out

#### Manager Interface
- Manager can log in with their assigned ID and username
- View and manage tables containing:
  - Customer bookings
  - Transactions and booking details
  - Available cars for purchase or rent
  - Salespeople working in the company
- Ability to filter, add, remove, and update data
- Access to a report page with dynamic data (e.g., available vehicles, transactions, sales, etc.)
- Ability to log out


## Project Structure

```plaintext
Friends-Motors/
├── database/
│   └── friends_motors.sql         # MySQL database schema
├── frontend/
│   ├── index.html                 # Homepage
│   ├── styles.css                 # CSS styling
│   └── script.js                  # JavaScript interactions
├── backend/
│   └── app.py                     # Python logic for database interaction
├── README.md
```


### Running the Application

Make sure you have:

- MySQL installed for the database
- Python 3 installed for backend logic
- Visual Studio Code (or any code editor) for development
- Web browser to interact with the frontend

### Database Configuration

Before running the project, make sure to update the `connect.py` file with your own MySQL database credentials.

In the `connect.py` file, locate the following line:

> ```plaintext
> conn = mysql.connector.connect(host='localhost', username='root', password='1234', database='CarDealerShip')
> ```
