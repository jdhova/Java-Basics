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
### Classes 
```


```


