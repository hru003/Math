
## <span style="color:#00b0f0">Distributions</span>

- The idea of distributions is to assign probabilities to each of the individual outcomes in the sample space.
- It gives us the sense of how the probabilities are distributed over the outcomes.
	- Example
		- Rolling a die: S = {1,2,3,4,5,6}
		- If the die is fair, then pi = 1/6 ; i = 1, 2, 3, 4, 5, 6
		- 



## <span style="color:#00b0f0">Random Variable</span>

- A random variable is a quantitative variable whose value depends on chance.
- It is a function that assigns a real number to each sample in S.
- An example of a random variable would be tomorrow’s high temperature.
- Continuous Random Variable - Weight
- Discrete Random Variable - Score
- 

### <span style="color:#00b0f0">Discrete Random Variable</span>

- A discrete random variable is a random variable whose possible values can be listed i.e. finite.
- P(X = x) denotes the probability that the random variable X equals x.
- <span style="color:#ffff00">Probability distribution:</span> A listing of the possible values and corresponding probabilities of a discrete random variable, or a formula for the probabilities.
- <span style="color:#ffff00">Probability histogram:</span> A graph of the probability distribution that displays the possible values of a discrete random variable on the horizontal axis and the probabilities of those values on the vertical axis.

- Calculating Mean and Variance for Random Variables
	- ![](images/Pasted%20image%2020231201140209.png)   ![](images/Pasted%20image%2020231201140230.png | 600x100)  

	- The mean/Expectation of a discrete random variable X is denoted $μ_X$ or μ. It is defined by μ = $\sum x* P(X = x)$.
	- ![](images/Pasted%20image%2020231201163052.png)    x = Number of siblings
	- The standard deviation of a discrete random variable X is denoted $σ_X$. It is defined as σ = $\sqrt \sum (x − μ)^2 * P(X = x)$
	- For the above problem sd = 4.6.
	
	- Compute the mean, sd for the following data.
		- ![](images/Pasted%20image%2020231207163101.png)
		- mean = 3.7, sd = 1.61
#### <span style="color:#e538c0">Bernoulli Distribution</span>

- A discrete probability distribution wherein the random variable can only have 2 possible outcomes is known as a Bernoulli Distribution.
- ![](images/Pasted%20image%2020231201165207.png)
- P(x) = $p^{x}* (1-p)^{1-x}$ 
- mean = p and sd = $\sqrt p * (1-p)$ 
- ![](images/Pasted%20image%2020231203141956.png)
- Examples
	- A newborn child is either male or female. 
	- You either pass or fail an exam.
	- A tennis player either wins or loses a match.
	- A basketball player can shoot a ball into the basket with a probability of 0.6. What is the probability that he misses the shot? => 1-06 = 0.4
	- 

#### <span style="color:#e538c0">Binomial Distribution</span>

- Many applications of probability and statistics concern the repetition of an experiment. We call each repetition a trial. The trial has 2 outcomes.
- Testing the effectiveness of a drug
- Weekly sales of a car salesperson
- The binomial coefficient (n x) is defined as (n x)  = $\frac{n!} {x! * (n − x)!}$.
- (6 1) = 6, (5 3) = 10, (7 3) = 35, 
- The binomial distribution is the probability distribution for the number of successes in a sequence of Bernoulli trials.
	- Bernoulli Trials has 2 outcomes
	- Bernoulli Trials are independent
	- Bernoulli Trials are same success of probability
- The binomial probability formula for the number of successes, X, is P(X = x) = (n x) * $p^x$ $(1 − p)^n−x$.
- The mean and standard deviation of a binomial random variable with parameters n and p are μ = np and σ = np(1 − p), respectively.
- ![](images/Pasted%20image%2020231201164257.png)
	- n = 3, p = 0.8
	- P(X = 2) = 0.384
	- P(X ≤ 1) = P(X = 0) + P(X = 1) = 0.104
	- P(X ≥ 1) = P(X = 1) + P(X = 2) + P(X = 3) = 0.992
	- P(X = 3) = 0.512
	- Plot the distribution
	- mean = 2.4, sd = 0.7

- A particular college at which 60% of the student population is female.
	- Calculate the probability that a class of 10 students will have exactly four females. => n = 10, x = 4, p = 0.6 and P(4) = 0.1115
	- Calculate the probability that a class of 10 students will contain five, six, or seven females. => ![](images/Pasted%20image%2020231207165410.png)
	- Calculate the mean, variance, and standard deviation for this distribution. => 6, 2.4, 1.55
#### <span style="color:#e538c0">Geometric Distribution</span>

- Models the number of trials required to achieve the first success in a sequence of independent Bernoulli trials.
- ![](images/Pasted%20image%2020231207180347.png)
- mean = 1 / p and variance = (1-p) / p^2
- 
#### <span style="color:#e538c0">Poisson Distribution</span>

-  Poisson distribution is used to estimate how many times an event is likely to occur within the given period of time.
- $f(x) = P(X=x) = \frac{(e^{-λ} * λ^x )} {x!}$ , where e = 2.718
- E(X) = V(X) = λ = n * p
- ![](images/Pasted%20image%2020231207170408.png) 
- Examples
	- The number of cars that pass through a tollbooth during one hour 
	- In a cafe, the customer arrives at a mean rate of 2 per min. Find the probability of arrival of 5 customers in 1 minute using the Poisson distribution formula. => P(X = 5) = 0.036
	- If 3% of electronic units manufactured by a company are defective. Find the probability that in a sample of 200 units, less than 2 bulbs are defective. => P(X < 2) = P(X = 0) + P(X= 1)
	- The average number of tickets issued per month conforms to a Poisson distribution with an average of 3.7. 
		- Calculate the probability that exactly five traffic tickets will be issued next month. Substitute Q = 3.7 and x = 5. P(5) = 0.1429
		- Calculate the probability that no more than two traffic tickets will be issued next month. ![](images/Pasted%20image%2020231207164848.png)
		
### <span style="color:#00b0f0">Continuous Random Variable</span>

- A density curve represents the distribution of a continuous variable.
- Total Area of the density curve = 1.
- 
#### <span style="color:#e538c0">Uniform</span>

- A uniform distribution is defined by two parameters, a and b, where a is the minimum value and b is the maximum value.
-  It is generally denoted as u(a, b) = $\frac{1}{b-a}$ for $a≤ x ≤b$
- mean = $\frac{a+b} {2}$ and sd = $\sqrt\frac{(b-a)^2}{12}$ .
- For the conditional probability = P( c < x < d ) = $\frac{(d – c)} {(b – a)}$ 
- Using the uniform probability density function for random variable XX, X ~ (0,23), find P(2<X<18). => 18/23
- Using the uniform distribution probability density function for random variable X, in (0, 20), find P(3< X < 16). => 13/20
- A vending machine dispenses coffee in amounts that vary uniformly between 7.4 and 8.2 ounces per cup.
	- Calculate the probability that the next cup of coffee purchased will contain between 7.5 and 7.8 ounces. => 0.375
	- Calculate the probability that the next cup of coffee purchased will contain between 7.6 and 8.0 ounces. => 0.5
#### <span style="color:#e538c0">Normal</span>

- f(x) = $\frac{1}{\sigma \sqrt(2\pi)} * e^\frac{-(x-\mu)^{2}} {2\sigma^2}$ 
- ![](images/Pasted%20image%2020231207174150.png)
- A normally distributed variable having mean 0 and standard deviation 1 is said to have the standard normal distribution, i.e. Z-curve.
- ![](images/Pasted%20image%2020231207174253.png)
- Calculate the probability density function of normal distribution using the following data. x = 3, μ = 4 and σ = 2. => 1.106
- [Standard normal table - Wikipedia](https://en.wikipedia.org/wiki/Standard_normal_table)
- ![](images/Pasted%20image%2020231207175706.png) 
- Determine the area under the standard normal curve that lies to the left of 1.23. => 0.8907
- z > 0.76 = 0.2236
- -0.68 < z < 1.82 => 0.7173
- If X∼N(4,9), find P(X>6) => z=0.67 and P(x) = 0.25143
- The working lives of a particular brand of electric light bulb are distributed with a mean of 1200 hours and a standard deviation of 200 hours. What is the probability of a bulb lasting more than 1150 hours? Use normal distribution formula. => 0.59871
- Calculate the probability that the next car to pass will be traveling more than 58 miles per hour, given $\mu$ = 61 and $\sigma$ = 4. => 0.7734
#### <span style="color:#e538c0">Exponential</span>

-  How much time do we need to wait before a given event occurs?
- f(x) = $\lambda * e^{-\lambda*x}$ for x > 0, $\lambda$ is the decay parameter
- ![](images/Pasted%20image%2020231207172847.png)
- Mean = $\frac{1} {\lambda}$ , sd = $\frac{1} {\lambda}$
- A postal clerk spends an average of 4 minutes with their customer. Find the value of the function at x = 5 by using the exponential function formula. => 0.072
- A person spends an average of 10 minutes on a counter. Find the value of the function at x = 7 by using the exponential function formula. => 0.04966
- Assume that, you usually get 2 phone calls per hour. Calculate the probability, that a phone call will come within the next hour. => 
#### <span style="color:#e538c0">Gamma</span>

