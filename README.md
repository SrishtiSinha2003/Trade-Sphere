# Trade-Sphere

**Trade-Sphere** is a stock trading platform inspired by Zerodha, offering real-time stock tracking, portfolio management, and smooth stock buying and selling features. Built with modern web technologies, Trade-Sphere aims to provide an intuitive and efficient interface for users to manage their investments.

## Features

- **Real-time Stock Data**: Live updates of stock prices using external APIs.
- **Portfolio Management**: Track your stock holdings and monitor portfolio performance.
- **Buy/Sell Stocks**: Seamless stock trading experience.
- **Transaction History**: Detailed record of your trading transactions.
- **Interactive Charts**: Visualize stock trends and portfolio performance using Chart.js.
- **User Authentication**: Secure login and signup process with encrypted credentials.
- **Testing**: Comprehensive testing of key features using Jest.
- **Database**: MongoDB for efficient data storage and retrieval of user portfolios and transactions.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (React, Bootstrap)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Live APIs**: Integrated with external stock market APIs (e.g., Alpha Vantage, Yahoo Finance) for real-time data
- **Charts**: Data visualization using [Chart.js](https://www.chartjs.org/)
- **Testing**: [Jest](https://jestjs.io/) for unit and integration testing
- **Version Control**: Git, GitHub
- **Hosting**: Deployed on [Your Deployment Platform] (e.g., Heroku, Vercel)

## Installation and Setup

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SrishtiSinha2003/Trade-Sphere.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Trade-Sphere
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Set up environment variables:
    - Create a `.env` file in the root directory.
    - Add your MongoDB URI and API keys for live stock data (e.g., Alpha Vantage):
      ```bash
      MONGO_URI=your_mongodb_uri
      API_KEY=your_live_api_key
      ```

5. Start the development server:
    ```bash
    npm start
    ```

6. Open your browser and go to `http://localhost:3000` to view the application.

## Running Tests

This project uses **Jest** for testing. To run the tests, use the following command:

```bash
npm test

