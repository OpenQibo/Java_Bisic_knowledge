```
void println() – Terminates the current line by writing the line separator string.
```

For **println()**, it adds new line after the message gets dispalyed.It can work without arguments.

For **print()**, It does not add any new line. This method only and only works with argument, otherwise it is an syntax error.


Example of **print()**
```
import java.io.*; 
  
class GFG { 
    public static void main(String[] args) 
    { 
  
        // The cursor will remain 
        // just after the 1 
        System.out.print("GfG1"); 
  
        // This will be printed 
        // just after the GfG2 
        System.out.print("GfG2"); 
    } 
} 
```
Output: 
```
GfG1GfG2
```



Example of **println()**

```
import java.io.*; 
  
class GFG { 
    public static void main(String[] args) 
    { 
  
        // The cursor will after GFG1 
        // will at the start 
        // of the next line 
        System.out.println("GfG1"); 
  
        // This will be printed at the 
        // start of the next line 
        System.out.println("GfG2"); 
    } 
} 
```
Output
```
GfG1
GfG2
```
