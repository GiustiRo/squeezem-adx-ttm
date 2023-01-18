# squeezem-adx-ttm
PineScript @4 that combines indicators: Squeeze Momentum + ADX + Trade The Market Waves (Inspired by Jhon Carter & Jaime Aibsai).

### Use it:
You can search for this Indicator directly on Trading View's Chart view, or searching on my TV profile: 
https://es.tradingview.com/u/rolgui/#published-scripts

The content of 'script' file must be placed on Trading View's Pine Script editor to be used.

![image](https://user-images.githubusercontent.com/39607414/213170812-72b8f6c4-c5df-48a4-9fda-03aabc3d7883.png)

### About this indicator:
This indicator aims to combine two good performing strategies, which can be used separately or together, mainly for investment positions, although it can also be used for intraday trading.

Strategy 1) Squeeze Oscillator and Average Directional Index:
This strategy is taught by Jaime Aibsai, which determines market entries based on reading the direction of the price movement (Directionality of the Oscillator) along with the strength of the Oscillator (Slope of the ADX ).

Both tools are configured according to Jaime Abisai's strategy, by default (note that point 23 of the ADX is represented by point 0 on the panel, to make reading easier, its interpretation is not affected). Anyway you can adjust the input data according to your interest.

*You can see this setting in the first panel.

Strategy 2) Squeeze Momentum and Trade The Market Waves:
This strategy can be consulted either in John F. Carter's books or on his website.

This market reading is based on Price Volatility ( Bollinger Bands and Keltner Channels interaction) and its Trend (Exponential Moving Averages), showing entries at times when price volatility is low and taking filtering active trend using T.T.M. Waves.

To configure the indicator in the same way that Carter does, it would be enough to turn off the ADX , turn on the Squeeze Momentum signals along with the T.T.M. Waves, and importantly, change the Linear Momentum value to 12 (this configuration can be found in his book).

*You can see this setting in the second panel.

Why this indicator?
I've added and removed the above flags as I needed to query them (which became tedious for me). The main objective of having merged them into one is to make their reading more agile and comfortable and thus improve the decision-making capacity of the trader who wishes to use them.

Credits and Acknowledgments:
I would like to give credits to other authors, for the sections of code that I have used to make this technical indicator. Thanks to @LazyBear, @futura_matt, @jombie and @joren for contributing to the community and keeping their code open. It is priceless!

Feel free to combine and practice your trading with both strategies, personally, they improved my profitability and this is why I recommend researching more about them. I've been using it for crypto investing, let me know if it's worth for you on stock market!
Enjoy.
