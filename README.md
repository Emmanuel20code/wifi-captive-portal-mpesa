# WiFi Captive Portal with M-Pesa Integration

A complete WiFi captive portal system with M-Pesa (Daraja API) integration for testing and production use. Users connect to WiFi, authenticate via the portal, and can make payments using M-Pesa.

## Features

- 🔐 Captive portal authentication
- 💳 M-Pesa payment integration (Daraja API)
- 📱 Responsive mobile-first design
- 🔄 Real-time payment status
- 📊 Admin dashboard
- 🗄️ SQLite/PostgreSQL support
- 🔑 Easy credential management

## Prerequisites

- Python 3.8+
- Node.js 14+ (for frontend)
- M-Pesa Daraja API credentials
- WiFi router with captive portal support

## Quick Start

1. Clone the repository
2. Set up environment variables
3. Install dependencies
4. Run the server
5. Configure your router's captive portal to point to this service

See [Setup Guide](./docs/SETUP.md) for detailed instructions.

## API Endpoints

- `POST /api/auth/login` - User authentication
- `POST /api/payment/initiate` - Initiate M-Pesa payment
- `GET /api/payment/status/:transactionId` - Check payment status
- `GET /api/admin/transactions` - Admin transaction history

## Project Structure

