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