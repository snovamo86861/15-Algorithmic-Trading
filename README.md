# Algorithmic-Trading

**Session 15.1 Algorithmic Trading I**

What is Algorithmic trading?

- Algorithmic trading is simply code to decide and  execute a trade(Buy/sell)

**For example:**



 A simple algorith could be to sell 100 shares of a stock when the intraday percentage 
 return of a stock falls below -3%

**CODE**

 A pseudocode snippet for preventing further intraday loss of a stock by selling a stock when the intraday return falls -3%. There is# an assumption that a Stockmarket account has 100 shares of MU.

- Initiate StockMarket accout object

acount = StockMarket()

- Set stock tiker and share size

stock = "MU"

shares = 100


Continuous loop that checks intraday return of a particular stock


while  True:


      # Check intraday return


    intraday_return = account.get_intraday_return(stock)


    # If intraday percentage return falls below -3%, sell the stock and
    # shrare.

    if intraday_return < -0.-3:
       account.sell(shares, stock)



**Why is Algorithmic Trading so Prevalent today?**

- Algorithmic trading is mainly used by institutional investors and big brokerage houses to cut down on costs associated with trading.

- Algorithmic trading also allows for faster and easier execution of orders, making it attractive for exchanges.

- Traders and investors can quickly book profits off small changes in price.

-  The scalping trading strategy commonly employs algorithms because it involves rapid buying and selling of securities at small price increments. (Scalping is a trading strategy geared towards profiting from minor price changes in a stock's price. raders who implement this strategy place anywhere from 10 to a few hundred trades in a single day with the belief that small moves in stock price are easier to catch than large ones; traders who implement this strategy are known as scalpers. Many small profits can easily compound into large gains, if a strict exit strategy is used to prevent large losses.)


- Algorithmic trading can be backtested using historical and real-time data to see if it is profitable 
trading strategy,

- It reduces the possibility of human eror in which traders mistime trades base on emtional and psychological factors.

**Who Performs Algorithmic Trading?**

- Some use  algorithms to help to inform, with the human making the final trade decision.

- Auto pilot 


**BASIC DEFINITIONS**


**Signals:**  Information that is useful for predicting the future
direction of an asset.

**Entery Rules:** A decision rule telling you when to buy an asset(Such  as when a signal reaches a 
pre-specified, high enough level) 


**Exit rules:** Adecision riule telling you when to sell or dispose of an asset(such as when a signal reaches a
pre-specified, low enough level)

- The machine learning model takes in data, outputs a decision.

**Trading signals**

A trading singal is the point at which a technical indicator, such as the crossover of two moving averages
(short MA and long MA).


**What Is a Moving Average?**


A moving average (MA) is a widely used indicator in technical analysis that helps
smooth out price action by filtering out the “noise” from random short-term price
fluctuations. It is a trend-following, or lagging, indicator because it is based on
past prices.


**Trading Signals: Technical indicator**

![Trading image](https://phtradersclub.files.wordpress.com/2016/09/signals-1.png)

A trading signal is the point at which a technical indicator, such as the crossover of two averages (short MA and long MA), suggests an opportunity for action-namely whether an individual trader or algorithmic trading program should issue a buy or sell order for a security(suuch as stock) at the point in time. 

 ***Moving Averages***

- Moving averages "smooth" price data by creating a single flowing line. The line represents the average price over a period of time. Which moving average the trader decides to use is determined by the time frame in which he or she trades. For investors and long-term trend followers, the 200-day, 100-day, and 50-day simple moving average are popular choices.

**There are several ways to utilize the moving average:**


-  The first is to look at the angle of the moving average. If it is mostly moving horizontally for an extended amount of time, then the price isn't trending, it is ranging. If the moving average line is angled up, an uptrend is underway. Moving averages don't predict though; they simply show what the price is doing, on average, over a period of time.

- Crossovers are another way to utilize moving averages. By plotting a 200-day and 50-day moving average on your chart, a buy signal occurs when the 50-day crosses above the 200-day. A sell signal occurs when the 50-day drops below the 200-day. The time frames can be altered to suit your individual trading time frame.

![image](https://www.investopedia.com/thmb/o-DlAlzlHTYRyU6N1feC0cBrWcY=/519x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/indicators-fig_1-5bfd934846e0fb0051d86822)

- When the price crosses above a moving average, it can also be used as a buy signal, and when the price crosses below a moving average, it can be used as a sell signal. Since the price is more volatile than the moving average, this method is prone to more false signals, as the chart above shows.

**MACD (Moving Average Convergence Divergence)**

The MACD is an oscillating indicator, fluctuating above and below zero. It is both a trend-following and momentum indicator. 


One basic MACD strategy is to look at which side of zero the MACD lines are on in the histogram below the chart. Above zero for a sustained period of time, and the trend is likely up; below zero for a sustained period of time, and the trend is likely down. Potential buy signals occur when the MACD moves above zero, and potential sell signals when it crosses below zero.

![image](https://www.investopedia.com/thmb/G08h82SUuG1-stEP2DmdWG6tH2M=/520x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/indicators-fig_3-5bfd93514cedfd0026f4070d)

Signal line crossovers provide additional buy and sell signals. A MACD has two lines – a fast line and a slow line. ***A buy signal occurs when the fast line crosses through and above the slow line.*** *A sell signal occurs when the fast line crosses through and below the slow line.*


