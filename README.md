# csci-b505-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSCI-B505 Assignment 3 Solved](https://www.ankitcodinghub.com/product/csci-b505-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99631&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI-B505 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Problem 1: Variable Arguments

</div>
</div>
<div class="layoutArea">
<div class="column">
Python allows variable arguments to functions which makes coding easier. Assume we have two functions, one that sums a list of numbers and one that finds the product.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
</pre>
1 2 3 4

</div>
<div class="column">
def

def

</div>
<div class="column">
sum1(x): s=0

if x:

for i s

return s

prod1(x): s=1

if x:

for i s

return s

</div>
<div class="column">
in x: +=i

in x: *=i

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>if __name__ == ’__main__’:
</pre>
<pre>    xlst = [1,2,3,4,5]
</pre>
<pre>    print("sum " + str(sum1(xlst)))
    print("product " + str(prod1(xlst)))
</pre>
If we execute this program, we have:

<pre>PS D:\505&gt; py .\Assignment_3\mult_arg_1.py
sum 15
product 120
PS D:\505&gt;
</pre>
It’s clear from inspecting the code that the spirit of the two functions are nearly indentical. We’d like to write one function that finds either the sum or product given some key value. In Python this is denoted with * and **. Prefixing a single asterisk means the variable will be bound to a list. Prefixing a double asterisk means the variable will be a key value into the dictionary named as the bound variable. Examine the code below and its execution.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 3 Page 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
</pre>
1 2 3

</div>
<div class="column">
def

</div>
<div class="column">
f(*x, **y):

def s1(x): s=0 if x:

<pre>        for i in x:
            s += i
</pre>
return s

def p1(x): s=1 if x:

<pre>        for i in x:
            s *= i
</pre>
return s

<pre>if y["action"] == "sum":
    return s1(*x)
</pre>
<pre>elif y["action"] == "prod":
    return p1(*x)
</pre>
<pre>else:
    return f"bad argument: {y}"
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>if __name__ == ’__main__’:
</pre>
<pre>    xlst = [1,2,3,4,5]
</pre>
<pre>    print(f(xlst, action = "sum"))
    print(f(xlst, action = "prod"))
    print(f(xlst, action = "reciprocal sum"))
</pre>
when run gives:

<pre>15
120
bad argument: {’action’: ’reciprocal sum’}
</pre>
Line 1 uses *. The variable x creates a list object of all the values up to, but not including the expression key = “value”. We moved the two functions to be locally defined. Lines 17-22 show how we’re using the **. Lines 28-30 show the values sent. At run-time, the string action is made into a key in the dictionary y. The value assigned is its value. We check in code 17-22 if we invoke the appropriate functions given the values–since we haven’t defined the reciprocal sum, we let the user know it’s an error. You should experiment with removing the asterisk on lines 18 and 20 to observe the error and figure out why the asterisk is required.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 3 Page 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Problem 2: Console I/O

</div>
</div>
<div class="layoutArea">
<div class="column">
There will be many times when you’ll want to run your program from the console with various arguments. Python promotes using the argparse module, now standard for some time, as the means of writing console argument scripts. Please read this documentation before continuing: https://docs.python.org/3/howto/argparse.html

Write this script and execute it. Please read about the elements that make it work.

1 import argparse

2

3 parser = argparse.ArgumentParser() 4

<ol start="5">
<li>5 &nbsp;parser.add_argument(’-lst’, nargs=’+’, default = [’1’], help=”List of ←􏰆
numbers”)
</li>
<li>6 &nbsp;parser.add_argument(’-op’, default = ’sum’, help = “sum, prod, rec”)</li>
</ol>
7

8 args = parser.parse_args() 9

<ol start="10">
<li>10 &nbsp;print(args.lst)</li>
<li>11 &nbsp;print(args.op)
when runs gives:
</li>
</ol>
<ol>
<li>1 &nbsp;PS D:\505&gt; py .\Assignment_3\goo.py -lst 1 2 3 4 5 -op sum</li>
<li>2 &nbsp;[’1’, ’2’, ’3’, ’4’, ’5’]</li>
<li>3 &nbsp;sum</li>
<li>4 &nbsp;PS D:\505&gt;</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 3

</div>
<div class="column">
Page 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Problem 3: OO

</div>
</div>
<div class="layoutArea">
<div class="column">
Like most contemporary languages, Python is object-oriented though differing in some minor ways. This in no way is meant to teach you OO in Python; it’s meant to be illustrative of significant elements to help you when you need to build a class.

Python has as a type, complex numbers that use j instead of the standard i. Here is a session:

<ol>
<li>1 &nbsp;&gt;&gt;&gt; (1+3j) + (3+4j)</li>
<li>2 &nbsp;(4+7j)</li>
<li>3 &nbsp;&gt;&gt;&gt; (1+3j) – (3+4j)</li>
<li>4 &nbsp;(-2-1j)</li>
<li>5 &nbsp;&gt;&gt;&gt; (1+3j) * (3+4j)</li>
<li>6 &nbsp;(-9+13j)</li>
<li>7 &nbsp;&gt;&gt;&gt; complex(1,3)</li>
<li>8 &nbsp;(1+3j)
The following code is an attempt to write complex numbers as a class like Python. In this class we add a method cadd which allows us to add an arbitrary number of complex numbers, but we must chain the method call. Python allows you to overload most symbols (+ for instance) which we can overload to make our complex addition similar to what would be expect as a native type. We decided to use i instead of the j that Python uses.
</li>
</ol>
1 class complex_:

</div>
</div>
<div class="layoutArea">
<div class="column">
2 def 3

4

5

6 def 7

8

9 def

10

11

12 def 13

14

15

16 def 17

18

19

20

21 def 22

</div>
<div class="column">
<pre>__init__(self, re=0, im=0):
self.re = re
self.im = im
</pre>
<pre>get_re(self):
return self.re
</pre>
<pre>get_im(self):
return self.im
</pre>
__str__(self): g=lambdax:”+”ifx&gt;=0else””

return f”({self.re}{g(self.im)}{self.im}i)”

<pre>cadd(self, other):
new_re = self.get_re() + other.get_re()
new_im = self.get_im() + other.get_im()
return complex_(new_re, new_im)
</pre>
<pre>__add__(self, other):
new_re = self.get_re() + other.get_re()
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 3

</div>
<div class="column">
Page 5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
<ol start="23">
<li>23 &nbsp;new_im = self.get_im() + other.get_im()</li>
<li>24 &nbsp;return complex_(new_re, new_im)</li>
</ol>
25

26 if __name__ == ’__main__’:

27

<ol start="28">
<li>28 &nbsp;w = complex_(1,-3)</li>
<li>29 &nbsp;x = complex_(-1,3)</li>
<li>30 &nbsp;y = complex_(1,3)</li>
<li>31 &nbsp;z = complex_(-1,-3)</li>
<li>32 &nbsp;print(w)</li>
<li>33 &nbsp;print(x)</li>
<li>34 &nbsp;print(y)</li>
<li>35 &nbsp;print(z)</li>
</ol>
36

37 print(w.cadd(x).cadd(y).cadd(z))

38

39 print((1-3j) + (-1+3j) + (1+3j) + (-1-3j)) 40

41 print(w + x + y + z)

When run we get:

<ol>
<li>1 &nbsp;(1-3i)</li>
<li>2 &nbsp;(-1+3i)</li>
<li>3 &nbsp;(1+3i)</li>
<li>4 &nbsp;(-1-3i)</li>
<li>5 &nbsp;(0+0i)</li>
<li>6 &nbsp;0j</li>
<li>7 &nbsp;(0+0i)
The __init__ works like a constructor. You don’t have to worry about destructors. Python does not have real private or protected data unlike Java or C# for example. We overload print in lines 12-14 using __str__ which uses the string we construct when print is called with our object. We overload + in lines 21-24 using __add__. Observe that we must return an object of the same type. The last three lines of output are all equivalent to zero:
</li>
</ol>
<ol>
<li>1 &nbsp;\addcontentsline{toc}{subsection}{Interactive Python Session}</li>
<li>2 &nbsp;&gt;&gt;&gt; 0 == (0+0j)</li>
<li>3 &nbsp;True</li>
<li>4 &nbsp;&gt;&gt;&gt;</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 3

</div>
<div class="column">
Page 6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Problem 4: Homework

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

2.

3. 4.

1 2 3 4 5 6 7 8 9

10

1 2 3 4 5 6 7

1 2 3 4 5 6 7 8 9

</div>
<div class="column">
Modify the second program to allow for the sum of reciprocals. For example, when given a list of numbers 1,2,3,4, 5 then the sum would be 1/1 + 1/2 + 1/3 + 1/4 + 1/5 = 2.283. When adding this function, add it locally and use the other sum function and use an inline lambda function that maps x to 1/x. You can assume zero is never in the list.

Using how to read in console information in problem 2, modify the first program so that it can be executed from the console using a list of numbers and the operation. You should not modify the original function–simply add script to read in data from the console.

Add multiplication to the Python class overload asterisk.

Perform an experimental analysis over the three algorithms, average1, average2, aver- age3. In a log-log chart, visualize their running times as a function of the input size.

<pre>def average1(S):
  #S:sequence
  n = len(S)
  my_average = [0] * n
  for j in range(n):
</pre>
<pre>    total = 0
    for i in range(j + 1):
</pre>
<pre>       total += S[i]
    my_average[j] = total / (j+1)
</pre>
<pre>  return my_average
</pre>
<pre>def average2(S):
  #S:sequence
  n = len(S)
  my_average= [0] * n
  for j in range(n):
</pre>
<pre>    my_average[j] = sum(S[0:j+1]) / (j+1)
  return my_average
</pre>
<pre>def average3(S):
 #S:sequence
</pre>
<pre>  n = len(S)
  my_average = [0] * n
  total = 0
  for j in range(n):
</pre>
total += S[j]

<pre>    my_average[j] = total / (j+1)
  return my_average
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 3

</div>
<div class="column">
Page 7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
5.

1 2 3 4 5 6 7

1 2 3 4 5 6 7

1 2 3 4 5 6

</div>
<div class="column">
Inthisquestion,youwillworkwiththethreealgorithms,algorithm1,algorithm2,algorithm3, which check whether a given sequence is unique. Perform an experimental analysis to determine the largest value of input size such that the given algorithm runs in less than 45 seconds.

<pre>def algorithm1( S):
    #S:sequence
</pre>
<pre>    for j in range(len(S)):
        for k in range(j+1, len(S)):
</pre>
<pre>             if S[j] == S[k]:
                return False
</pre>
return True

<pre>def algorithm2(S):
   #S:sequence
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
S=

for

</div>
<div class="column">
<pre>sorted(S)
j in range(1, len(S)):
if S[j-1] == S[j]:
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>            return False
    return True
</pre>
<pre>def algorithm3(S, start, stop):
    #slice S[start:stop],  S:sequence
    if stop - start &lt;= 1: return True
    elif not algorithm3(S, start, stop-1): return False
    elif not algorithm3(S, start+1, stop): return False
    else: return S[start] != S[stop-1]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
