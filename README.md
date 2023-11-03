# Django Stripe Checkout Integration

This Django project demonstrates how to integrate Stripe Checkout for processing payments on your website. With this integration, you can securely accept payments for products or services.

## Features

- Stripe Checkout integration for secure payments.
- E-commerce setup with product listings and shopping cart.
- User authentication and registration system.
- Product catalog with details like name, price, and description.
- Order and payment history tracking.
- Admin panel for product and order management.

## Prerequisites

Before getting started, ensure you have the following:

- Python 3.x ++
- Django 3.x ++
- Stripe account (for API keys)
- Django extensions (for shell_plus)

## Installation

1. Clone the repository:

   ```
   git clone git@github.com:aibunny/django-stripe-checkout.git
   ```


2. Navigate to the project directory:
   ```
   cd django-stripe-checkout
   ```

4. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate
   ```
5. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Configuration

1. Set up your Stripe account and obtain your API keys (publishable and secret).
2. Create a `.env` file in the project root and add your Stripe API keys:
  ```
STRIPE_PUBLISHABLE_KEY=your_publishable_key
STRIPE_SECRET_KEY=your_secret_key
```
 
3. Run database migrations:
   ```
   python manage.py migrate
   ```
4. Create a superuser for the admin panel:
   ```
   python manage.py createsuperuser
   ```
5. Start the development server:
```
   python manage.py runserver
```

## Usage

1. Access the admin panel at `http://localhost:8000/admin/` and log in with the superuser credentials.
2. Add products in the admin panel, including name, price, and description.
3. Visit the e-commerce site at `http://localhost:8000/` to browse products and add them to your cart.
4. Complete a purchase using Stripe Checkout.
5. View order history and payment details on your user profile page.

## Contributing

Feel free to contribute to this project by opening issues or pull requests. Your feedback and improvements are welcome!Feel free to contribute to this project by opening issues or pull requests. Your feedback and improvements are welcome!
