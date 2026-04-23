# Data scientist

### Education
Math-statistics, Bachelor 

### Experiences
  HCD Summer Lab Designed 
  - An educational intervention using human-centered design to engage K–8 students in learning about native plants and boosting academic achievement.
  - Collaborated in an interdisciplinary team to design solutions grounded in user research and empathy driven methods.

### Projects
  STATISTICAL MODELING OF ADULT DEPRESSION PREVALENCE USING BOOTSTRAP METHODS
  - Analyzed California Behavioral Risk Factor Surveillance System (BRFSS) data to examine gender differences in depression prevalence
  - Estimated population-level differences using sample mean and median estimators
  - Implemented bootstrap resampling (B = 5000) in R to evaluate estimator variability
### Project ideas
  - Stock: trend analysis
      - "How does stock price volatility vary over time, and are there periods of unusually high or low risk?"
      - "Do major events correspond to significant changes in stock price behavior?"
  - Personal screen time analysis
      - "How does school work affect my screen time?"
      - "Does more screen time before bed affect sleep quality?"
  - Movie ratings & trends
      - "How have movie ratings changed over time, and are there trends across different genres?"
      - "How has the relationship between movie ratings and box office revenue changed over time?"

### Week 10 update
- I will be working on my own
- The general topic will be about stock market. Maybe about predictions?
- I may use data from yahoo.
    - Pros: Free access, wide data coverage, long historical data, simple structured
    - Cons: Might be limited, the API is likely not officially supported？， would need a lot data cleaning
 
Questions: ( I haven't decide which stock market I would like to ecplore more yet, here are ssome of my thoughts)
 - How does stock price change over time? Example: How has Apple (AAPL) stock price changed over the past 5 years?
 - How are two stocks related to each other? Example: What is the relationship between Tesla (TSLA) and S&P 500 returns?
 - How does stock performance differ across time periods?Example: Is stock return higher in summer vs winter months?

### Project Update - Week 11
- I decided to work with Yahoo Finance stock data and focus on Apple (AAPL) stock prices. I chose this data source because it is easy to access, provides historical stock information such as daily opening price, closing price, highest and lowest price, and trading volume. Apple is a really big company, which makes it a good choice to explore trends over time.
- I was able to obtain the data using Python in Google Colab with the yfinance package, which pulls historical stock data from Yahoo Finance. I downloaded the apple historical stock data from Yahoo finance. And store it in pandas for analysis.
- I inspected the dataset, checked the variables, and created visualizations. The question I want to focus on is 'Can moving averages help identify major trend changes in Apple stock prices over the study period?'
- From my preliminary exploratory analysis, I learned that Apple’s stock price generally increased over the study period, although there were still noticeable short-term ups and downs. The moving averages helped smooth out the daily fluctuations and made the broader trend easier to see. In particular, the 20 day moving average showed short term movement more quickly, while the 50 day moving average showed the longer term direction of the stock. Looking at the graph, it seems that moving averages do help identify major trend changes more clearly than the raw daily closing prices alone.
- I imported the data into Colab, checked that the dates were in the correct format, and made sure the stock price variables were usable for plotting and analysis. I then created additional variables, including the 20 day moving average and 50 day moving average, to support my research question.
- The challenge is that stock prices has many short term fluctuations that may make patterns harder to interpret. Another challenge is that moving averages are useful for showing trends, but they may miss sudden changes or lag behind real price movement. The project currently relies on only one company, so the findings may not generalize to the stock market as a whole. 
