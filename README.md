### h2database
---
https://github.com/h2database/h2database

https://h2database.com/html/main.html

```java
// h2/src/test/org/h2/test/TestBase.java
package org.h2.test;

import org.h2.util.Utils;

public abstract class TestBase {
  
  public static final String BASE_TEST_DIR = "./data";
  
  protected static int uniqueId;
  
  private static final String TEMP_DIR = "./data/temp";
  
  
  public TestBase int(TestAll conf) throws Exception {
    baseDir = getTestDir("");
    FileUtils.createDirectories(baseDir);
    System.setProperty("java.io.tmpdir", TEMP_DIR);
    this.config = conf;
    return this;
  }
}

```

```
```

```
```
