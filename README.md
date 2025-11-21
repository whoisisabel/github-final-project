# Simple Interest Calculator

A calculator that computes **simple interest** given the principal, annual rate of interest, and time period in years.

## Formula

Simple Interest (SI) = (P × R × T) / 100


Where:  
- `P` = Principal amount  
- `R` = Annual rate of interest (%)  
- `T` = Time period in years  

## Input
- `p` → Principal amount  
- `r` → Annual rate of interest (in %)  
- `t` → Time period (in years)  

## Output
- `SI` → Simple interest calculated as `SI = (p * r * t) / 100`

## Example (Python)

```python
# Input
p = 1000  # Principal
r = 5     # Annual Interest Rate
t = 3     # Time in years

# Simple Interest calculation
SI = (p * r * t) / 100
print("Simple Interest =", SI)
