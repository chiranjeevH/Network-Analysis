# Network-Analysis
# Website Conversion and Probability Analysis

## Project Overview

This project consists of two parts:
1. Analyzing the conversion rates of two different versions of an online retailer's website to determine if there is a statistically significant difference between them.
2. Estimating probabilities associated with two slot machines in a casino based on payout frequencies.

## Problem Statements

### Website Conversion Analysis

An online shopping retailer is experimenting with two different versions of its website. The webpage randomly loads one of the two versions to every new request for the webpage. 
- **Version A** was viewed by 3,250 customers, with 1,320 conversions.
- **Version B** was viewed by 2,870 customers, with 1,250 conversions.

The retailer wants to know if either version is associated with a higher sales conversion rate (i.e., higher chance of a customer purchasing). 

**Hint:** You can draw samples from a binomial distribution using the function `random.binomial()` from the numpy library in Python.

### Slot Machine Probability Estimation

Two slot machines (M1 and M2) in the Three Rivers Casino have the following payout probabilities:
- Machine M1 pays out 15% of the time.
- Machine M2 pays out 5% of the time.

The problem is identifying which machine is which based on the payouts. If you randomly choose one of the machines (say M1) and it does not pay out, you need to estimate the probability that M1 is the machine of interest. Similarly, if it had paid out, what would be your new estimate?

**Hint:** Consider the most important rule in probability theory.

## Tools and Libraries

- Python
- numpy
- scipy
- matplotlib

## Methodology

### Website Conversion Analysis

1. **Calculate Conversion Rates:**
   - Determine the conversion rates for both website versions.

2. **Combined Proportion of Conversions:**
   - Calculate the combined conversion rate for all customers.

3. **Standard Error Calculation:**
   - Compute the standard error of the combined conversion rate.

4. **Hypothesis Testing:**
   - Perform a z-test to determine if there is a significant difference in conversion rates between the two versions.

5. **Binomial Distribution Simulation:**
   - Draw samples from a binomial distribution for both versions to simulate conversion counts.

6. **Visualization:**
   - Plot histograms of the simulated conversion counts for both versions.

### Slot Machine Probability Estimation

1. **Calculate Initial Probabilities:**
   - Determine the initial probabilities for the payout and no payout scenarios for both machines.

2. **Bayesian Updating:**
   - Update the probabilities using Bayes' theorem based on the observed outcomes (payout or no payout).

3. **Monte Carlo Simulation:**
   - Run simulations to estimate the probabilities for different outcomes.
  

## Results

### Website Conversion Analysis

The analysis showed no statistically significant difference in conversion rates between the two versions of the website. This insight allows the retailer to retain both designs without unnecessary changes, thereby saving resources and focusing on other optimization strategies.

### Slot Machine Probability Estimation

The updated probability that M1 is the desired machine is approximately 47.22% when there is no payout and 75% when there is a payout. This provides a probabilistic approach to identifying the more favorable machine.

## Conclusion

The project provided valuable insights into both website conversion rates and slot machine probabilities using statistical analysis and probability theory. The retailer can make informed decisions about website design, and a probabilistic strategy can be applied in choosing the better slot machine.

