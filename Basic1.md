
P(A ∩ B) 用编程语言表示为
```python
def function_P(generated_random_int_1to100__A, generated_random_int_1to100__B):
    if generated_random_int_1to100__A > 40 and generated_random_int_1to100__B > 40: #两个事件都发生
        return 0.36
```

P(B) 用编程语言表示为
```python
def function_P(generated_random_int_1to100__B):
    if generated_random_int_1to100__B > 40: #事件发生
        return 0.6   
```

则 P(A|B) = P(A ∩ B) / P(B) 求得值为 0.36 / 0.6 = 0.6

