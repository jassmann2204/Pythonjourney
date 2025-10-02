Python Notes – Printing and Functions
1. Printing in Python
    • To show something on the screen, we use the print() function.
    • Example:

print("Hello World")
Explanation:
    1. print → This is a function in Python.
    2. Functions are blocks of code that perform a task. In this case, print() displays something on the screen.
    3. The thing inside the brackets () is what the function will work on.
    4. Double quotes "" (or single quotes '') are used to tell Python that it is text (a string).
    5. Whatever is displayed on the screen is called the output.
Example Output:

Hello World

2. Understanding Functions
    • A function is a reusable piece of code that performs a specific task.
    • In Python, you can use built-in functions like print(), or you can create your own functions later.
Key Points:
    • print() → shows output
    • input() → asks for user input (we will learn this later)
    • Functions can take values (called arguments) inside the brackets
    • Functions can return a result (we will cover this later)

3. Practice Tips
Try printing different things:

    • print("I am learning Python")
print("Python is fun!")
print("12345")
print("Hello" + " " + "World")  # Concatenation example
    
    • Notice how Python prints exactly what is inside the quotes.

    4. Python Character Set

Letters – A to Z, a to z

Digits – 0 to 9
Special Symbols - + - * / etc.
Whitespaces – Blank Space, tab, carriage return, newline, formfeed
Other characters – Python can process all ASCII and Unicode characters as part of data or literals

    5. Print Numbers too
    Ø We can also print numbers too if required for eg:
    Ø Example print(897870878907) - it will then give us the output
    Ø Print (8979879879879879800345678) it will then give us this output

We can also carry multiplication, addition, subtraction
    Ø For eg print(2+2) - the out put will be 4
    Ø For edg print (3*2) 0 the out put will be 6 and so on

    6. Variables
    Ø A variable is a name given to a memory location in a program
    Ø Something that can be changed

For Eg:
Name = "Jas" - string (we need to use double quotes)
Age = 25 - INT
Price = 25.99 - floating value

So in the above we can see that name, age and price can vary

We always write Variable = Value

Practical

    Ø Now in above, I have instated that my variable Name, age, price have the above values
    Ø If I want to print my name using print - I will have to use [print (name)] instead of [print ("name")] - this is because in quotes it will not recognise our defined value as variable but as a string.
    Ø Ok so here is what else we can do:
    Ø Task: tell me your name and how old you are and how much you cost lol?

The command would be:
Print ("Hi, my name is:", name, "I am", age, "years old", "my services can be boiught for:", price)

What is equal to "=" used for?
    Ø Its called the assignment operator, basically whatever value I am defining in right is going to the left , in this case, my age or price is being assigned to the left hand side.

Adding another variable with same value?
Ok so interestingly, we can also assign the values from 1 variable to another
For examaple my variable age can be age2
Eg: age2 = age
print ("hi my name is:", name, "I am", age2, "years old", "while the cost of the mangoes have gone up, the ogsitics have stood at:", price2)

    7. Rules for identifiers
    • An identifier is the name you give to things in Python.
    • It is used to identify a variable, function, class, module, or object.
    • Simply put: whenever you create something in Python and need to give it a name, that name is called an identifier.
    • It cannot start with the digit
    • Cannot use special symbols
    • Can be of any lengths - but make it clean

    8. Data Types
    i. How do you find out a type of data being used in variable?
    - Simply type 
Print (type(age)) and you will get int
Print (type(price)) and you will get int
Print (type(name)) and you will get string 




And we call these  Data Types

Date Types	Explanation	Example
Integers	+ve, -ve, 0 - so numbers basically	56 or -56 - same thing
String	Sentence or word 	"Jas" 'Jas' '''Jas'''can be used with single quotes, double or triple
Float	Decimal numbers 	25.88, 66.99, 9.0
Boolean	True or False only, always use caps with T & F	Old = false, hungry = True
None	Where we don’t want to store any values	Name = none


Quick Example: 



    
    9. Keywords

    
    10. Print SUM
    
    
    a = 20
    b = 50
    sum = a*b
    print(sum)
    j = 600
    D = 40000
    sum = j+D
    print(sum)
    p = 5
    h = 2
    sum = p-h
    print(sum)

    
    11. Comments
    If we want to explain something in the code and this is how we can do it
    Basically it will not execute
    
    #This will not execute -
    """This will not also work""" - So basically 3 """
    # print("Hello world")
    # print("Hello world")
    # print("Hello world")
    
    #These 3 lines above were also not commented by pressing two keys - Ctrl and forward slash "/"
    
    12. Type of Operators
    An Operator is a symbol that performs a certain operation between operands. Operator job is to perform any operation. Like + performs addition, * performs multiplication.
    
    • Operand = the numbers (or things) you use. 
    • Operator = the sign (symbol) that tells the computer what to do.
    
    • 2 + 3
    • 2 = operand
    • 3 = operand
    • + = operator (means add)
    
    
    Type	Explain	Example
    Arithmetic operators	#arithemtic operators	
        a=5
        b=2
        print(a+b) #Addition
        print(a-b) #Minus
        print(a*b) #Multiply
        print(a/b) #Divide - Always get Floating value (means decimal)
        print(a % b) #To find the remainder  - We use Percentage sign to find this value (%)
        print(a ** b) #to find the power so in this case a to the power b so 5 to the power of 2 which should be 25
        
        Output - 
        
        
    Relational	To compare 2 values	
        
        #Relational/Comparison Operators
        a=5
        b=2
        print(a==b) #in python to find whether the value is equal or not, we use 2 == signs instead of 1
        print(a!=b) #To find not equal to we use !
        print(a>b) #To find if operatant is bigger than the other - we use ">"
        print(a<b) #To find if operatant is smaller than the other - we use "<"   
        print(a>=b) #To find out if a is equal or greater than b
        print(a<=b) #To find out if a is equal or smaller than b
        
    Assignment	Kisi Value ko assign karna	
        
        #Assignment Operators
        num = 10
        #num = num + 10 #Basically whatever is assigned to the main value, this will keep adding 10 hence the answer is 20
        #num +=10 #basically I placed a + sign and then it will allow it to add extra 10
        # num -=5
        # num *=5
        # num /=2
        # num **=2
        
    Logical	They work on Boolean values	
        
        NOT
        
        #Logical Operators
        a=100
        b=20
        print(not (a > b))
        In this example above we know a is 100 and b is 20, now we know a is greater than b so the value should be true but with NOT we get False
        
        
        AND
        
        #and
        val1 = True
        val2 = True
        print ("Answer is", val1 and val2)
        
        
        In this answer will only be True if both value are "TRUE"
        
        OR
        In Or operator if either of the values are true, then it will be true
        
        #or
        val1 = True
        val2 = False
        print ("Answer is", val1 or val2)
        
        
        #or
        a = 100
        b = 20
        print("Answer is:", a==b or a>b)
        
    
    13. Type Conversion
    When we convert 1 type of variable to another type of variable.
    
    For example, if I want to convert an integer into a floating type - we use type Conversion
    
    There are 2 type of conversion:
    
    Type Conversion	Type Casting
    Automatically converts	Manually Converts
        
    #Type Conversion	#Type Cast
    a = 2	a = int("30")
    b = 4.25	b = 4.25
    sum = a + b	sum = a + b
    print(sum)	print(type (a))
        print(sum)
        
        
    
    14. Inputs in Python
    Input() statement is used to accept values (using keyboard) from user
    
    Eg. 
    
    #Inputs in Python
    name = input ("Please tell us your name")
    age = input("Please enter your name")
    hobby = input ("What are your hobbie")
    emotion = input ("how are you feeling today")
    
    print ("hi", name, "we are glad your age is:", age, "we like that your hobby is:", hobby, "we are happy that you are feeling", emotion)

    
    
    name = input("Please tell us your name")
    age = int(input("Please tell us your age: "))
    emotion = float(input ("Please tell us in percentage how happy you are: "))
    print(type(name), name)
    print(type(age), age)
    print(type(emotion), emotion)
    print("Hi", name, "we are so happy to have you here and its good that you are above 18",age, "Please note you need to be happy", emotion)

    
    15. Inputs in Python

    
    #Write a program to input 2 numbers & print their sum
    Num1 = int(input("Please enter Number 1:"))
    Num2 = int(input("Please enter Number 2:"))
    sum = Num1+ Num2
    print(sum)

    

    
    #Write a program to input side of a square and print its area
    side1 = int(input("Pleaee enter your dimensions of side 1:"))
    side2 = int(input("Pleaee enter your dimensions of side 2:"))
    sum = side1 * side2
    print("The Total sum of your square is:", sum)

    
    
    #Write a program to input side of a square and print its area
    side = float(input("Please enter your side of a sqaure"))
    area = side*side
    print("Your square Area is:", area)

    

    
    #Write a program to input 2 folating point numbers and print their average
    num1 = float(input("Please enter Number Floating point number 1:"))
    num2 = float(input("Please enter Number Floating point number 2:"))
    sum = (num1+num2)/2
    print("Your average is:", sum)
    
    

    
    #Write a program to input 2 int numbers, a and b
    #Print True if a is greater than or equal to b. if not false
    a = int(input("Please enter int a: "))
    b = int(input("Please enter int b: "))
    print(a>=b)

    
