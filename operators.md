> ### Q1. Perform the following operations and provide the results:
> * 15 + 7
> * 28 - 9
> * 6 * 5
> * 20 / 4
> * 17 % 3
> * ANSWERS
22
19
30
5
2

> ### Q2. Declare a variable total with an initial value of 50. Use compound assignment operators to perform the following updates:
> * Increment total by 15
> * Decrement total by 8
>
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

> ### Q4. Given boolean variables isSunny and isWarm, write Swift code to determine and print whether it's a good day based on the following conditions
> * It's a good day if it's both sunny and warm.
> * It's a good day if it's either sunny or warm.
```
var isSunny = false
var iswarm = false
if (isSunny == true && iswarm == true) ||  (isSunny == true || iswarm == true){
    print("It's a good day")
}
else{
    print("It's a bad day")
}
```

> ### Q5. Use the nil-coalescing operator (??) to provide default values for optional variables:
> * var username: String? = "JohnDoe"
> * var age: Int? = nil

> ### Q6. Use the closed range operator (...) to create a range and print the numbers from 1 to 10.
```
for i in 1...10{
    print(i)
}
```

> ### Q7. Given the variable score = 85, use the ternary conditional operator to determine and print whether the student passed or failed (passing score is 70 or above).
```
var score = 85
print(score >= 70 ? "student passed" : "student failed")
```

> ### Q8. Given the optional variable student of type Student? use optional chaining to safely access and print the student's name:
>  struct Student {
>    var name: String
> }
> var student: Student?


# Single choice multichoice Question.

**Which operator is used for exponentiation in Swift?**
   [ ] a) ^    
   [✅] b) **   
   [ ] c) ^*   
   [ ] d) ^^    


**What is the purpose of the % operator in Swift?** 

[ ] a) Division
[✅] b) Modulus  
[ ] c) Multiplication   
[ ] d) Exponentiation   

**Which of the following is the correct way to concatenate two strings in Swift?**
 [✅] a) str1 + str2 
 [ ] b) str1 .+ str2    
 [ ] c) str1 ~ str2 
 [ ] d) str1 ++ str2    

**What is the purpose of the ..< range operator in Swift?**

 [ ] a) Inclusive range operator    
[✅] b) Half-open range operator    
 [ ] c) Closed range operator   
 [ ] d) Open-ended range operator   

**Which of the following operators is used for logical AND in Swift?**

  [✅] a) &&  
 [ ] b) ||  
 [ ] c) !   
 [ ] d) &   

