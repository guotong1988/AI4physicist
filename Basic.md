P(A ∪ B) 用编程语言表示为

def function_P(generated_random_int_1to100__A, generated_random_int_1to100__B):
    if generated_random_int_1to100__A > 50 or generated_random_int_1to100__B > 50: #事件发生
        return 0.75

P(A ∩ B) 用编程语言表示为

def function_P(generated_random_int_1to100__A, generated_random_int_1to100__B):
    if generated_random_int_1to100__A > 50 and generated_random_int_1to100__B > 50: #事件发生
        return 0.25
        
P(A) 用编程语言表示为

def function_P(generated_random_int_1to100__A):
    if generated_random_int_1to100__A > 50: #事件发生
        return 0.5    
        
P(B) 用编程语言表示为

def function_P(generated_random_int_1to100__B):
    if generated_random_int_1to100__B > 50: #事件发生
        return 0.5   
        
所以，在A和B有相互影响的时候，有

P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
