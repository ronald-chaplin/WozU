# CodeWars Capitalization
## Ronald Chaplin

```java
import java.util.*;

class Solution{
    public static String[] capitalize(String s){
        // Gorillaz - Do Ya Thing (2010)   
      String[] letters = new String[2];
      String odd = "";
      String even = "";
      String x= "";
      for(int i = 0; i < s.length(); i++){
        x = String.valueOf(s.charAt(i));
        if (i % 2 == 0 ){
          even += x.toUpperCase();
          odd += x; 
        }
        else {          
          even += x;
          odd += x.toUpperCase();  
        }
      }
      System.out.println(odd);
      letters[0] = even;
      letters[1] = odd;
        return letters;
    }
}
```
