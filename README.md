# Online Shop

## Project Overview
This project is an e-commerce platform designed for electronics, built with a robust Python Django backend and a dynamic React frontend. Our goal is to provide users with a seamless shopping experience where they can explore a variety of electronics, compare products, and make purchases with ease.

## Tech Stack
- **Backend:** Python, Django
- **Frontend:** React
- **Database:** PostgreSQL
- **Storage:** Amazon S3
- **Authentication:** JWT (JSON Web Tokens)

## Features
- User authentication and authorization
- Product browsing and filtering
- Shopping cart functionality
- Secure checkout process
- Order management system
- User reviews and ratings for products

## Setup Instructions
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/cursekiller5555-dotcom/online-shop.git
   cd online-shop
   ```
2. **Set up the backend:**  
   - Navigate to the backend directory, install dependencies using pip:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
   - Set up the database and run migrations:
   ```bash
   python manage.py migrate
   ```
3. **Set up the frontend:**  
   - Navigate to the frontend directory and install dependencies:
   ```bash
   cd ../frontend
   npm install
   ```
4. **Run the application:**  
   - Start the Django server from the backend:
   ```bash
   cd ../backend
   python manage.py runserver
   ```
   - In a separate terminal, start the React application:
   ```bash
   cd frontend
   npm start
   ```
5. **Access the application:**  
   Open your browser and go to `http://localhost:3000` to view the application.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for any enhancements or bug fixes.