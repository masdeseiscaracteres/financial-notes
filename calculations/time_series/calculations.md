# Time series calculations

* Statistics

  * Performance

    * Total return

    * Average return

  * Risk
  
    * Standard deviation
    
    * Value at Risk (VaR)
    
    * Expected shortfall
       
       Also known as Conditional Value at Risk (CVaR), Average Value at Risk (AVaR), and expected tail loss (ETL).
    

  * Trade-off

* Anualized statistics

* Rolling statistics

## Drawdown

The drawdown is a measure of the decline of a time series from its historical peak. Given a time series $$x_t$$, the drawdown at time $$t$$ is defined as:


$$
\operatorname{DD}(t) = \max_{\tau \in [0,t]}(x_\tau-x_{t})
$$


### Maximum drawdown

The maximum drawdown in the interval $$[0,T]$$ is, therefore, calculated as:


$$
\operatorname{MDD}(T)=\max_{t\in [0,T]} \operatorname{DD}(t)
$$


##### References

Magdon-Ismail, Malik et al. _On the Maximum Drawdown of a Brownian Motion._ Journal of Applied Probability, vol. 41, no. 1, 2004, pp. 147–161. [www.jstor.org/stable/3215821](http://alumnus.caltech.edu/~amir/drawdown-jrnl.pdf)

## Drawdown duration

Time duration of the drawdown period.

