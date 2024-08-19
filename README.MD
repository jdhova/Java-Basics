### BASIC JAVA

```
javac Hello.java
java Hello.java

```
### Data Types 

```
import java.math.BigInteger;

class Hello 
{
    public static void main(String a[])
    {
       int num1 = 20;
       float marks = 4.3f;
        char chh = 'k';
        double mark = 623333333;
        byte by = 127;
        short sh = 588;
        long l = 822218222;
        boolean b = true;
        BigInteger reallyBig  =  new BigInteger("1234567890123456890"+ "30");
        String str =  "Yess";
        String strs =  "Noo";
        
        

        num1 = 10+ 20;
        num1 = 22;
        chh = 'f';
        mark = 7.222222;
        by = 126;
        sh = 12345;
        l = 1234567890;
        b = false;
        str = "Hello World this is a code";
        String.join(str+strs);
        String.join(str,strs,"yellow");

        System.out.println(num1 + marks);
        System.out.println(num1);
        System.out.println(marks);
        System.out.println(chh);
        System.out.println(mark);
        System.out.println(by);
        System.out.println(sh);
        System.out.println(l);
        System.out.println(b);
        System.out.println(reallyBig);
        System.out.println("YES");
        System.out.println( String.join(str+strs));

    }
    
}
273 is largest value for byte which is lower value of int
```

### Operators 
```
{
    public static void main(String a[])
    {
     int num3 = 33;
     num3 +=20;
     num3++;

     System.out.println(num3);

    }
    
}

```
### Strings
```

class Hello2 
{
    public static void main(String a[])
    {
        String txt = "Hello";
        txt.toUpperCase()
        System.out.println(txt.length());

        String firstName = "John ";
        String lastName = "Doe";
        System.out.println(firstName + lastName);

        String firstName = "John ";
        String lastName = "Doe";
        System.out.println(firstName.concat(lastName));

        String txt = "We are the so-called \"Vikings\" from the north.";
        System.out.println(txt);

        
    }

    
}


```
### Maths
```
class Hello3 
{
    public static void main(String a[])
    {
        Math.max(5, 10);
        Math.min(5, 10);
        Math.sqrt(64);
        Math.abs(-4.7);
        Math.random();   
    }

    
}

```
### If else conditions

```

int myAge = 25;
int votingAge = 18;

if (myAge >= votingAge) {
  System.out.println("Old enough to vote!");
} else {
  System.out.println("Not old enough to vote.");
}

int time = 20;
String result = (time < 18) ? "Good day." : "Good evening.";
System.out.println(result);


```
### While Loop

```
class Hello2 
{
    public static void main(String a[])
    {   
       int x = 0;
        while (x < 11) {
          String result = (x % 3 == 0) ? "Good day." : "Good evening.";
          System.out.println(x+ " " +( result));
          x++;
        }

    
    }
    
}
```
### Fizz Buzz with loops

```
class Hello2 
{
    public static void main(String a[])
    {   
       int x = 0;
        while (x < 21) {
         if (x % 15 == 0) {
            System.out.println(x + " "+ "Fizz Buzz");
         } else if (x % 5 == 0)  {
            System.out.println(x + " "+ "Buzz");
         } else if (x % 3 == 0){
            System.out.println(x + " "+ "Fizz");
         } else{
            System.out.println(x + " "+ "neutral");
         }
          x++;
        }
        


    }
    
}
```
### Nested Loops**

```
class Hello2 
{
    public static void main(String a[])
    {   
        for (int i = 1; i <= 3; i++) {
            System.out.println("Mercedes: " + i); // Executes 2 times
            
            // Inner loop
            for (int j = 1; j <= 3; j++) {
              System.out.println(" C-Class: " + j); // Executes 6 times (2 * 3)
            }
          } 
        


    }
    
}
```
### For off loops
```
class Hello2 
{
    public static void main(String a[])
    {   
        String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
        for (String i : cars) {
          System.out.println(i[0]);
        }
        

    }
    
}

***Unpacking an array**

public class Hello2 {
    public static void main(String[] args) {
      int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
      for (int i = 0; i < myNumbers.length; ++i) {
         for(int j = 0; j < myNumbers[i].length; ++j) {
            System.out.println(myNumbers[i][j]);
         }
      }
    }
 }
 

```

### Java Methods **pending



### Object-Oriented Programming.

```
public class Main {
  int x = 5;
  int y = 50;
  char l ='f';
 String name = "Jude";
 String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

  public static void main(String[] args) {
    
    Main myObj1 = new Main();  // Object 1
    Main myObj2 = new Main();  // Object 2
    System.out.println(myObj1.x);
    System.out.println(myObj1.y);
    System.out.println(myObj1.l);
    System.out.println(myObj1.name);
    // System.out.println(myObj2.cars);
  }
}
```

### Classes in OOP

```
public class Main {
  int x = 500;
 final int y = 50;
  char l ='f';
 String name = "Jude";
 String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

  public static void main(String[] args) {

    Main myObj1 = new Main();  // Object 1
    Main myObj2 = new Main();  // Object 2
    System.out.println(myObj1.x);
    System.out.println(myObj1.y);
    System.out.println(myObj1.l);
    System.out.println(myObj1.name);
    // System.out.println(myObj2.cars);
  }
}

class Second {
  public static void main(String[] args) {
    Main myObj1 = new Main();
    System.out.println(myObj1.x);
  }
}

class Third {
  public static void main(String[] args) {
    Main myObj1 = new Main();
    System.out.println(myObj1.name);
  }
}

class fourth {
  public static void main(String[] args) {
    Main myObj1 = new Main();
    myObj1.name = "James";
    System.out.println(myObj1.name);
  }
}

class Fifth {
  public static void main(String[] args) {
    Main myObj1 = new Main();
    System.out.println(myObj1.cars);
  }
}

```
### Main and Public Class OOP Static void and Public void 
```

public class Main {
  // Static method
  static void myname() {
    System.out.println("My Name us Jude");
  }

  static void myAge(int age) {
    System.out.println("I am "+ age +" Years Old");
  }

  // Public method****
  public void myOccupation() {
    System.out.println("I am a Software Dev");
  }

  
  // Public method****
  public void myEducation() {
    System.out.println("I have a Msc and PHD degree");
  }

  public void myYear() {
    System.out.println(333);
  }


  // Main method
  public static void main(String[] args) {
    myname(); // Call the static method
    myAge(22);
    Main myObj = new Main(); // Create an object of MyClass
    myObj.myOccupation(); // Call the public method
    myObj.myEducation();
    myObj.myYear();

    
    
  }
}



```
### Constructors 
```
public class Main {
  int age; String education; char initial;  String name;

 
  public Main(int myAge, String myEducation, char ini,String myName) {
    age = myAge;
    education = myEducation;
    initial = ini;
    name = myName;
  }

  public static void main(String[] args) {
    Main myPerson = new Main(22, "Msc and Phd",'K',"Jude");
    System.out.println("My name is "+ myPerson.name +
     " and I graduated with a " + myPerson.education + " and my initial is " + myPerson.initial + " and I am" + myPerson.age + " Years Old! ") ;
  }
}


```

### Modifiers ***
```
Private class are classes that can not be assesed from outside 
however Public class can be assesed from the outside. more like global variable
protected The code is accessible in the same package and subclasses
```
### Incapsulation ***
```
This can be explained as hiding the inner information so it can not be viewed from the outside, However if we use public set and getters can asses this information 

Class attributes can be made read-only (if you only use the get method), or write-only (if you only use the set method) GETTERS and SETTERS
```

### Java API and packages***


### Java Encapsulation Inheritance and Polymorphism

```

class Main {
  protected String Surname = "OKAGU";

  public void occupation() {
    System.out.println("Developer and Engineer!");
  }
  
  protected void occupation2() {
    System.out.println("Developer and Doctor!");
  }
}

class Person1 extends Main {
  private String Person1Fname = "Jude";
  private String Person1MName = "Ike";
  private int PersonSIN = 222111;
  public static void main(String[] args) {
    Person1 info = new Person1();
    info.occupation2();
    info.occupation();
    System.out.println(info.Surname + " " + info.Person1Fname + " " + info.Person1MName + " and his sin is " + info.PersonSIN);
  }
}

class Person2 extends Main {
  private String Person1Fname = "Grace";
  private String Person1MName = "Amarachi";
  private int PersonSIN = 111222;
  public static void main(String[] args) {
    Person2 info = new Person2();
    info.occupation();
    System.out.println(info.Surname + " " + info.Person1Fname + " " + info.Person1MName + " and her sin is" + info.PersonSIN);
  }
}

Person1 and Person2 classes are extension of Person this they inherit the values from Person and the info in the class is confidential and encaapsulated
```

### Inner classes

```
class OuterClass {
  int x = 10;

  static class InnerClass {
    int y = 5;
  }
}

public class Main {
  public static void main(String[] args) {
    OuterClass.InnerClass myInner = new OuterClass.InnerClass();
    System.out.println(myInner.y);
  }
}

Inner classes can also inherit from the outer class
```

### QUIZ 

#### palidrone and rev string
```
public class Main {
  public static void main(String[]args) {
    String letter = "KAYAK";
    String revletter = "";

    for (int i = 0; i < letter.length(); i++) {
      revletter = letter.charAt(i) + revletter;
     
    }
    // System.out.println(revletter+"IS A PAL");
    // System.out.println(letter +"IS A PAL");
    if (revletter .equals(letter) ) {
      System.out.println(revletter.toLowerCase()+" IS A PAL1 "+letter.toLowerCase());
    } else {
      System.out.println(revletter.toLowerCase()+" IS A PAL "+letter.toLowerCase());
    }
    // System.out.println(revletter.toLowerCase()+" IS A  Aa  PAL "+letter.toLowerCase());
    
  }
}

```

### count array and sum

```
public class  Main{
  public static void main ( String []args){
    int[] myArray =  {1,3,5,6,7,8};
    // int [] myArrays = {};
    int sum  = 0;
    for(int i = 0; i<myArray.length;i++){
      sum =+ myArray[i];
    }
    // myArrays = myArray.charAt(i) + myArrays;
    
    System.out.println("The sum is: " + sum);

  }
  
  
}

public class Main {

  public static void digits(int n) {
    for (int i = 0; i < n; i++){
      System.out.println(i);
    }

  }

  public static void main(String[]args){
    digits(30);
  }
}

```
## Data Structures

### Big O  0(n) 0(n)2  and 0(1)
```
Omega Ω  Thetha θ and Omicron(Big O)  O

Ω takes the least speed, 
θ medium , 
O worst case speed


A notmal forloop is 0n because it runs a given no of times while
A nested for loop is 0n2 because it runs n*n times

0(1) or constant time is most effitient bcause we have to do one operation once
0(n) is when we do an operation n times(for loop)
0(a + b) is when we do an operation n times(for loop with more than one input arguement)
0(n)2 is when we do an operation n * n times(nested for loop)

recussions are used to minimize from 0(n)2 to 0(1)



```


### Big O  0(log n) (sorting Algorithm) 

```
This is when we split the array into different sorts before we find the value
that is using sorting before we find the value.

Finding a value by the index is o(1) because we go directl to the index
Finding a value with the value is O(n) because we need to search the values one after the other.

Inserting a value at the end is 0(1) because it takes less time while usiig index is 0(n) because we need to re arrange the index.


```
#### Linked List
```
public class LinkedList {
  private Node head;
  private Node tail;
  private int length;


/// create the Node
  class Node {
    int value;
    Node next;

    Node(int value){
      this.value = value;
    }
  }

  public LinkedList(int value) {
    Node newNode = new Node(value);  // this created a new node 
    head = newNode;
    tail = newNode;
    length = 1;


  }

}



```

### Getters and Setters

```

public class Person {

  // initialise public variables that can be used 

  // Mthods functions

  private String name;
  
  void run(String run){
    System.err.println("I can" +run);
  }

  void set_name(String name){
   this.name = name;
  }
  

  String get_name(){
   return name;
   }
   
  
  private String nation = "Canadian";



  public static void main( String []args) {

    

    // devlare your node and initialize my class
    Person jude  = new Person();

    jude.set_name("James");

    System.err.println("Hello world"+jude.nation+""+jude.get_name());

  }

}

```
### setters
```

public class Person {

  // initialise public variables that can be used 

  // Mthods functions

  private String name;
  private String membership;
  
  void run(String run){
    System.err.println("I can" +run);
  }

  void set_name(String name){
   this.name = name;
  }
  

  String get_name(){
   return name;
   }
  
   public enum membership{
    Gold, Silver, Yellow, can
   }

   void set_membership(String membership){
    this.membership = membership;
   }

   void set_membership(membership membership){
    this.membership = membership.name();
  
   }
   
     String get_membership(){
    return membership;
   }

  

   
  
  private String nation = "Canadian";



  public static void main( String []args) {

    

    // devlare your node and initialize my class
    Person jude  = new Person();

    jude.set_name("James");
    jude.set_membership(jude.membership);

    System.err.println("Hello world"+jude.nation+""+jude.get_name()+""+jude.membership);

  }

}

```

