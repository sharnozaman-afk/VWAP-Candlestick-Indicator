# VWAP-Candlestick-Indicator
Project Overview
This project uses Python to calculate and visualize the Volume Weighted Average Price (VWAP) alongside candlestick charts. It combines Python 
programming, financial market analysis, and data visualization to better understand how trading activity influences price behavior.

Key Features
Calculates typical price using high, low, and closing prices
Computes cumulative price-volume and total trading volume
Calculates VWAP across multiple trading periods
Visualizes candlestick charts with a VWAP overlay

What I Learned
Throughout building this project, I learned a lot more about VWAP and the market concepts connected to it. For instance, VWAP is the average traded price weighted by volume. It serves as a benchmark for institutions to evaluate whether their orders were executed at a favorable price. For a buying institution, getting executed above VWAP means paying a more expensive price relative to the average, while getting executed below VWAP means purchasing at a cheaper price.

An important distinction is that price crossing VWAP does NOT necessarily mean you should immediately buy or sell. Instead, you would also look at order flow, volume, and delta. Is the price moving higher because there are a lot of aggressive buyers? Are sellers able to absorb that buying pressure? A crossover above or below VWAP simply tells you where price is trading relative to its volume-weighted average. It does not necessarily predict where price will move next.

There is also a common misconception that institutions always buy at VWAP. One of the most important fundamentals I am learning while studying market microstructure is that prices move because different market participants have different objectives and constraints. For example, one institution might have an algorithm that only buys shares relatively close to VWAP, while another institution might believe that SPY is currently undervalued below its VWAP and decide to buy. One institution prioritizes execution performance, while the other focuses on purchasing shares when the price reaches a level it considers attractive. Both institutions are participating in the same market, but their decisions are driven by different objectives.

Furthermore, in a balanced market, price may move above or below VWAP before returning toward its average. Mean reversion is a possibility in balanced markets, but VWAP is not a magnet that price must continuously return to. In a directional uptrend, buyers may be willing to accept increasingly higher prices, causing prices to remain above VWAP rather than reverting toward it.

In addition, one feature I would like to add to my project is standard deviation bands. Standard deviation measures how far values are spread out from their average. VWAP standard deviation bands are particularly useful because they show how far price has moved from VWAP relative to the session's price dispersion, often using bands at one and two standard deviations. These bands can provide additional context about volatility and whether price is trading relatively far from its average. If we know that historically price tends to trade 68% between the normal one standard devation and price naturally is going to bounce back and forth we can then manage risk and also see how the markt reacts when price is above that one standard deviation. 
