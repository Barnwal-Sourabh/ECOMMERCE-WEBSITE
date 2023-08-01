# G&STORE Ecommerce Website

![store](https://github.com/Barnwal-Sourabh/ECOMMERCE-WEBSITE/assets/91266813/76fa27d5-6350-41fb-964f-e04a86bd96a2)
![STORE1](https://github.com/Barnwal-Sourabh/ECOMMERCE-WEBSITE/assets/91266813/4e82d326-8db1-40f5-bfea-1e628da2ff22)

![store2](https://github.com/Barnwal-Sourabh/ECOMMERCE-WEBSITE/assets/91266813/5c292276-0f8b-482b-8a42-7b4765440ad9)
![store3](https://github.com/Barnwal-Sourabh/ECOMMERCE-WEBSITE/assets/91266813/80e18b3a-5c50-45e6-aee0-d52179dbad87)

![store 4](https://github.com/Barnwal-Sourabh/ECOMMERCE-WEBSITE/assets/91266813/67ee109a-aa9c-42c1-8a24-4d98f9fe4dfc)


G&STORE is an Ecommerce website project built using React, React Router, JavaScript, SCSS, REST API, Strapi, Stripe for payment integration, and MySQL database.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

G&STORE Ecommerce Website is a full-fledged online store application that allows users to browse through various products, add them to their cart, make purchases, and complete payments using the Stripe payment gateway. The application is built with a frontend powered by React and React Router for handling navigation, while the backend is built with Strapi to manage the product and user data using REST APIs. MySQL database is used to store the data.

## Features

- User registration and authentication
- Product browsing and filtering
- Product details display
- Shopping cart functionality
- Checkout process with Stripe integration
- Order history and tracking
- Admin panel for managing products and orders

## Requirements

Before running the application, ensure you have the following software installed:

- Node.js (https://nodejs.org) - to run the frontend application
- MySQL Server (https://dev.mysql.com/downloads/mysql/) - for the database management
- Strapi (https://strapi.io/documentation/developer-docs/latest/getting-started/quick-start.html) - to set up the backend server and REST APIs

## Installation

1. Clone this Git repository to your local machine:

```
git clone https://github.com/your-username/TGstore-ecommerce.git
```

2. Install the frontend dependencies. Navigate to the project folder and run:

```
cd TGstore-ecommerce/frontend
npm install
```

3. Install the backend dependencies. Navigate to the project folder and run:

```
cd TGstore-ecommerce/backend
npm install
```

4. Set up the MySQL database:
   - Create a new database in MySQL for the project.
   - Update the database connection settings in `TGstore-ecommerce/backend/config/database.js` with your MySQL credentials.

5. Set up Strapi backend:
   - Follow the instructions in the Strapi documentation to set up the backend server and create necessary content types and REST APIs.

6. Start the development server for frontend:

```
cd TGstore-ecommerce/frontend
npm start
```

7. Start the backend server for Strapi:

```
cd TGstore-ecommerce/backend
npm start
```

## Usage

- Visit the application in your web browser at `http://localhost:3000/`.
- Browse through the products, add items to your cart, and proceed to checkout using the Stripe payment gateway.
- To access the Strapi admin panel, visit `http://localhost:1337/admin` and log in with your credentials.

## Technologies Used

- React
- React Router
- JavaScript
- SCSS (Sass)
- REST API
- Strapi
- Stripe
- MySQL

## Contributing

We welcome contributions to enhance the features and fix issues. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request, describing the changes you made.

## License

The G&STORE Ecommerce Website is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.
