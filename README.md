# Lemonade-Stand

A Django application that implement a sales tracking and reporting system to help manage the incredible amounts of lemonade they sell on a daily basis, and automatically calculate appropriate commissions for their hard-working sales staff

### How to run it
- pip install -r requirements.txt
- python manage.py runserver

### Admin Login
- http://127.0.0.1:8000/admin/
- Username: admin
- Password: 123456

### User Login
- http://127.0.0.1:8000/sales/login/
- Username: user
- Password: 123123

### Index
- http://127.0.0.1:8000/sales/

### Form
- http://127.0.0.1:8000/sales/form/
- Input the staff name, the beverage sold and the quantity of sale
- Store the sales record

### Report
- http://127.0.0.1:8000/sales/report/
- Input the staff name, the start date and the end date
- Generate a report that presents the sales made and commissions earned by a salesperson between specific dates
