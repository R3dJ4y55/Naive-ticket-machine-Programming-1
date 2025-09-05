# Naive Ticket Machine
---
This is a lab for Vanier's Programming 01 course
---
2. The value returned is 0  

3a. If we insert too much money the machine takes it all and only prints 1 ticket.
  
3b. If we do not insert enough, the machine still prints 1 ticket. 
 
5. The price listed on the ticket is different
``` java
// Question 6
public class Student 
{

}
// and
public class LabClass 
{

}
```
7. Yes, it matters. if we write ***class public TicketMachine*** the class diagram for *TicketMachine* goes red, indicating an error.

7(Continued). We get 2 errors. (1) ***\<identifier\> expected***, and (2) ***class, interface, enum, or record expected***

7(Continued 2). I do not believe the message is that clear, a beginner might have some issues with comprehension.

8. It is.

9. One cannot leave out the *class*

## Question 10 list
### Fields
* price
* balance
* total
### Constructors
* Ticketmachine
### Methods
* getPrice
* getBalance
* insertMoney
* printTicket
---
11. (1) It starts with a capital letter. (2) It doesn't specify a datatype

12.
| Field | DataType |
| ----- | -------- |
| private int count; | int |
| private Student representative; | Student |
| private Server host; | Server |

13.
| Field | Name |
| ------ | ---- |
| private boolean alive; | alive |
| private Person tutor; | tutor |
| private Game game; | game |

14. The class names are: 
* Student
* Server
* Person
* Game

15. It does matter which order *private int price;* appears in.

16. Yes, a field declaration must end with a semicolon.
``` java
// Q17
private int status;
```

18. It belongs to the class *Student*

19. It has 2 parameters.
* String
* double

20. 

(a) It will need to be stored for as long as the object exists. It may be stored in a variable.

(b) No.  

(c) No.

``` java
// Question 21

public Pet(String petsName)
{
    name = petsName;
}
```
``` java
// Q22 - Challenge exercise

public Date(String month, int day, int year) 
{

}
```

23. In the headers, the name of the methods are different. In the bodies, getPrice() returns the value for ***price***, while getBalance() returns the value for ***balance***

24. getBalance() : "How much money was given to the machine?"

25. No. The accessor method having the same name as the return variable is only convention, not law.

27. *missing return statement*

28. The main difference is the contents of the body. *getPrice()* is a simple return statement. While *printTicket* prints several lines and updates the values of 2 variables.

29. No. They are of the *void* return type. Additionally, they purpose does not require them to return any values.

``` java
// Q31

public void increaseScore(int points)
{
    score = score + points; // OR score += points;
}
```

32. Yes, addCredits is a mutator method. To demonstrate, (1) get the initial value of *credits* for the student object. (2) add a positive, non-zero, number of credits. (3) get the final value of *credits* and compare it with the initial value. They will differ.

``` java
// Q 33
public void discount(int amount)
{
    price -= amount;
}
```
``` java 
// Q 34

public void setAge(int currentAge)
{
    age = currentAge;
}
```
``` java
// Q35

public void setAlive(boolean isAlive)
{
    alive = isAlive;
}
```

36. The value of ***price*** stays 0. I would assume this is due to the global variable price having preedence over the local parameter.

37. My cat has green eyes.

39. It would print: 
``` text
# price cents.
```
40. It would print:
``` text
# price cents.
```
42. They have different outputs. They output the value of ***price*** stored locally in the object.

43. The output is identical. %d must refer to the ***price*** specified after the string. the %n is newline(linebreak).

44. We are only asked to specify a name. No parameter is asked of us.

46. empty() is a mutator. It changes the value of a variable.










