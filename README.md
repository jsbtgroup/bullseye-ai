# Bullseye AI - Stock Prediction Platform

A simple MVP for a stock prediction platform that provides investment recommendations based on real-time market data and selected trading strategies.

## Features

- Real-time stock data integration with Polygon.io API
- Support for multiple investment strategies:
  - Long-term Growth
  - Swing Trading
  - Day Trading
- Interactive stock symbol search
- Real-time price, volume, and market cap display
- Strategy-based prediction with confidence levels
- Modern, responsive UI built with React and Chakra UI

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Polygon.io API key (sign up at https://polygon.io)

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/bullseye-ai.git
cd bullseye-ai
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your Polygon.io API key:
```
REACT_APP_POLYGON_API_KEY=your_polygon_api_key_here
```

4. Start the development server:
```bash
npm start
```

The application will be available at http://localhost:3000

## Usage

1. Enter a stock symbol in the search bar (e.g., AAPL, GOOGL)
2. Select your preferred investment strategy
3. View real-time stock data and prediction
4. The prediction includes:
   - Buy/Sell recommendation percentage
   - Confidence level
   - Price change indicators
   - Strategy-specific recommendations

## Technical Stack

- React.js with TypeScript
- Chakra UI for styling
- Polygon.io API for real-time market data
- Axios for API requests

## Limitations

This is a simplified MVP version with:
- Basic prediction algorithms
- No user authentication
- No historical data analysis
- Limited stock symbol suggestions
- No portfolio management

## Future Improvements

- Advanced prediction algorithms using machine learning
- User authentication and personalized portfolios
- Historical data analysis and visualization
- Real-time price alerts
- Portfolio performance tracking
- Social features for sharing predictions

## License

MIT 