# Usefull constructions on python 

## Example of using unit test
```python
import unittest 
  
class TestStringMethods(unittest.TestCase): 
    def test_negative(self): 
        firstValue = "geeks"
        secondValue = "gfg"
        message = "First value and second value are not equal !"
        self.assertEqual(firstValue, secondValue, message) 
  
if __name__ == '__main__': 
    unittest.main() 
```

## Example of using map and lambda
```python
numbers = (1, 2, 3, 4)
result = map(lambda n : n * 2, numbers)
print(list(result))
```