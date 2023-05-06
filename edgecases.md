# Edge cases in Python

In Python, an edge case is a specific input or set of inputs that tests the limits or boundaries of a function or program. It is usually used to identify potential errors or unexpected outcomes that may occur when the function or program is used in real-world scenarios.

For example, suppose you have a function that calculates the average of a list of numbers. An edge case for this function might be an empty list or a list with only one element. These inputs test the boundary conditions of the function and may require special handling or consideration to avoid errors or unexpected outcomes.

Here's an example of a function in Python that calculates the average of a list of numbers, including special handling for edge cases:


```
def average(numbers):
    if len(numbers) == 0:
        return 0
    elif len(numbers) == 1:
        return numbers[0]
    else:
        return sum(numbers) / len(numbers)
```

In this example, if the input list is empty, the function returns 0 to avoid a divide-by-zero error. If the input list has only one element, the function returns that element to avoid a division by 1. These are examples of edge cases that have been specifically handled to avoid errors or unexpected outcomes.

