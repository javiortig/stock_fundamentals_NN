#**US STOCK NEURAL NETWORK BASED ON FUNDAMENTAL ANALYSIS**  

---  
        
## A bit of background:
As a young computer science student and a [value investor][1] in the stock market, I always wondered if at some point I could do some research to fuse those different worlds in a fresh new project. Thats when I bumped into the world of machine learning, then deep learning, and now Neural Networks. Let me introduce to the new predicting model: *Cuberta*.

## Project Setup:
*Cuberta* consist in a multi-layered Neural Network that looks forward predicting the average stock price growth and the [dividend yield][2] of a company the next fiscal year, based on a series of fundamental stock analysis ratios.
In order to keep everyone in track, lets leave an example:  

In 2019, IBM had an average price of 126\\$ per stock.  
In 2020, IBM had an average price of 114\\$ per stock, with a dividend yield of 0.052.
The aim of *Cuberta* is to predict(the Y or Labels) the average stock price growth from 2019 to 2020 was 114/126=0.9047(which is actually degrowth) and a diviend yield of 0.052 per stock.

As many readers will know, playing with $X \in[-1, 1]$ rather than $X\in{\Bbb R}$ is, in general terms, a better idea for working with this type of algorithms, and that's what we will aim for.


[1]: https://en.wikipedia.org/wiki/Value_investing
[2]: https://en.wikipedia.org/wiki/Dividend_yield
