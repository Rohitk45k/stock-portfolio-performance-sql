# stock-portfolio-performance-sql
This project uses SQL to analyze 4,000+ stock transactions. It helps track how users buy and sell stocks, find top-performing stocks, and detect trading patterns and data issues.

**Project Title**
Stock Portfolio Performance Tracker (SQL Project)

**Dataset Information**
- transaction_id`: Unique ID for each transaction
- `user_id`: ID of the user
- `stock_symbol`: Stock ticker (e.g., AAPL, TSLA)
- `transaction_type`: Buy or Sell
- `quantity`: Number of shares
- `price_per_share`: Price of each share
- `transaction_date`: Date of transaction

**Objectives / Questions Solved**
1. Total number of Buy and Sell transactions per user
2. Total investment amount (Buy) for each user
3. Average price per share for each stock when bought
4. Total shares held by each user per stock (Buy - Sell)
5. Users who only made Buy transactions
6. Most traded stock by number of transactions
7. Total quantity sold for each stock
8. Stock with the highest average sell price
9. Top 5 stocks with the highest total investment value
10. Stocks that were only sold and never bought (data issue)
11. User with the highest number of transactions
12. Users who traded more than 5 different stocks
13. Users who made both Buy and Sell for the same stock
14. Number of transactions per month across all users
    
**Tools Used**

MySQL
- VS Code / DBeaver
- Git & GitHub
