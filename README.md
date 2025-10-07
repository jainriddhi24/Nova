# Nova - Modern eCommerce Platform

Nova is a full-stack eCommerce platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that offers a seamless shopping experience.

## Features

- 🛍️ **Product Management**
  - Browse products with category filters
  - Search functionality
  - Product details with images
  - Related products suggestions
  - Price filtering
  - Pagination support

- 🔐 **User Authentication**
  - JWT-based authentication
  - Protected routes for users and admins
  - Password recovery system
  - Profile management

- 👤 **User Dashboard**
  - Order history
  - Profile updates
  - Cart management

- 👑 **Admin Dashboard**
  - Product management (CRUD operations)
  - Category management
  - User management
  - Order tracking
  - Image upload functionality

- 🛒 **Shopping Cart**
  - Add/remove items
  - Persistent cart data
  - Price calculations
  - Quantity management

## Tech Stack

- **Frontend**: React.js, Ant Design, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **File Upload**: Express-formidable
- **State Management**: Context API
- **Routing**: React Router v7

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/jainriddhi24/Nova.git
```

2. Install dependencies for backend:
```bash
cd Nova
npm install
```

3. Install dependencies for frontend:
```bash
cd novafront
npm install
```

4. Set up environment variables:
Create `.env` file in root directory with:
```
PORT=8080
DEV_MODE=development
MONGO_URL=your_mongodb_url
JWT_SECRET=your_secret
```

5. Run the development servers:
```bash
# Run backend server
npm run server

# Run frontend server (in another terminal)
cd novafront
npm start
```

## Contributing

Contributions are welcome! Feel free to submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
Nova is a full-stack eCommerce platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that offers a seamless shopping experience.
