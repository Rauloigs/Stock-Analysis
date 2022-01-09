# stock-analysis

## 1. Overview of Project
Steve wants to be able to do the analysis over different years, but he also wants to be able to use our program to go through whatever number of stocks when it is necessary, so he can introduce his parents to better options of stocks.

Now it´s time to refactor the code and loop through all data, collect the same information and additionally determine if the refactored VBA script runs faster than the non-refactored. 


## 2. Results

We are reviewing to general results. The first one is **the comparisson of the stock performance between 2017 and 2018**, and the second one is the **execution times among the origanl spcript and the refactored one**. 

### 2017 vs 2018 Stocks

In 2017 all stocks except TERP had positive outcome regarding their return investment. form 5.5%& up to 199.4%. This last one was DQ which is the start up which Steve´s parents wanted to initially invest in. This could be attributed to the initial public offering (IPO) of the company, which it commonly generates high expectations in investors and therefor its value tends to inflate. Probably in 2018 it can tend to an equilibrium point. 

<img width="224" alt="2017" src="https://user-images.githubusercontent.com/84519822/148663408-1f4e0427-fe58-45cc-8b78-77ed9aeb9fa4.png">


During 2018 all stocks excepting ENPH and RUN gave a positve return of 81.9% and 84.0% respectively. The rest performed from -3.5 down to -62.6. In this year DQ, had the worst performance of them all, though as its being mentioned before in this analysis, it may be the consequence of a stock expectation deflating or finding its equilibrium point. 

<img width="225" alt="2018" src="https://user-images.githubusercontent.com/84519822/148663405-d860033b-dbe6-4b81-9475-28bac55f6c34.png">

Some important considerations about this analysis for investment is that we are seeing highly volatile stocks. This could be attirbuted to the trend their market (green stocks) or of their status within time (start-ups). It might be a bet with very high or low rewards. 

### Executing Time Results

The refactored code performed simply faster as shown in the image below: 

<img width="290" alt="Refactored" src="https://user-images.githubusercontent.com/84519822/148663031-c1cabb04-7c7e-4214-8673-7935c8643f97.png">

The original outcome was the following: 

<img width="278" alt="Not_Refactored" src="https://user-images.githubusercontent.com/84519822/148663036-71fe3a4d-ef4e-4954-a33b-d7a0d48badac.png">

We can easily observe a clear reduction in time when refactoring.

## 3. Summary

### What are the advantages or disadvantages of refactoring code?

Advantages: 
1. You can probably use it for the same application but with a greater scope. 
2. You can approach to something specific with something general. So in other words, with something general you approach to many specific situations. 

Disadvantage: 
1. I takes time and two *Office Hours* to make it happen. 
2. Just kidding (sorry if not funny). You can get lost, because you use a little bit more variables and less specific names for the variables. Which means you need to be conscious of were those variables / principles are going to be refected.   

### How do these pros and cons apply to refactoring the original VBA script?

- Now we can use this code for whatever year, whatever stocks. 
- At least me. I got pretty lost when using the tickersIndex(i), for me (a very beginner), using arrays instead of just keys of names was more difficult. 

If you think you are missing something to check from my Challenge, please click here: https://github.com/Rauloigs/stock-analysis
