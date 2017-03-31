Pine Script Tutorial - As implemented on tradingview.com

[https://www.tradingview.com/wiki/Pine_Script_Tutorial](https://www.tradingview.com/wiki/Pine_Script_Tutorial)  

There are two types of scripts
- Indicator Scripts
    - A standard pine script is an indicator. Use it to read the a series {open, high, low, close, volume} which can be accessed by subscript [] in reverse chronological order from the present.
    
- Strategy Scripts
    - A strategy is a study that can send, modify and cancel orders (to buy/sell). Strategies allow you to perform backtesting (emulation of strategy trading on historical data) and forwardtesting (emulation of strategy trading on real-time data) according to your precoded algorithms.
      - When you write a strategy code, it should start with the keyword “strategy”, not “study”. 
      - strategy.entry
      - strategy.exit
      - strategy.order

Goals 
- One goal is to draw top-of-value bottom-of-value virgin-points-of-control on any chart.
  - One order to do that we need to know what the units of the chart are.
    - Calculating tov/bot/vpoc will be better performed on a 15minute unit chart calculated by the day.
  - Can pine scripts know the price volume distribution? 
    - Not currently. [https://getsatisfaction.com/tradingview/topics/volume-profile-values-in-pine-script](https://getsatisfaction.com/tradingview/topics/volume-profile-values-in-pine-script)

- One goal is to calculate the "saucy" moment, as I'll describe herein and hopefully scribe into PineScript.
  - Daily is the most important unit for secret sauce moments.
  - The saucy moment is when the a stock which has broken out and is trading above the rising 50/150/200 has a bullback to the point where it grazes the rising 50.

