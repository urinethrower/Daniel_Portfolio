# Daniel_Portfolio
Project portfolio
  
# [Algorithmic Trading Bot / Expert Advisors:](https://github.com/urinethrower/Project-Deities)
* Developed 3 trading strategies navigating various markets including forex, stock indices, precious metals and Bitcoin (CFDs)
* Backtested over 1000 single-criteria trading systems, and customised over 20 algorithms from existing indicators
* Strategies including trend-following, confluence trading, grid trading (without Martingale)
* Risk management system is implemented virtually to avoid stoploss hunting or other broker manipulations
* Advanced features including: hedging, equity curve trading, trade filters, dashboard, etc.
* Created a dynamically linked library (.dll) to handle loop-intensive functions on C++ (e.g. real-time optimisations) and return values to main bot
  
<img src="https://github.com/urinethrower/Project-Deities/blob/main/img/Demeter_snapshot.JPG" alt="https://github.com/urinethrower/Project-Deities/blob/main/img/Demeter_snapshot.JPG" width="668" height="417"></img>  
  
# [Classic Titanic Dataset with a C++ twist:](https://github.com/urinethrower/Project-Titanics)
* This is a feasibility study towards leveraging machine learning models in quantitative trading in the future
* Random forest model was chosen mainly because of its generally lower risk of over-fitting for small datasets, and it is great for performing feature-based analysis
* Classic Titanics dataset is used for simplicity, 89% accuracy was recorded after minimal tuning hyper parameters
* Model is first built in R, output to flat file, embedded to C++, compiled as `.dll` and imported into MQL4
* Applying multi-threading to further speed up the execution on C++
  
![ntrees](https://user-images.githubusercontent.com/106392189/171839711-84ca8a9b-58d0-457f-ac22-7ef443f000e5.png)
![mtry](https://user-images.githubusercontent.com/106392189/171839746-6ba82794-5425-471a-842e-9f25d27a1173.png)
  
