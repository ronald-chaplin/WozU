# Name Date Email
## written by Ronald Chaplin

```java
import java.time.LocalDate;
import java.util.*;


class Main {
  public static void main(String[] args) {    
    String [] input = userInput();
    output(input);
  }

  public static String[] userInput(){ 
    Scanner scan = new Scanner(System.in);   
    System.out.println("Enter your name:");
    String name = scan.nextLine();
    System.out.println("Enter your email:");
    String email = scan.nextLine();
    scan.close();
    return new String[]{name, email};
  }

  public static void output(String[] a){
    System.out.println("User's name: " + a[0]);
    System.out.println("Email: " + a[1]);
    System.out.println(LocalDate.now());
    
  }
}
```
