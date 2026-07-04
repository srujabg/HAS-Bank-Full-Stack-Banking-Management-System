<h1 align="center">HAS Bank - Full Stack Banking Management System</h1>

<p>
HAS Bank is a full-stack MERN banking management application that allows users to securely create and manage online bank accounts. The system supports deposits, withdrawals, fund transfers, transaction history tracking, and admin-based account management through a responsive web interface.
</p>


## 🚀 Features

- Full Stack MERN Application (MongoDB, Express.js, React.js, Node.js)
- Secure user authentication and authorization using JSON Web Tokens (JWT)
- User account creation and management
- Deposit and withdrawal functionality
- Fund transfer system
- Transaction history tracking
- Admin dashboard for managing user account requests and account statuses
- Role-based access control
- Responsive user interface


## 🛠️ Tech Stack

### Frontend
- React.js
- HTML
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB


## 📂 Project Structure

```
HAS-Bank/

├── Frontend/
│   └── React application files

├── Backend/
│   └── Node.js and Express server files

├── package.json
└── README.md
```


## ⚙️ Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install backend dependencies:

```bash
npm install
```

Install frontend dependencies:

```bash
cd Frontend
npm install
```

Run the project:

```bash
npm run both
```


## 🔐 Environment Variables

Create a `.env` file and add:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CORS_DOMAINS=http://localhost:3000
```


## 📌 Functionalities

### User
- Register and login securely
- Manage bank account
- Deposit money
- Withdraw money
- Transfer funds
- View transaction history


### Admin
- Manage user account requests
- Monitor account details
- Manage account status


## 📈 Future Improvements

- Enhanced dashboard analytics
- Improved transaction visualization
- Additional security features
- Deployment optimization
