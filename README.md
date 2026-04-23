# actuarial-pricing-model

## Overview
This project develops an actuarial pricing model by combining techniquess I learned in numerical analysis with insurance risk modeling. The goal is to estimate claim severity and construct risk-based premium curves using methods taught to me in numerical analysis, combining the two topics together. 

## Objectives
- Model claim severity using a lognormal distribution
- Estimate distribution parameters using Newton's Method
- Construct risk-based premium curves
- Apply interpolation techniques to approximate pricing functions

## Methodology
### 1. Severity Modeling
Claim severity is modeled using a lognormal distribution, capturing the right-skewed nature of insurance loss data. 

### 2. Parameter Etimation
The standard deviation of the lognormal distribution are estimated using Newton's Method, allowing for efficient numerical optimization and demonstration of Newton's Method.

### 3. Premium Construction
Expected losses are calculated and used to construct premium curves based on varying levels of risk. 

### 4. Interpolation
Cubic spline interpolation is applied to generate smooth premium curves across continuous risk variables.

## Results
- Successfully modeled severity using a lognormal distribution
- Generated smooth premium curves across risk classes
- Demonstrated the relationship between risk level and expected loss
- Showed how numerical methods can be applied to actuarial pricing problems

## Tools 
- Python

## Key Takeaways
This project demonstrates how mathematical and computational techniques can be integrated to solve real-world actuarial problems, particularly in pricing and risk modeling. 

## Future Improvements
- Incorporate frequency modeling using exposure data to build a full frequency-severity model
- Explore alternative severity distributions
- Apply ML techniques for enhanced prediction accuracy

## Author
Nathan Tassey
 with Patrick Lakomy
