## Loggable
### A simple log4j meta-library
&copy; 2010-2018  Daniele Di Bernardo

### Overview
Loggable is a handy library that will make logging much more easy in your Java project.
It leverages the features of the Apache log4j library, and will make use of reflection to make you log directly in your
classes removing all the redundant code required by log4j.

### Info
You can find all the appropriate information about this meta-library
at the following page:
http://www.marzapower.com/loggable

### Example
Try out this quick example:

```java
import com.marzapower.loggable.*;

@Loggable
public class Test {
  public static void main(String... args) {
    Log.get().debug("System is working!");
  }
}
```
