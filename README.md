# Description
The Vendor Management System, developed using Django, is a web application designed for streamlined vendor relationship management.

It encompasses functionalities for managing vendor profiles, tracking purchase orders, and evaluating vendor performance.

Users can create, update, and delete vendor profiles, monitor purchase orders, and assess vendor performance metrics such as on-time delivery rate, quality rating average, average response time, and fulfillment rate.

# Roadmap
- Start and Plan: Understand the project scope and set up the basic structure.

- Vendor Setup: Create a system to manage vendor information and test it.

- Purchase Order Management: Develop purchase order forms and check their functionality.

- Performance Evaluation: Add a scoring system for vendors and calculate scores dynamically.

- Historical Tracking: Include a history feature to track vendor performance over time.

- Testing Phase: Conduct thorough testing, find and fix bugs.

- Deployment: Put the system online for use.

- Maintenance: Keep an eye on the system, fix issues, and assist users.

# Features
- User and Admin can add or remove vendors
- User and Admin can delete vendors
- User and Admin can update vendors
- User can search for specific vendor through their name and address.
- Admin can give the perfect calculations for performance
- Easy to use
- API endpoints can be checked using Django ORM
- User can add vendor.
- User and admin can view order details.
- User and admin can delete order details
- User and admin can update order details
- User and admin can search for order through po_number and vendor name.
- API Reference
# Vendor Profile Management
- POST /api/vendors/: Create a new vendor.
-  GET /api/vendors/: List all vendors.
- GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
- PUT /api/vendors/{vendor_id}/: Update a vendor's details.
- DELETE /api/vendors/{vendor_id}/: Delete a vendor.
-  UPDATE /api/vendors/{vendor_id}/: Update a vendor.
# Purchase Order Tracking
 -  POST /api/purchase_orders/: Create a new order.
 - GET /api/purchase_orders/: List all orders.
 - GET /api/purchase_orders/{vendor_id}/: Retrieve a specific order's details.
 - PUT /api/purchase_orders/{vendor_id}/: Update a order's details.
 - DELETE /api/purchase_orders/{vendor_id}/: Delete a order.
 - UPDATE /api/purchase_orders/{vendor_id}/: Update a order.
# Tech Stack
Stack: Python, Django, dbsqlite3

Server: localhost:8000

# Installation
```http
  python -m venv venv

source venv/Scripts/activate

pip install django

pip install djangorestframework

pip install -r requirements.txt

python manage.py makemigrations 

python manage.py migrate

python manage.py createsuperuser 

python manage.py runserver

http://localhost:8000/vendors/  --for vendor list

http://localhost:8000/admin  --for admin
```













