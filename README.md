
# Price-Optimization-Engine
## OVERVIEW:
The Price Optimization Engine is a dynamic software solution designed for retail businesses to maximize profits by intelligently adjusting product prices based on market conditions, demand, and competitive pricing. It caters to retailers seeking automated and data-driven pricing strategies, enhancing competitiveness and profitability in the ever-changing market landscape.


## FEATURES:
- **Dynamic Pricing:** Adjust product prices in real-time based on market conditions.
- **Data-Driven Strategies:** Utilize data analytics for informed pricing decisions.
- **Competitive Analysis:** Stay competitive by considering and adapting to competitor pricing.
- **Customizable Rules:** Tailor pricing rules to align with business goals and strategies.
## INSTALLATION:
1. Clone the repository:
```bash
https://github.com/Shuv07/Price-Optimization-Engine.git
  ```
2. Install dependencies:
```bash
pip install pandas numpy
pip install pandas scikit-learn
```
3. Run the Code:
```bash
python price.py
```
## PROJECT STRUCTURE:
- ``` price.py ```:The Price Optimization Engine code is designed using python script.
- ``` retailsales_data.csv ```: This CSV files containing Inventory, Terms of Trade, Margins, Strategic Call, Time of the day and current market prices for the betterment of customers.


## TEST CASES:
## Case 1: Testing with sample input for recommendation
test_case_1 = recommend_price(0, 6, 2023, 150, 0.15, 0.25)
print(f'Test Case 1: ${test_case_1}')

## Case 2: Testing with another set of input parameters
test_case_2 = recommend_price(4, 3, 2024, 80, 0.12, 0.18)
print(f'Test Case 2: ${test_case_2}')

## Case 3: Testing with extreme values
test_case_3 = recommend_price(6, 12, 2022, 200, 0.05, 0.3)
print(f'Test Case 3: ${test_case_3}')

## Case 4: Testing with invalid input (negative values)
test_case_4 = recommend_price(0, 4, 2025, 199, 0.12, 0.25)
print(f'Test Case 4: ${test_case_4}')

## Case 5: Testing with invalid input (out of range values)
test_case_5 = recommend_price(9, 20, 2026, 260, 0.26, 0.6)
print(f'Test Case 5: ${test_case_5}')
##  Usage:
1. Ensure the engine is configured properly.
2. Integrate with your retail platform using the provided APIs.
3. Monitor pricing adjustments and analyze performance.
## Acknowledgments
- [Shuvankit Barik] (https://github.com/Shuv07)
- [Debashis Biswal] (https://github.com/Deba123q)
- [Amiyanshu Sahoo] ( https://github.com/Adi-HereToLrn)
- [Akash Gourav] (https://github.com/sinu32)
           
            
           
