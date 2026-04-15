Code sturctured with a main() and other function called inside it can be unit tested.
This allows you to test specific functions thoroughly instead of the whole file at once.


1. Make a new file
  ex. calculator.py ---> test_calculator.py

2. Import the file being tested into the test file
  ex. import calculator
  (do this in test_calculator.py)

3. Create a test version of the function
   ex. add() ---> test_add()

4. Assert expected results from add() into test_add()

5. run pytest test_add.py
