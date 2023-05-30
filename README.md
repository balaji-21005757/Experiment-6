# Experiment-6
## Aim :
To define a method to calculate power of a number raised to other i.e. ab using recursion where the numbers 'a' and 'b' are to be entered by the user.
## Algorithm :
1. Open intellij application.
2. Get the base value and power to be increased value.
3. Create a function to calculate power of number
4. Enter the base value and power value as argument of function.
5. Execute the result.
## Program :
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int basevalue,powervalue;
        System.out.println("Enter base value");
        basevalue = sc.nextInt();
        System.out.println("Enter power value");
        powervalue = sc.nextInt();
        int result = power(basevalue,powervalue);
        System.out.println(basevalue +"^"+ powervalue +"="+ result);
    }
    public static int power(int base,int powerraised)
    {
        if(powerraised !=0)
        {
            return (base*power(base,powerraised-1));
        }
        else {
            return 1;
        }
    }
}

```
## Output :
![image](https://github.com/balaji-21005757/Experiment-6/assets/94372294/ca9b4634-bef0-4b7e-b6e8-1e9f79e7e940)

## Result :
Thus To define a method to calculate power of a number raised to other i.e. ab using recursion where the numbers 'a' and 'b' are to be entered by the user.
