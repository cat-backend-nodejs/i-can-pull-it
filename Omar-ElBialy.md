## Recursive solution using Python
```python
def sum(n):
    if not n >= 1 & n <= 10e9:
        print("n must be in the scope [1, 10e9]")
    
    if n == 1:
        return 1
    else:
        return n + sum(n-1)
    
print (sum(10))
```
