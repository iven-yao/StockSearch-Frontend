# Stock Search
developed with Angular, data from finnhub.io 

# Updates
- Partial api calls not available (12/31/2023)
  
  social-sentiment and stock candles are not available on finnhub now, remove associated part, (sentiment table and candle chart)

# Functions
- search by stock ticker, search bar has autocomplete feature and debouncing
- show detail and real-time updated stock price (update with every 15 seconds)
- show ~~historic stock price charts~~(deprecated), associated peer stock (and linked to its detail page), company related news
- mock trading feature with real-time price, starting with $25,000 in your mocking-wallet
- watchlist with localstorage, so you can view all the stocks you are interested in in one page 

# Host on Vercel
https://stock-search-frontend-smoky.vercel.app/
