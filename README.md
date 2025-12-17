# E-commerce Application

A full-stack e-commerce application built with React frontend and Node.js backend.

## Project Structure

```
E-commerce/
├── backend/           # Node.js Express API
│   ├── controller/    # Route controllers
│   ├── model/         # Database models
│   ├── routes/        # API routes
│   ├── service/       # Business logic
│   ├── config/        # Configuration files
│   └── server.js      # Main server file
├── my-app/           # React frontend
│   ├── src/          # Source files
│   ├── public/       # Static files
│   └── package.json  # Frontend dependencies
└── README.md

```

## Features

- Product catalog display
- Product details view
- Shopping cart functionality
- Responsive design
- RESTful API backend

## Technologies Used

### Frontend
- React 19
- React Router DOM
- Vite
- CSS3

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- CORS
- JWT Authentication

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/rakeshp2024eee-lab/E-commerce.git
cd E-commerce
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../my-app
npm install
```

### Running the Application

1. Start the backend server
```bash
cd backend
npm start
```
The backend will run on http://localhost:5000

2. Start the frontend development server
```bash
cd my-app
npm run dev
```
The frontend will run on http://localhost:5173

## API Endpoints

- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get product by ID
- `POST /api/products` - Create new product
- `PUT /api/products/:id` - Update product
- `DELETE /api/products/:id` - Delete product
- `GET /api/products/search?q=query` - Search products

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.