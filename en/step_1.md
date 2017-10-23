Python has a built in function called `strftime` which can provide a date and/or time, formatted as a string.

+ Add this line of code at the top of your Python file to import the function

```python
from time import strftime
```

You can ask for the current date or time in any format

For example, if the date today is 23rd October 2017:

```python
day = strftime("%d")    # Results in 23
month = strftime("%B")  # Results in October
whole_date = strftime("%d/%m/%y")   # Results in 23/10/17
```

You can choose the format you would like by looking up the items you want in the [strftime reference](http://strftime.org/). You can use any combination of the format strings (which start with "%") and other characters such as / for date or : for time.

```python
full_datetime = strftime("%d/%m/%y at %I:%M%p")
# Results in 23/10/17 at 09:20AM
```
