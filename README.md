# SmartTradeHub - Revolutionizing E-commerce with Django 🛒

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
  - [For Application](#for-application)
  - [For Users](#for-users)
- [Installation](#installation)
- [Usage](#usage)
- [Pages](#pages)
  - [Home Page](#home-page)
  - [Search Functionality](#search-functionality)
  - [My Listings](#mylistings)
  - [Add Product](#add-product)
  - [Update Product](#update-product)
  - [Delete Product](#delete-product)
  - [User Register](#user-register)
  - [User Login](#user-login)
  - [Admin Dashboard](#admin-dashboard)
    - [Admin Login](#admin-login)
    - [Authentication and Authorization](#authentication-and-authorization)
    - [Products](#products)
    - [Profile](#profile)
  - [Seller Profile](#seller-profile)
  - [Checkout](#checkout)
  - [Payment](#payment)
  - [Payment Success](#payment-success)
- [Video Attachment](#video-attachment)
- [Conclusion](#conclusion)

## Introduction
Welcome to **SmartTradeHub**, the future of online shopping. Built with the power of Django, this platform offers a robust and user-friendly experience for both buyers and sellers. From browsing products to secure transactions, SmartTradeHub ensures a seamless e-commerce journey.

## Features
- **User Authentication and Profiles**: Secure user registration, login, and profile management.
- **Dynamic Product Management**: Easily add, edit, and delete products. Maintain detailed product listings and descriptions.
- **Search and Filtering**: Advanced search and filtering options to help users find exactly what they need.
- **Order Processing and Checkout**: Smooth and intuitive order placement and checkout process.
- **Secure Payments**: Integrated with Stripe for secure payment processing.
- **Admin Dashboard**: Comprehensive admin panel for managing products, orders, and user accounts.
- **User Experience**: Responsive design with Bootstrap and Tailwind CSS ensuring a consistent user experience across devices.


## Technologies Used
- **Backend**: Django 4.x, Python 3.x
- **Frontend**: HTML, CSS, JavaScript, Bootstrap, Tailwind CSS
- **Database**: SQLite3
- **Template Engine**: Django Template Language (DTL)

## Prerequisites

### For Application
Before setting up the project, ensure you have the following prerequisites:
- Python 3.x installed
- Django 4.x installed via pip
- Node.js and npm installed for managing frontend dependencies

### For Users
To fully utilize SmartTradeHub, users should:
- **Create an Account**: Register using a valid email address for account management and order confirmations.
- **Log In**: Access the platform by logging in with their credentials.
- **Payment Method**: Have a valid payment method (credit card, debit card) ready for completing purchases.

## Installation
Follow these steps to set up SmartTradeHub locally:

1. **Clone the Repository**:
    ```
    git clone https://github.com/your-username/e-commerce-django.git
    cd e-commerce-django
    ```

2. **Create a Virtual Environment**:
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Required Packages**:
    ```
    pip install -r requirements.txt
    ```

4. **Install Node.js Dependencies**:
    ```
    npm install
    ```

5. **Apply Migrations**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Create a Superuser**:
    ```
    python manage.py createsuperuser
    ```

7. **Run the Development Server**:
    ```
    python manage.py runserver
    ```

8. **Access the Application**: Open your browser and navigate to `http://127.0.0.1:8000/`.

## Usage
- **Admin Panel**: Manage products, categories, and orders at `http://127.0.0.1:8000/admin/`.
- **User Interface**: Browse products, add items to the cart, and complete the checkout process.
- **Seller Portal**: Add new products or manage existing listings via the seller dashboard.

## Pages

### Home page
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/ebfb42da-a660-4418-8bb2-7385ec471ad7)

### Search functionality
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/d2889426-534d-4ed3-9d04-11ae31e9c5e1)

### Mylistings
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/232bcc0d-527a-4986-bfd4-81a28d512f44)


### Add product
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/d4847083-e599-4c18-a458-650976ef9901)

### Update product
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/70ab5272-bc23-4a61-a099-18833027ee18)

### Delete product
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/dbca1659-dd06-48f5-b1d6-206261cc85a1)

### User register
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/d30ff426-3fb6-4b27-99a5-4e7c19b7af19)

### User login
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/e4d8317f-1352-41de-8b48-46128498030a)

### Admin dashboard

#### Admin login
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/1440db00-bdff-4771-9dfe-4caadb141ef7)

#### Authentication and Authorization
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/3e94d844-6534-4f79-8831-c5aefd1e8208)


#### Products
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/2f32159d-1b52-4089-ab1a-8c48ac1e616b)

#### Profile
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/c96b7d65-4198-4672-a919-bbd53785d1ac)

### Seller profile
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/8f020384-8edb-4389-9144-e8f34a0cae39)

### Checkout
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/36e6acb7-81d0-428a-a94a-780ded9897fb)

### Payment
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/a3234cf6-ffc0-41ed-8814-64293d660425)

### Payment success
![image](https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/886405de-3265-4b3d-83e5-496116641dcc)


## Video attachment
https://github.com/rubikab23/buy-sell-application-django-certification-course/assets/145020830/da3def76-bc37-48ae-9690-0feab661aff6


## Conclusion
SmartTradeHub is designed to transform the e-commerce experience, making it easy and secure for users to buy and sell products online. With a focus on user experience, security, and efficient management, SmartTradeHub is your go-to platform for all your e-commerce needs. 


**Thank you for choosing SmartTradeHub! Happy trading and happy coding !**
