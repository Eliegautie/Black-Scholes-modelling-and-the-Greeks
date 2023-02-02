# Black & Scholes modelling for financial Greeks

All the content you will find there come from the Udemy class 'Mathematical Finance with Python'.

I decided to take this course in order to improve my coding on Jupyter Lab, and also because these tools are very useful when dealing with options.

**Black & Scholes modelling : from the B&S mathematical equation, i gave the formula for a Call and a Put :**

- N() = cumulative distribution function 

- T = time left til' maturity (in years)

- S = underlying stock price  

- K = strike price  

- r = risk free rate  

- sigma = volatility of the underlying stock  


In the first graph, we can see a relation bewteen **S** and the call and put values. When **S** increseas , the Call value increase and the Put value decrease and inversely.  

If we bought a call option with a strike price X at the money or in the money (meaning that at the time of the purchase **S** = **K** or **S** > **K**), if S increases we make money. 

If we bought the Call out of the money (**K** > **S**), same result but we make money when **S** surpasse **K**.   


**T become a variable :**  

For any stable stock, the price is expcected to increase as time progresses. That's why when **T** increase, the option Call value increase steadily and the Put value decrease. Important note, the Put value decrease only after a certain period of time, if **T** is small, the option Put value stay at an certain level.   
We can deduct from this graph that holding aPut option over a long period of time will not get us any profit.




