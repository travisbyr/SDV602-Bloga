<h1>Week 2 - Journal</h1>

<h3>What</h3>

This week we created a number counter the tells us whether a number is a fizz, buzz or fizz buzz. For the next lesson of this week we learned how to scan a document in python. Here is what I learnt:

<h3>Fizz buzz</h3>

Fizz buzz is a number division teaching game.  Fizz buzz is a game where a number is either a fizz, buzz, fizz buzz or neither. The outcome is determined by the following rules:

- If a number can be divided by 3 its a fizz.
- If a number can be divided by a 5 its a buzz.
- If a number can be divided by both its a fizz buzz.
- If none of the above rules applies the number is shown.

For the first class, we were tasked to create a program in pars , where a user inputs a range of numbers, and the program would determine the outcome using the above rules.  Below is the our code example, as well as a photo of the outcome.

```python
def fizz_buzz(fizz=3, buzz=5, up_to=15):
    x = 0
    result = []
    while x <= up_to:
        string = ""
        if x % 3 == 0: # If x can be divided by 3
            string += "Fizz"
        if x % 5 == 0: # If x can be divided by 5
            string += "Buzz"
        print((x, (str(x) if string == "" else string))) # Print x and its outcome.
        x += 1

fizz_buzz(3, 5, 56)
```

Outcome:



<h3>Scanning</h3>

For the next class we were given a code example of a scanning function. This function would retrieve values from a .CSV file. We were also given a function that displayed this data in a table. 

We were tasked to solve tasks using the given functions, here are functions I created to solve these tasks.

```python
# Exercise one


def sum_of(column_name, a_list_of_dictionary):
    """
    Return one value that is the sum of the column 
    column_name of each "row" (dictionary)
    """
    x = 0
    for i in range(0, len(a_list_of_dictionary)):
        x = x + int(a_list_of_dictionary[i][column_name])
    print(column_name + ": " + str(x))

# Exercise Two


def multiple_cols(column_names, a_list_of_dictionary):
    """
    Return a new list of "rows" (dictionary)
    That multiples the values of the named columns
    """
    x = []
    for i in range(0, len(a_list_of_dictionary)):
        x.append(int(a_list_of_dictionary[i][column_names]))
    product = 1
    for i in x:
        product *= i
    print(column_names + ": " + str(product))
```

To begin with I found it difficult to solve the tasks, as I struggled to understand the tasks and how the existing function works. From carefully reading the function and task I was able to create an effective outcome to solve the issue.

Overall I find the tasks assigned to me this week very useful to learn about. From learning about these, I now know how to manipulate data from a given CSV file. I also have a better understanding of mathematical equations and how I can use python to achieve an outcome I desire. From this week, I have further developed my knowledge of python and how I can use it to my advantage.  

<h3>Comparison</h3>

I find python to be a very useful language that will be very beneficial for me to know in-depth. Although so far its only the second week, and my knowledge is very basic, I have learned so much and know have a basic understanding of python. When comparing this language to other languages that I know a lot about, such as JavaScript and C#, I find python similar in some aspects, but very different in others.
