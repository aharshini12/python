Student: Harshini A
Register number: 1912260702
Python: 3.12.3
Libraries: Python standard library only (decimal, time, math, sys)


Files and run commands

Run commands from this folder:



Task 1: python task1_analysis.py

Task 2: python task2_types_decimal.py

Task 3: python task3_constants.py

Task 4: python task4_expressions.py

Task 5: python task5_input_validation.py

Task 6: python task6_functions.py

Task 7: python task7_module_demo.py

Task 8: python task8_algorithm.py

Task 9 interactive calculator: python task9_calculator.py

Task 9 tests: python task9_tests.py

Task 10 benchmark: python task10_performance.py

Task 11 benchmark: python task11_recommendation.py

Task 12 seasonal challenge: python task12_seasonal.py


milkrate.py contains shared constants and reusable functions.


Important assumptions to verify

The scanned PDF is not text-readable in several places. This solution interprets the original adjustments as ₹0.40 per 0.1% fat and ₹0.30 per 0.1% SNF, and the seasonal values as base ₹32.00, fat step ₹0.45, bonus ₹0.50/litre. Please compare these values with your original assignment page before submitting. The exact SNF validation range is not clearly specified, so this implementation uses 0–20% as a configurable input range.


Complexity summary

For n entries, processing each entry once takes O(n) time. Keeping all entries takes O(n) extra space; keeping only a running total takes O(1) extra space. A dictionary rate cache for k distinct fat/SNF pairs uses O(k) space and has average O(1) lookup after a rate is cached.
