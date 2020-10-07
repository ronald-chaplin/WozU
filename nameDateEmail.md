# Name Date Email
## written by Ronald Chaplin

```java
import java.time.LocalDate;
import java.util.*;


class Main {
  public static void main(String[] args) {    
     Scanner scan = new Scanner(System.in);    
    System.out.println("Enter your name:");
    String name = scan.nextLine();    
    System.out.println("Enter your email:");
    String email = scan.nextLine();
    System.out.println("Enter month of birth (1-12): ");
    int month = scan.nextInt();
    System.out.println("Enter day of birth : ");
    int day = scan.nextInt();
    System.out.println("Enter year of birth (XXXX): ");
    int year = scan.nextInt();
    scan.close(); 
    System.out.println("User's name: " + name);
    System.out.println("Email: " + email);
    System.out.println("Birthday: " + LocalDate.of(year, month, day));
    
  }
}
```
