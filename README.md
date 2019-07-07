<p>
This repository is used to store some fun and easy mini python programs for beginners to explore, practice and have some fun.
Feel free to email me for any questions you encountered!!
 <br/>
  <br/>
email: yixuan99316@gmail.com
</p>


**************************************************************************************************************


<strong>Here are SOME Python Notes for Beginners!!</strong>

 - <em>#</em> - single-line comment
 - <em>""" """"</em> - multi-line comment

<strong>Variabales</strong>
 - variable name must start sith a letter, may contain numbers and underscores
 - syntax: <em>variable_name = value</em>

<strong>Strings and Variables</strong>
 - Built-in functions:
          1.<em>print()</em> - takes in a value, display
          2.<em>len()</em> - takes in a string in the braket, return the length of an item
          3.<em>str()</em> - takes in a item, return a string object
          4.<em>input()</em> - Reads a string input
          5.<em>upper()</em> - returns a copy of string all upper case
          6.<em>lower()</em> - returns a copy of string all lower case
          7.<em>format()</em> - returns a formatted version of the string
      
<strong>Numbers and Math</strong>
 - when diving a int by an int, eg. 8/4, the value returned by python is a float, eg. 2.0
 - <em>int()</em> - to convert a string to an integer
 - <em>float()</em> - to convert a string to a float
 
<strong>Booleans</strong>
 - Boolean Operators
   <br/>and - Evaluates to True if both statements are true, otherwise false
   <br/>or - Evaluates to True if either of the statements is true, otherwise evaluates to false
   <br/>not - Evaluates to the opposite of the statement
 - Order of Operations for Booleans: 
   1. not
   2. and
   3. or
   4. Anything surrounded by parenthesis is evaluated first and as its own unit

<strong>Code Blocks</strong>
```
Block One
    Block Two
    Block Two
       Block Three
Block One
Block One
```
 - python uses 4 spaces indentation / but 2 is also allowed, please be consistent!
 
 
 <strong>The if Statement</strong>
 ```
 if condition1 :
     #true-code
 elif condition2 :
     #true-code
 else:
     #false-code
```

<strong>Functions</strong>
```
def function_name():
    #code block
```
Function Definition Examples: 
```
def say_hi():
    print('Hi!')

def say_hi2(name):
    print('Hi {}!'.format(name))
    
def say_hi3(first,last):
    print('Hi {} {}!'.format(first,last))
```
Calling a function:
```
say_hi()
say_hi2('Jason')
say_hi3('Jane','Doe')
```
 - A function has to be define before it is called
 
 <strong>List</strong>
 ```
 #create list with items in it
 list_name = [item_1,item_2,item_N]
 
 #create empty list
 list_name = []
 
 #get item from index
 list_name[index]
 
 #get item from negative index : -1 means get the last item from the list
 list_name[-1] 
 
 #set value by index
 list_name[index] = value
 
 #add an item to the back of the list
 list_name.append(item)
 
 #add multiple items to the back of the list
 #extend method takes in an list as parameter
 list_name.extend([item_1, item_2])
 
 #insert item at index, all existing item will be shift back
 list_name.insert(index, item)
 
 
 ```
 
 
 
 
     
 
   
