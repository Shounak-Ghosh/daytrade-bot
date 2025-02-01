# daytrade-bot
What the code does:
1. Web scrapes active stocks from yahoo finance.
2. Evaluates active stocks (can evaluate 100s of stocks per minute as the application is multithreaded) using different strategies such as EMA crossovers/resistance breakthroughs, regression stock direction testing, and news sentiment analysis (buys and sells stocks based on quarterly earnings information or big news!).
3. Evaluates current stock portfolio by checking if any stock no longer seems worth holding.
Sends buy and sell requests using the alpaca paper trading api

Code TODOs:
1. Add more strategies to ensure better returns
2. Refine buying and selling times
3. Differentiate between long term and short term day trading positions

Features to add:
1. Add a GUI to display current portfolio and current stock evaluations
 user should be able to choose which stocks to follow and which strategies to use
2. Add a GUI to display current portfolio and current stock evaluations (embed alpaca display)
