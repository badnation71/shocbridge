# ShocBridge - Intelligent Footwear E-Commerce Platform

## Overview
ShocBridge is an intelligent shoe shopping platform that uses foot measurement data to recommend the right size, reducing dissatisfaction and returns for both consumers and vendors.

## Features
- 🦶 **Foot Measurement Tool** - Accurate foot measurement input system
- 🤖 **AI Size Recommendation** - Intelligent sizing algorithm based on measurements
- 👟 **Shoe Catalog** - Browse and filter shoes by brand, style, price
- 🛒 **Shopping Cart** - Add/remove items, manage quantities
- 💳 **Payment Integration** - Stripe integration for secure payments
- 👤 **User Accounts** - Registration, login, order history
- 📦 **Order Management** - Track orders, returns, replacements
- 🎯 **Admin Dashboard** - Manage inventory, orders, users
- 📱 **Responsive Design** - Works on desktop, tablet, mobile

## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT
- **Payment**: Stripe API
- **Deployment**: Docker, AWS/Heroku

## Quick Start

### Prerequisites
- Node.js v16+
- PostgreSQL 13+
- Docker (optional)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/badnation71/shocbridge.git
cd shocbridge
```

2. **Setup Backend**
```bash
cd backend
npm install
cp .env.example .env
npm start
```

3. **Setup Database**
```bash
psql -U postgres
CREATE DATABASE shocbridge;
\c shocbridge
\i database/schema.sql
\i database/seed.sql
```

4. **Serve Frontend**
```bash
cd frontend
python -m http.server 8080
```

Visit `http://localhost:8080`

## Project Structure
```
shocbridge/
├── frontend/
├── backend/
├── database/
├── docker-compose.yml
├── .env.example
└── README.md
```

## License
MIT License