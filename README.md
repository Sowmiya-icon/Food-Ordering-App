
This Food Ordering App allows users to browse, select, and order a variety of dishes from a curated list of available food items. Built with a user-friendly interface and robust backend, it aims to streamline the process of online food ordering, providing a smooth experience for both customers and administrators.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Secure login and signup for users.
- **Menu Browsing**: Users can view a categorized menu with item descriptions, images, and prices.
- **Search Functionality**: Quickly find desired items with a real-time search bar.
- **Order Management**: Users can add items to their cart, review their order, and place it.
- **Real-time Order Tracking**: Track the order status (optional).
- **Admin Dashboard**: Allows administrators to add, edit, and delete menu items, view orders, and manage users.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Angular
- **Backend**: Spring boot
- **Database**: MySQL
- **Authentication**: JSON Web Tokens (JWT)
- **Payment Integration**: (e.g., Stripe, PayPal) *Optional, if included*
- **Real-time Updates**: Socket.io (optional, if real-time updates are implemented)

## Installation

To get this project up and running on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sowmiya-icon/Food-Ordering-App.git
   cd Food-Ordering-App
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   cd client
   npm install
   ```

3. **Set up Environment Variables**:
   - Create a `.env` file in the root directory and add your configuration:
     ```env
     PORT=5000
     server.port=8080
spring.application.name=my-service
spring.datasource.url=jdbc:oracle:thin:@//localhost:1521/ORCL

     ```

5. **Run the App**:
   - To start the server and client, run:
     ```bash
     npm run dev
     ```

   - This will start both the frontend and backend servers concurrently.

6. **Access the Application**:
   - Open a web browser and navigate to `http://localhost:3000` to access the frontend.

## Usage

1. **Sign Up/Login**:
   - New users can create an account, and existing users can log in.

2. **Browse Menu**:
   - Explore the menu and use filters or search functionality to find specific items.

3. **Add to Cart**:
   - Add desired items to your cart, review, and proceed to checkout.

4. **Order and Track**:
   - Place your order, select payment options, and track the order in real time.

5. **Admin Access** (if applicable):
   - Admins can log into the dashboard to manage the menu, orders, and users.

## Project Structure

```
Food-Ordering-App/
├── client/                     # React frontend
│   ├── public/                 # Public assets
│   ├── src/                    # React components and pages
│   └── package.json
├── server/                     # Backend files
│   ├── controllers/            # Route controllers
│   ├── models/                 # Database models
│   ├── routes/                 # API routes
│   └── server.js               # Main server file
├── .env                        # Environment variables
└── README.md
```

## Contributing

Contributions are welcome! If you’d like to improve this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
