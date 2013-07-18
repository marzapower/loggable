Loggable - a simple log4j meta-library
Copyright (C) 2010-2013  Daniele Di Bernardo

You can find all the appropriate information about this meta-library
at the following page:

http://www.marzapower.com/loggable

Example
Try out this quick example:

```java
import com.marzapower.loggable.*;

@Loggable
public class Test {
  public static void main(String... args) {
    Log.get().debug("System is working!");
  }
}
```java
