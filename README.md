# Markowitz-Model
This project is a Python implementation of Markowitz's Portfolio Optimization Model. 
The aim is to create a portfolio containing stocks of the FAANG companies: FB, AAPL, AMZN, NFLX, GOOG.

The portfolio is to be optimised in such a way that highest return is achieved for a given risk. 

The historical data of the stock prices for the last 10 years is fetched from [Yahoo! Finance](https://finance.yahoo.com/) using the yFinance library. The data looks as follows:

|    Date    |        FB   |      AAPL  |       AMZN  |      NFLX  |       GOOG   |
| ---------- | ----------- | ---------- | ----------  | ---------  | ----------   |        
| 2011-01-03 |        NaN  | 10.063868  | 184.220001  | 25.487143  | 301.046600   |
| 2011-01-04 |        NaN  | 10.116389  | 185.009995  | 25.910000  | 299.935760   |
| 2011-01-05 |        NaN  | 10.199140  | 187.419998  | 25.675714  | 303.397797   |
| 2011-01-06 |        NaN  | 10.190897  | 185.860001  | 25.427143  | 305.604523   |
| 2011-01-07 |        NaN  | 10.263881  | 185.490005  | 25.614286  | 307.069031   |
| ...        |        ...  |       ...  |        ...  |       ...  |        ...   |
| 2021-12-27 | 346.179993  | 179.836319 | 3393.389893 | 613.119995 | 2961.280029  |
| 2021-12-28 | 346.220001  | 178.799164 | 3413.219971 | 610.710022 | 2928.959961  |
| 2021-12-29 | 342.940002  | 178.888916 | 3384.020020 | 610.539978 | 2930.090088  |
| 2021-12-30 | 344.359985  | 177.712143 | 3372.889893 | 612.090027 | 2920.050049  |
| 2021-12-31 | 336.350006  | 177.083878 | 3334.340088 | 602.440002 | 2893.590088  |

The comparative chart of the stock prices of the five companies is as follows:


