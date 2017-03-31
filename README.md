Pine Script Tutorial - As implemented on tradingview.com

[https://www.tradingview.com/wiki/Pine_Script_Tutorial](https://www.tradingview.com/wiki/Pine_Script_Tutorial)  

There are two types of scripts
- Indicator Scripts
    - A standard pine script is an indicator. Use it to read the a series {open, high, low, close, volume} which can be accessed by subscript [] in reverse chronological order from the present.
    
Strategy Scripts
    - A strategy is a study that can send, modify and cancel orders (to buy/sell). Strategies allow you to perform backtesting (emulation of strategy trading on historical data) and forwardtesting (emulation of strategy trading on real-time data) according to your precoded algorithms.
      - When you write a strategy code, it should start with the keyword “strategy”, not “study”. 
      - strategy.entry
      - strategy.exit
      - strategy.order

Goals 



