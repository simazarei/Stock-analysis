# Green Energy Stocks Analysis
## Overview of Project
Steve wants to help his parents to invest in stock market. They are passionate about green energy that is why they are willing to invest their fund in green energy stocks. They have not done enough research on stocks market and want to invest all their money in _DAQO_ (_DQ_) stocks based on their experience with _Dairy Queen_ (totally irrelevant). The purpose of project is to help Steve by analyzing the stocks market of green energy to see whether _DAQO_ is the best option to invest all available fund in it, or it is better to diversifying the available fund between other green energy stocks.
## Results of Stock Performance Analysis
### Stock Performance for 2017
Comparing the Return rate of different stocks in _2017_, almost all green energy stocks (except _TERP_ with -7.2% return rate) had a higher stock appreciation by end of _2017_ and some of them such as _DQ_, _ENPH_, _FSLR_, and _SEDG_ even returned gains having average annual returns of more than 100% of the initial start of year stock price. In terms of liquidity all the stocks seem to have a large volume of shares traded in _2017_. With considering both return and daily volume of shares traded in only _2017_, it seems to be logical to invest in green energy stocks, and investors would gain an average more than 60% of their shares.
### Stock Performance for 2018
However, in _2018_ the return rate for almost all the stocks depreciated, which shows instability, fluctuation and high rate of risk for investors in this industry stocks. In the case of _DQ_, even though the daily volume of shares traded increased by almost 3 times, the return rate of -62% which is the lowest of all, does not seem to be a good investment for investors and Steve's parents. Although for _ENPH_ after dropping the return rate from 129% to 81% and for _RUN_ increasing from 5% to 84% also appreciation in daily volumes between years of _2017_ to _2018_, they seem to be a better fit to invest in green energy stocks.
### Stock Performance Analysis Conclusion 
By comparing each ticker between _2017_ and _2018_, it would be realized that the daily volume of each ticker is not a reliable factor to analyze the stock market. In addition, to fully understand the stock market, a year of data can not be sufficient. For instance, in this Data Set based on the daily volumes and return rates in _2017_, green energy stocks seem to be a great investment, but after _2018_ data added to the analysis process we can clearly recognize that the fluctuation of the return rate for most of the stocks and daily volumes for some of them the green energy stocks is not a stable market to invest all Steve's parents' fund. 
## Time Execution Analysis
The execution time for _Original Script_ of VBA for _2017_ is _1.19_ seconds and in _2018_ it is _1.19_ seconds. But _Refactored Script_ for _2017_ and _2018_ ran in _0.15722_ and _0.16113_ seconds respectively, which shows code refactoring can be beneficial in terms of **time**. 

**Figure 1**: Time execution and Stock Performance for _2017_ in Refactored Script

![](Resources/VBA_Challenge_2017.png)

**Figure 2**: Time execution and Stock Performance for _2018_ in Refactored Script

![](Resources/VBA_Challenge_2018.png)


## Advantages and Disadvantages of refactoring code
### Advantages
1) The Macro runs faster after refactoring the script.
2) It is more organized, readable, and easier to find the reason behind each line of code 
3) It makes the script maintainable and less expensive for future adjustments
### Disadvantages
1) In big Data it can be risky and expensive 
2) It may cause bugs in the script
3) It may be time consuming to refactor code scripts written by someone else
## Pros and Cons of refactoring the original VBA script
Pros to be mentioned for refactoring is that by adding tickerIndex to the script it prevents Macro from having duplicated variables and reduces the number of times that the script is running the loop throughout the Worksheet. By adding more detail to each line of the script we increased the maintainability of the script.
Refactoring the original VBA script has its own coms too first one is that it was time consuming and we wrote all the detail and reason behind each line of VBA script, it caused some bugs in the script while refactoring it. By reducing duplicated variables and adding tickerIndex the script became more complicated and harder to understand for further maintenance for people with lower knowledge of VBA.
