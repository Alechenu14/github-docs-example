# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in ***markdown make it easy*** for tech people to *copy, paste, share code*.
A good Cloud __Engineer uses__ Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- in order to create codeblock in markdown you need to use three backtics (`)
-  Not to be confused with quotation (')


```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```

check out the difference when you apply synthax highlighting to your codeblock

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```

![download (1)](https://github.com/Alechenu14/github-docs-example/assets/145616713/f7a5c119-3134-4362-8f6d-92d5a9596594)

# Use of codeblock

A good cloud uses codeblocks for both code and error that appears in the console.

```bash
Traceback (most recent call last):
  File "example.py", line 5, in <module>
    result = 10 / 0
ZeroDivisionError: division by zero

```

> Here is an example of using codeblock for an error that appears in bash

## Use Github flavoured Task Lists

Github extents Markdown to have a list where you can check of item<sup>[1]</sup>

- [x] Finish Step 1
- [x] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emoji (Optional)
Github Flavoured Markdown  (GFM) Support emoji Shortcodes
Here are some examples:
| Name | Shortcode | Emoji |
| --- | ---- | --- |
| woman | `:woman_dancing:` | :woman_dancing: |

# Step 5: How to create a table

```
| Name | Shortcode | Emoji |
| --- | ---- | --- |
| woman | `:woman_dancing:` | :woman_dancing: |

```
> Github Extends the functionality of Markdown tables to provide more alignment and table cell options)<sup>[1]</sup>


## References
- [Basic writing and formatting syntax(Github flavored markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Github Flavoured markd down task list](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [GFM emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet)
