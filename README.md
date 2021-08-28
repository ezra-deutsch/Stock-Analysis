# VBA of Wall Street

## Overview of Project
 
 VBA of Wall Street is our first foray into writing scripts to perform functions and analyses. Steve has data from the stock market and is trying to compare the different performances of 12 different companies. The metrics analyzed are trade volume, open price, and end price. Steve asked us to write a VBA script to calculate total annual volume and annual returns for 12 different stock tickers for 2017 and 2018. Steve was happy with the first version of our product but also recommended that we refactor the code to make it more efficient and capable of handling more data in the future. In this analysis I will describe the product and the gains in efficiencies.

### Results

The refactoring was a complete success. Code version A used nested loops to perform the analysis on all of the lines of data at once. The refactored code broke up the analysis into separate loops and arrays to more easily store the summarized data. This resulted in an 88% improvement in speed. 

### Code Performance Improvement Stats 
![A_vs_Refactoring_Stats](https://user-images.githubusercontent.com/88510296/131220247-a4a8448c-a7d0-4f02-8a91-36670b6cb89e.png)

### Version A: Returns and Performance
![2017_AllStocks](https://user-images.githubusercontent.com/88510296/131220296-ec94d0d4-b604-4f83-970c-9b56d6354c77.png)

![2018_AllStocks](https://user-images.githubusercontent.com/88510296/131220307-178c0067-2998-4e44-8be4-146f54f6b20d.png)

### Refactored: Returns and Performance
![2017_AllStocks_Refactored](https://user-images.githubusercontent.com/88510296/131220327-b10bb859-5ca2-4135-b3fd-e59169e08b35.png)

![2018_AllStocks_Refactored](https://user-images.githubusercontent.com/88510296/131220336-3f12bb30-8a02-4222-a3b0-e5accebb0a18.png)

### Summary

Refactoring code, in general, has many advantages such as; high chance of enhancement, bug fixing, and peer review. This makes the the time spent on refactoring a worth while time investment. However, in certain circumstances refactoring should not take priorty. Delivery deadlines, higher cost, and code stability should all be considered as disadvantages to refactoring.

Clearly, when viewing the outcome of this VBA scripting exercise, the refactoring advantages outweighed the disadvantages. The refactoring created a product with an 88% faster runtime. The only disadvantage was, perhaps, the number of refactored code lines were reduced by only 4.

Web Link: https://github.com/ezra-deutsch/Stock-Analysis
