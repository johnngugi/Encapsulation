## What is Encapsulation

Encapsulation in Java is a mechanism of wrapping the data and code acting on the data together as as single unit. In encapsulation the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class, therefore it is also known as data hiding.Encapsulation is like your bag in which you can keep your pen, book etc. It means this is the property of encapsulating members and functions.

~~~Java

public class EncapTest {

   private String name;
   private String idNum;
   private int age;
 }
 ~~~

 In the above example the variables name and idNum are not available to outside classes.

## Setters and Getters

Getters and Setters are used to access data that is encapsulated. For each variable, the get method returns its value, while the set method sets the value.

Getters start with get, followed by the variable name, with the first letter of the variable name capitalized.
Setters start with set, followed by the variable name, with the first letter of the variable name capitalized.

Example:
~~~Java

public class EncapTest {

   private String name;
   private String idNum;
   private int age;

   public String getname() {
     return name;
   }
   public String getidNum() {
     return idNum;
   }
   public void setname(String newName) {
     name = newName;
   }
   public void setidNum(String newNum) {
     idNum = newNum;
   }
 }
~~~

In the above example the get method is used to return the values of **name** and **idNum**, and the set method is used to set the values of **newName** and **newNum**.
