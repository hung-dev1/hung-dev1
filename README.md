# 📈 Stock Market Dashboard

A modern, responsive front-end application for tracking and analyzing stock market data in real-time. Built with cutting-edge technologies as part of the FPT Aptech curriculum.

## ✨ Features

- **Real-Time Stock Quotes** - Track live stock prices and market movements
- **Interactive Charts** - Visualize historical price trends with candlestick and line charts
- **Portfolio Management** - Create and manage your watchlist of favorite stocks
- **Market Analysis Tools** - Technical indicators and price predictions
- **Responsive Design** - Seamless experience on desktop, tablet, and mobile devices
- **Dark Mode Support** - Eye-friendly interface with light and dark themes

## 🛠️ Tech Stack

- **Frontend Framework:** React.js / Vue.js / Angular
- **UI Library:** Material-UI / Tailwind CSS / Bootstrap
- **State Management:** Redux / Vuex / Context API
- **Charting Library:** Chart.js / ECharts / TradingView Lightweight Charts
- **HTTP Client:** Axios / Fetch API
- **Build Tool:** Vite / Webpack
- **API Integration:** RESTful APIs / WebSocket for real-time data
- **Version Control:** Git & GitHub

## 🚀 Getting Started

### Prerequisites
- Node.js (v14.0 or higher)
- npm or yarn package manager
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hung-dev1/stock-market-dashboard.git
   cd stock-market-dashboard
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Create environment configuration:**
   ```bash
   cp .env.example .env.local
   ```
   Update `.env.local` with your API keys and endpoints.

4. **Start the development server:**
   ```bash
   npm start
   # or
   yarn dev
   ```

5. **Open your browser:**
   Navigate to `http://localhost:3000` (or your configured port)

## 📁 Project Structure

```
stock-market-dashboard/
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/           # Page components
│   ├── services/        # API calls and external services
│   ├── hooks/           # Custom React hooks
│   ├── store/           # State management
│   ├── utils/           # Helper functions
│   ├── styles/          # Global styles and themes
│   └── App.jsx          # Main App component
├── public/              # Static files
├── .env.example         # Environment variables template
├── package.json         # Project dependencies
└── README.md           # This file
```

## 📚 Available Scripts

- `npm start` - Run development server
- `npm run build` - Create production build
- `npm run test` - Run test suite
- `npm run lint` - Check code quality
- `npm run dev` - Alternative development command

## 🔗 API Integration

This project uses financial APIs to fetch real-time stock data:
- **Alpha Vantage** - Stock quotes and technical indicators
- **IEX Cloud** - Market data and company information
- **Finnhub** - Real-time market data and news

See `docs/API_SETUP.md` for detailed configuration instructions.

## 📖 Documentation

- [Setup Guide](./docs/SETUP.md)
- [API Documentation](./docs/API_SETUP.md)
- [Component Guide](./docs/COMPONENTS.md)
- [Contributing Guidelines](./CONTRIBUTING.md)

## 🎓 About the Developer

**Student:** Hung Dev  
**School:** FPT Aptech  
**Program:** Professional IT Training  
**Specialization:** Full Stack Web Development

## 📞 Contact & Support

- **Email:** hung.dev@fptu.edu.vn
- **GitHub:** [@hung-dev1](https://github.com/hung-dev1)
- **LinkedIn:** [Hung Dev](https://linkedin.com/in/hung-dev1)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 🙏 Acknowledgments

- FPT Aptech instructors and mentors
- React and open-source community
- Financial API providers for data services
- All contributors and users of this project

---

**Note:** This is an educational project created for learning purposes. Stock market data should be verified through official sources before making investment decisions.

**Last Updated:** April 24, 2026
