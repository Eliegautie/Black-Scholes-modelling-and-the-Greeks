# Black & Scholes modelling

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

For any stable stock, the price is expcected to increase as time progresses. That's why when **T** increase, the option Call value increase steadily and the Put value decrease. Important note, the Put value decrease only after a certain period of time, if **T** is small, the option Put value stay at an certain level. We can deduct from this graph that holding aPut option over a long period of time will not get us any profit.

**Sigma become a variable :**  

If the volatility increases, both Put and Call option values increases. Logical, when sigma is high, the chance for the price to reach the target (S) is higher.

**Black & Scholes modelling with dividend**  

a stock paying dividend will have a lesser value than a stock not paying dividend, it's reflected in the option value  
  

# Financial Greeks  

**Delta:**  

Delta measures the sensitivity of an option's price to movement in the underlying stock (how much the option price moves for every 1% increase of the underlying stock price). In order to write down the formulas, i'm taking the Black & Scholes models with dividends.  

**Theta:**  

The theta of a portfolio of options is the rate of change of the value of the portfolio with respect to the passage of time. Theta is sometimes referred to as the time decay of the portfolio. For a European call option on a nondividend-paying stock, it can be shown from the **Black–Scholes–Merton** formul. Theta is always a negative number (option are a wasting asset), as we get closer to the expiration date of the option, Theta become greater and greater.  

**Vega:**  

Vega is a type of option Greek which is used to compute the sensitivity or rate of change of the value of an option contract with respect to the volatility of the underlying asset. If the Vega is a very high positive or a negative number, this means that the option price is highly sensitive to the volatility of the underlying asset. The Vega is maximum when the option price is at the money.











