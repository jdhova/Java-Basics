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