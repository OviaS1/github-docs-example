# Writing Good Documentation 

## Step 1 - Using Codeblocks 

Codeblocks in markdown makes it *easier to copy* and share code,
**A good Cloud Engineer** uses Codeblock whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.
To create codeblocks, use single back tick *not single quotations*

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```
when you can you should attempt to apply syntax to codeblocks

```Python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```
![keyboard](https://github.com/OviaS1/github-docs-example/assets/145389326/9f840d37-a9fa-4b25-bfef-270e40c91686)

Good cloud Engineer use codeblock for both error and example, 

```bash
# Attempting to divide by zero
numerator = 10
denominator = 0

try:
    result = numerator / denominator
except ZeroDivisionError as e:
    print(f"Error: {e}")
see an example
```
Emoji is supported in GFM, see example below
☁️
| Name | Shortcode| Emoji |
| --   | -------- | ----- |
| cloud| :cloud:  |       |


## References
- [Github markdown](https://www.wikipedia.org/) <sub>[1] </sub>

