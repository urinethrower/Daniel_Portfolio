# Daniel_Portfolio
Project portfolio
  
# [Algorithmic Trading Bot / Expert Advisors:](https://github.com/urinethrower/Project-Deities)
* Developed 3 trading strategies navigating various markets including forex, stock indices, precious metals and Bitcoin (CFDs)
* Backtested over 1000 single-criteria trading systems, and customised over 20 algorithms from existing indicators
* Strategies including trend-following, confluence trading, grid trading (without Martingale)
* Risk management system is implemented virtually to avoid stoploss hunting or other broker manipulations
* Advanced features including: hedging, equity curve trading, trade filters, dashboard, etc.
* Created a dynamically linked library `.dll` to handle loop-intensive functions on C++ (e.g. real-time optimisations) and return values to main bot
  
<img src="https://raw.githubusercontent.com/urinethrower/Project-Deities/main/img/Demeter_snapshot.JPG" alt="https://raw.githubusercontent.com/urinethrower/Project-Deities/main/img/Demeter_snapshot.JPG" width="668" height="417">  
  
# [Random forest model on Titanics dataset: R modelled, C++ executed](https://github.com/urinethrower/Project-Titanics)
* A feasibility study towards leveraging machine learning models in quantitative trading in the future
* Random forest model was chosen mainly because of its generally lower risk of over-fitting for small datasets, and it is great for performing feature-based analysis
* Classic Titanics dataset is used for simplicity, 89% accuracy was recorded after minimal tuning hyper parameters
* Model is first built in R, output to flat file, embedded to C++, compiled as `.dll` and imported into MQL4
* Applying multi-threading to further speed up the execution on C++
<div>  
<img src="https://user-images.githubusercontent.com/106392189/171841472-1ef4d16e-7a55-4171-a61a-f2797e2e7fa0.png" alt="https://user-images.githubusercontent.com/106392189/171841472-1ef4d16e-7a55-4171-a61a-f2797e2e7fa0.png" width="410" height="397">
<img src="https://user-images.githubusercontent.com/106392189/171841501-3398e479-3406-4085-a0d0-7fc7933f2a8e.png" alt="https://user-images.githubusercontent.com/106392189/171841501-3398e479-3406-4085-a0d0-7fc7933f2a8e.png" width="367" height="397">
</div>
  
