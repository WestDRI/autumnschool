+++
title = "Conditionals"
slug = "python-04-conditionals"
weight = 4
+++

Python implements conditionals via *if*, *elif* (short for "else if") and *else*. Use an *if* statement to control
whether some block of code is executed or not.

~~~ {.python}
mass = 3.54
if mass > 3.0:
    print(mass, 'is large')
~~~

Let's modify the mass:

~~~ {.python}
mass = 2.07
if mass > 3.0:
    print (mass, 'is large')
~~~

Add an *else* statement:

~~~ {.python}
mass = 2.07
if mass > 3.0:
    print(mass, 'is large')
else:
    print(mass, 'is small')
~~~

Add an *elif* statement:

~~~ {.python}
x = 5
if x > 0:
    print(x, 'is positive')
elif x < 0:
    print(x, 'is negative')
else:
    print(x, 'is zero')
~~~

What is the problem with the following code?

~~~ {.python}
grade = 85
if grade >= 70:
    print('grade is C')
elif grade >= 80:
    print('grade is B')
elif grade >= 90:
    print('grade is A')
~~~
