# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenevr possible.

Because it allows others to copy and paste their code to replicate or research issues.
- In order to create codeblocks in markdown you need to use three backticks ```


```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

# Input a number to calculate its factorial
num = int(input("Enter a non-negative integer: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```
- When you caan you should attempt to apply syntax highlighting to your codeblocks.

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

# Input a number to calculate its factorial
num = int(input("Enter a non-negative integer: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```

![Terraform Bootcamp Pr check list 2023-09-16 113312](https://github.com/rangaraju1/github-docs-example/assets/33320534/f8d2cfdf-8eed-4964-86cc-feb211981c37)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.
> Here is an example of using codeblock for an error that appears in bash.

```bash
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero
```

## References

- [Basic writing and formatting syntax (Github Flavoured Markdown)]https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
