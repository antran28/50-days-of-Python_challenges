> *Write a function called convert_add that takes a list of strings 
as an argument, converts them to integers, and sums the list.
> For 
example, ["1", "3", "5"] should be converted to [1, 3, 5] and 
summed to 9.*

```
def convert_add(input_string):
    if input_string:
        list = [int(i) for i in input_string]
        return print("Modified list is: "+ str(list))
    else:
        return None

test_string = ["1","3","8"]
convert_add(test_string)
```
