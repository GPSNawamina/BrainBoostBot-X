# 💸 FinBotX

**FinBotX** is a modern financial tracking web application designed to help users take control of their expenses, monitor their income, and gain valuable insights into their spending habits. Inspired by platforms like Emma and Mint, FinBotX offers a clean UI and rich analytics for smarter money management.

## 🚀 Features

- 🔐 Secure user authentication (OAuth 2.0 or JWT-based)
- 📊 Real-time dashboard with expense & income summaries
- 🧾 Transaction management (add/edit/delete)
- 📂 Categorization of spending (food, bills, transport, etc.)
- 📅 Monthly budget planner and alerts
- 📉 Visual analytics with graphs & charts
- 🔎 Search and filter transactions
- 📥 CSV export for transactions

## 🛠 Tech Stack

### Frontend
- React.js (with Hooks & Context API)
- Chart.js or Recharts for data visualization
- Axios for API communication
- Tailwind CSS / Material UI for styling

### Backend
- Node.js + Express.js
- MongoDB (with Mongoose)
- Authentication: OAuth 2.0 / JWT
- RESTful APIs

## ⚙️ Installation

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)

### Backend Setup

```bash
cd backend
npm install
# Add your MongoDB URI and secret keys in a `.env` file
npm run dev
```
### Frontend Setup

```bash
Copy
Edit
cd frontend
npm install
npm start
