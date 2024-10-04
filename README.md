# Crypto Volating Trading Bot

## Description
This crypto trading bot monitors price fluctuations across all coins on Binance and trades on the most volatile ones. It tracks purchased coins and executes sales based on user-defined Stop Loss and Take Profit settings.

The bot specifically monitors USDT pairs, excluding Margin and Fiat pairs.

Configurable example settings include:

- The bot checks if any coin has increased by more than 3% in the past 5 minutes.
- It buys 100 USDT of the most volatile coins.
- It sells at a 8% profit or a 3% stop loss.
<br><br>

## READ BEFORE USE
1. If you use the `TEST_MODE: False` in your config, you will be using REAL money.
2. To ensure you do not do this, ALWAYS check the `TEST_MODE` configuration item in the config.yml file..
3. This is a framework for users to modify and adapt to their overall strategy and needs, and in no way a turn-key solution.
4. Depending on the current market, the default config might not do much, so you will have to adapt it to your own strategy.

## 💥 Disclaimer

All investment strategies and investments involve risk of loss. 
**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, 
and should not be construed as, a recommendation or as a guarantee of any specific outcome or profit.
By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.
