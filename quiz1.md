
> ### Q1. Declare a variable named age of type Int and assign it the value 25

```
var age: Int = 25
print(age)
```

> ### Q2. Initialize a variable name of type String with your own name.

```
var name: String = "Sandeep Reddy"
print(name)
```

> ### Q3. Declare an immutable variable named pi and assign it the value 3.14159.

```
let pi = 3.14159
print(pi)
```

> ### Q4. Declare an optional variable named city of type String? without assigning any value.

```
var city: String?
print(city)
```

> ### Q5. If city from the previous question is not nil, print its value using force unwrapping.

> ### Q6. Use optional binding to safely unwrap and print the value of city if it exists.

> ### Q7. Declare an implicitly unwrapped optional variable named username of type String! and assign it the value "john_doe".

> ### Q8. Declare a variable named temperature and let Swift infer its type based on the assigned value 25.5.

```
var temperature = 25.5
print(type(of: temperature))
```

> ### Q9. Declare a global constant named PI with the value 3.14159 and a local variable named radius with the value 10.0. Print the product of PI and radius within a function.

```
let PI = 3.14159

func calculate(){
    let radius = 10.0
    let area = PI * radius
    print(area)
}

calculate()
```

> ### Q10. Declare a variable named country: String and assign it the value "United States".
```
var country: String = "United States"
print(country)
```


# Single choice multiChoice Question.

**What is the keyword used to declare a constant in Swift?**

[✅] a) let  
[ ] b) var  
[ ] c) const  
[ ] d) constant  

**Which of the following data types is used for storing whole numbers in Swift?**

[ ] a) Float  
[ ] b) Double  
[✅] c) Int  
[ ] d) String  

**What is the primary difference between var and let in Swift?**

[ ] a) var is used for constants, and let is used for variables.  
[✅] b) var is used for variables, and let is used for constants.  
[ ] c) There is no difference; they can be used interchangeably.  
[ ] d) var is for integers, and let is for strings.  


**What is the default value of an uninitialized Int variable in Swift?**

[✅] a) 0 
[ ] b) nil  
[ ] c) 1  
[ ] d) ""  


**In Swift, how do you explicitly specify the data type of a variable?**

[ ] a) Using the type keyword  
[ ] b) Using the DataType: syntax  
[✅] c) Swift automatically infers the type, no need to specify  
[ ] d) Using the type() function  


**Which of the following statements is true regarding Swift variable names?**
[ ] a) Variable names can contain spaces.  
[✅] b) Variable names are case-sensitive.  
[ ] c) Variable names must start with a number.  
[ ] d) Variable names can be a reserved keyword.

**In Swift, what is the purpose of the typealias keyword?**

[ ] a) To create an alias for a class.  
[ ] b) To create an alias for a function.  
[✅] c) To create an alias for a data type.  
[ ] d) To create an alias for a variable. 


**Which of the following data types are considered as Swift primitive types?**

[✅] a) Int  
[✅] b) String  
[✅] c) Double  
[ ] d) Array  


**What does the nil keyword represent in Swift?**

[ ] a) An empty array.  
[✅] b) The absence of a value.  
[ ] c) A placeholder for a variable.  
[ ] d) A default value for an optional.  

**Which of the following is true about optionals in Swift?**

[ ] a) Optionals can only represent non-optional values.    
[✅] b) Optionals in Swift are denoted by a question mark (?).  
[ ] c) Optionals are not used for handling the absence of a value.  
[ ] d) Optionals are required for all variable declarations.  


> ### Q1. Perform the following operations and provide the results:
> * 15 + 7 = 22
> * 28 - 9 = 19
> * 6 * 5 = 30
> * 20 / 4 = 5
> * 17 % 3 = 2

> ### Q2. Declare a variable total with an initial value of 50. Use compound assignment operators to perform the following updates:
> * Increment total by 15
> * Decrement total by 8

```
var total = 50
total += 15
total -= 8
print(total)
```

> ### Q3. Given the variables x = 10 and y = 20, determine and print the results of the following comparisons:
> * x > y
> * x <= y
> * x == y
> * x != y

```
var x = 10, y = 20
print(x > y)
print(x <= y)
print(x == y)
print(x != y)
```
