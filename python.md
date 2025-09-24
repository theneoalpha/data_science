Why Python

- Easy and popular language
- Dynamic typing ( no need for int, char, bool,….)
- Wide range of extended(extra) libraries
- Long community support
- Resources abundant
- brackets is not required but INDENTATION is must

Libraries

    Numpy - numeric computing , smooth long array handling
    Panda - data manipulation, csv read, csv write
    Matplotlib- data visulaization
    Seaborn - statistical data visaulization

Operators in Python  

    - Arithematic Operators 

        Addition                              +
        Substraction                          -
        Multiplication                        *
        Divison                               / (always floating number)
        Floating Division                     // (always gives int number)
        Modulus                               % (remainder deta hai)
        Exponential                           a**b (a power b)

    - Comparison Operator (always in True and False only)
    
    - Logical Operator   And and  or or  not not

        And                                   and
        Or                                    or
        not                                   not

    - Bitwise Operator
        Bitwise and operator                  &
        Bitwise or operator                   |

    - Assignment Operator
    
    - Membership & Identity Operator (always True or False)

        Present in sequences                  x in 1st
        Not Present                           x not in 1st
        Same Object                           a is b
        different object                      a is not b



Taking input in Python - we have input() 

    eg. a = input("Enter the number”)  ## bydefault it takes user input always to string which need to typecast everytime
    
        a = input("Enter value of a”)              # '67'
        b = input("Enter value of b”)              # '45'

        print(a+b)                                  # 6745  // wrong in python 
        print(int(a)+int(b))                        # 112. // correct way
        
        
Precedence in Python

        bracket >           exponential >        multiply / divide >         addition / substraction


        (left to right)     (right to left)      (left to right)             (left to right)

If Else in Python (indentation is must)

    	x = 5
    	if x > 10:
    			print("x is greater than 10")
    	elif x > 5:
    			print("x is greater than 5 but not more than 10")
    	elif x == 5:
    			print("x is exactly 5")
    	else:
    			print("x is less than 5")


function in python 
    
    	def add(int a, int b)
            {return a+b}



Switch/ Match Cases in Python



    	match code:			
            case 200:print(“Response OK”)
            case 400:print(“Not found”)
            case _:print(“sorry not matchec”)		## default case handle by “_” in python


String Formatting and F-String

    String : string is immutable in Python, we make a copy of the string
    
        str = “Vikas” #actual string
        newStr = str.upper()            # yaha pe nayi string bani

    F-String :

        old Method
            print(“My name is {} and I am {} year old”.format(name,age))

        new Approach (F-STRING APPROACH) :
            print(f”My name is {name} and i am {age} year old”)
        
Padding and Allignment

    print(f”{“Python”:<10}”); # left align          Python
    print(f”{“Python”:>10}”); # right align           Python
    print(f”{“Python”:^10}”); # center align.        Python 
    
    
For Loop in Python

    for item in i :
        print(item)             # ye 0th se n-1 tak print kar dega
        
    for item in range(1,10):
        print(item)              # ye 1 se 9 tak print kar dega
        
        
While Loop 

    count = 0
    while count<3:
        print(count)
    cout+=1


List and List Methods (array in c++ , node)
    - mutable in python
    - mixed data-types we can add #[”banana”, 1, True]
     
Tuples (same just as array , BUT IMMUTABLE)
    - we cannot change the element of tuple
    - faster than list
    - empty_tuple = ()                                       # empty tupple example
    - number = (1,2,3,4,5)                                   # Basic example of tuples
    - mixed data types                                      # (1, “Hello”, 3.14, True)
    - Single element tuple (comma is necessary)             single_element = (42,)
Sets and set methods
    - unordered, mutable, unique collections of elements
    - numbers = {1, 2, 3, 4, 5}                                     # normal basic set example
    - Empty set (must use set(), not {})  - sample = set()      # ya pe “{}” nahi hai kyoki ye empty dictornary hota hai
    
Dictionary in Python ( Object in node)
    - Jis type se object hota hai , same python me usse dictornary bolte hai
    - key -value pair
    - empty dictornary is define as empty = {}

    - normal basic example			
        student = {
                    “name”:”vikas”,
                    “age”:34,
                    “grade”:”A”
    			    }
                    
        print(student[“name”])             #1st way to access the dictornary value NOT RECOMMENDED
        print(student.get(“name”))	      # 2nd way , better way , if key not exist then it shows “None” BETTER
