## Fix Calculator Tests

Fix the following Python test file to run successfully the tests

```python
import unittest
import calc

class TestCalculator(unittest.TestCase):

def add_test(self):
    self.assertEqual(calculator.add(1, 1), 2)

def test_substract(self):
    self.assertEqual(calculator.substract(4, 3), 1)

def multiply_test(self):
    self.assertEqual(calculator.multiply(3, 2), 6)

def divide_test(self):
    self.assertEqual(calculator.divide(4, 2), 2)
```
