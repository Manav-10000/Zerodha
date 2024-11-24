# 📈 Stock Trading Platform

A modern full-stack web application built using the **MERN stack** (MongoDB, Express, React, Node.js) to simulate real-time stock trading. This platform is designed to provide users with a seamless and interactive experience for managing virtual investments.

---

## 🏆 Key Features

- **User Authentication**: Secure registration and login using JWT for session management.
- **Portfolio Management**: Track and manage a virtual stock portfolio, including trade history and current holdings.
- **Real-Time Stock Data**: Integrated with third-party APIs to fetch real-time stock prices and market trends.
- **Dynamic Charting**: Visualize portfolio performance and stock price trends using interactive and responsive charts.
- **Responsive Dashboard**: A user-friendly dashboard optimized for both desktop and mobile, providing a summary of trades, portfolio statistics, and market insights.

---

## 💻 Tech Stack

### Frontend
- **React.js**: For building a responsive and dynamic user interface.
- **Redux**: State management for seamless data flow across the app.
- **Chart.js**: To render interactive charts for performance analysis.

### Backend
- **Node.js**: Server-side runtime for scalable and efficient handling of requests.
- **Express.js**: RESTful APIs to handle user and stock-related requests.
- **MongoDB**: Database to store user details, portfolio data, and trade history.

### Integration
- **Third-Party APIs**: For fetching live stock market data.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- A valid API key for a stock data provider (e.g., Alpha Vantage, Yahoo Finance API).

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/Manav-10000/Zerodha]
   cd Zerodha

2.Install dependencies:
   # For the backend
    cd backend
    npm install

  # For the frontend
    cd ../frontend
    npm install

 3.Set up environment variables: Create a .env file in the backend directory with the following:
    PORT=3000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    API_KEY=your_stock_api_key

4.Run the application:
  # Start the backend server
    cd backend
    npm start

  # Start the frontend development server
    cd ../frontend
    npm start
    
##🛠️ Features in Development

-Advanced stock screening tools.
-Social trading features (following and copying top traders).
-Personalized notifications for portfolio performance and market alerts.




