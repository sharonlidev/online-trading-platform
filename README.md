# 📈 Online Trading Platform

An end-to-end online trading platform that simulates the core functionalities of a modern brokerage system. This platform supports user registration, stock trading (buy/sell), portfolio management, real-time market data updates, and order execution logic—designed with scalability, modularity, and maintainability in mind.

---

## 🚀 Features

- User authentication & portfolio management
- Simulated market with price fluctuations
- Real-time order book and trade matching engine
- RESTful API interface for frontend interaction
- Order types: Market & Limit orders
- Trade history and performance analytics

---

## 🧱 Technologies Used

| Component       | Technology                        |
|----------------|-----------------------------------|
| Backend         | Python (Flask), SQLite            |
| Frontend        | HTML, CSS, JavaScript             |
| API Layer       | Flask RESTful                     |
| Database        | SQLite (can be swapped with PostgreSQL) |
| Message Queue   | (Planned) Redis / RabbitMQ        |
| Authentication  | JWT-based (Planned)               |
| Deployment      | Docker (Planned), GitHub Actions (CI/CD) |

---


Key components:

- **Frontend UI**: Simple dashboard to view portfolio, trade stocks, and view transaction history.
- **API Layer**: Routes REST calls to backend logic securely.
- **Matching Engine**: Core logic to match buy/sell orders.
- **Market Simulator**: Generates fake stock price changes for testing.
- **Database**: Stores persistent user data, orders, and trades.


---

## ✅ To-Do List

### 🔐 Authentication
- [ ] Implement user registration/login
- [ ] JWT token-based auth middleware
- [ ] Secure password hashing (bcrypt)

### 📊 Market & Pricing
- [x] Create dummy stock data
- [ ] Simulate price fluctuations using async task or cron job
- [ ] Add historical price tracking

### 🧮 Trade Engine
- [x] Implement order matching logic
- [ ] Support for limit/market orders
- [ ] Add order cancellation support
- [ ] Add order timeout expiration logic

### 📦 Backend API
- [x] Endpoint: `/register`, `/login`, `/portfolio`, `/orders`
- [ ] Endpoint: `/stocks`, `/history`, `/price-feed`
- [ ] Rate limiting and validation

### 🖥️ Frontend Interface
- [ ] Dashboard with portfolio & real-time price feed
- [ ] Trade execution form (Buy/Sell)
- [ ] Order history and trade confirmation UI

### 🧪 Testing & Quality
- [ ] Unit tests for trade engine & API endpoints
- [ ] Integration test suite
- [ ] Linting and code formatter setup (e.g., Black, Flake8)

### 🐳 Deployment
- [ ] Dockerize app for local development
- [ ] Docker Compose (API + DB)
- [ ] CI/CD pipeline using GitHub Actions


