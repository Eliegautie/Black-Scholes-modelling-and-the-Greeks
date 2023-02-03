# Black & Scholes modelling

*Ressources:*  
- Udemy class 'Mathematical Finance with Python' : https://www.udemy.com/
- SimTrade blog - Options Greeks : https://www.simtrade.fr/blog_simtrade/option-greeks-theta/
- SimTrade blog - Options Greeks : https://www.simtrade.fr/blog_simtrade/option-greeks-vega/


**Black & Scholes modelling :**

- N() = cumulative distribution function 

- T = time left til' maturity (in years)

- S = underlying stock price  

- K = strike price  

- r = risk free rate  

- sigma = volatility of the underlying stock  


In the first graph, we can see a relationship between **S** and the values of the Call and Put. When **S** increases, the value of the Call increases and the value of the Put decreases and vice versa.  

If i buy a Call option with a strike price **K** at the money or in the money (meaning that at the time of the purchase **S** = **K** or **S** > **K**), if S increases the profit I can make from exercising my option increases 

If I buy the Call out of the money (**K** > **S**), as S gets closer to K, my Call option increases in value. 


**T become a variable :**  

For any stable stock, the price is expected to rise over time. Therefore, as **T** increases, the value of the call option steadily increases and the value of the put option decreases. The value of the put option only decreases after a certain period of time, so if **T** is low, the value of the put option remains at a certain level. We can deduce from this graph that holding a put option for a long period of time will not bring us any profit.

**Sigma become a variable :**  

If volatility increases, the value of the call and put options increases. High volatility means that S has a high chance of going up, beneficial if you hold a call option, or a high chance of going down, beneficial if you hold a put option.

**Black & Scholes modelling with dividend**  

Same formula, but we incorporate the dividend. We can clearly see from the graph that a stock that pays a dividend will have a lower value than a stock that does not pay a dividend. This is reflected in the value of the option
  

# Financial Greeks  

**Delta:**  

The delta measures the sensitivity of an option price to movements in the underlying stock (how much the option price changes for every 1% increase in the price of the underlying stock). To write the formulas, I use the Black & Scholes model with dividends. 

**Theta:**  

The theta of a portfolio of options is the rate of change of the value of the portfolio with respect to the passage of time. Theta is sometimes referred to as the time decay of the portfolio. For a European call option on a nondividend-paying stock, it can be shown from the **Black–Scholes–Merton** formul. Theta is always a negative number (option are a wasting asset), as we get closer to the expiration date of the option, Theta become greater and greater. 

Ps : if you look up the link https://www.simtrade.fr/blog_simtrade/option-greeks-theta/, when the author give an example for calculating theta, he found a value of -0.2636 per trading day, or when i do my calculation i found -0.0381 per trading day, even if my formula gives the same result as in his excel file (pricer option). Maybe I'm wrong, if you find the same result as him, let me know! 

**Vega:**  

Vega is a type of option Greek which is used to compute the sensitivity or rate of change of the value of an option contract with respect to the volatility of the underlying asset. If the Vega is a very high positive or a negative number, this means that the option price is highly sensitive to the volatility of the underlying asset. The Vega is maximum when the option price is at the money.











