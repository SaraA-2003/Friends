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
│   └── CarDealerShip.sql         # MySQL database schema
├── frontend/
│   ├── templates/
│       ├── index.html            # Homepage
│       ├── beforeLog.html
│       ├── book_from.html
│       ├── book.html
│       ├── bookM.html
│       ├── Clog.html
│       ├── customer.html
│       ├── customerM.html
│       ├── indexAfter.html
│       ├── manager.html
│       ├── Mlog.html
│       ├── report.html
│       ├── salesperson.html
│       ├── salespersonT.html
│       ├── Slog.html
│       ├── transaction.html
│       ├── transactionM.html
│       ├── vehicle.html
│       ├── vehicleM.html     
│   ├── static
|       ├── img
│       ├── fonts           
│       ├── js/
|           ├── bootsnav.js
│           ├── bootstrap.min.js            
│           ├── custom.js
│           ├── feather.min.js
│           ├── jquery.js
│           ├── owl.carousel.min.js
│       ├── animate.css
│       ├── bootsnav.css
│       ├── bootstrap.min.css
│       ├── flaction.css
│       ├── font-awesome.min.css
│       ├── lineareicons.css
│       ├── mystyle.css
│       ├── owl.carousel.min.css
│       ├── owl.theme.default.min.css
│       ├── responsive.css
│       ├── style.css                # CSS styling
├── backend/
│   └── connect.py                   # Python logic for database interaction
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
