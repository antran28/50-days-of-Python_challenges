> *Write a function called divide_or_square that takes one 
argument (a number) and returns the square root of the number if 
it is divisible by 5, or its remainder if it is not divisible by 5. For 
example, if you pass 10 as an argument, then your function should 
return 3.16 as the square root*
```
def divide_or_square(n):
    if n % 5 == 0:
        return print(n ** 0.5)
    else:
        return print(n % 5)
```
divide_or_square(10) #3.1622776601683795

> *Extra Challenge: Longest Value
Write a function called longest_value that takes a dictionary as 
an argument and returns the first longest value of the dictionary. 
For example, the following dictionary should return "apple" as the 
longest value.*
```
fruits = {'fruit': 'apple', 'color': 'green'}

def longest_value(input_dict):
    # Check if the dictionary is not empty
    if input_dict:
        # Find the longest value using max and len
        longest_val = max(input_dict.values(), key=len)
        return print(longest_val)
    else:
        # Return None for an empty dictionary
        return None

# Example usage
fruits = {'fruit': 'apple', 'color': 'green', 'any': 'acradabra'}
longest_value(fruits)  #acradabra
```
