# Documentation

The Documentation is a short introduction to MASi and the tools implemented.

## How to build

In order to build the Documentation you'll need:

* Java SE Development Kit 8 or higher
* Apache Maven 3

Change to the folder where the sources are located, e.g.: /home/user/Documentation/. 
Afterwards, just call:

```
user@localhost:/home/user/Documentation/$ mvn install
[...]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 4.220 s
[INFO] Finished at: 2017-12-20T10:32:29+01:00
[INFO] Final Memory: 25M/451M
[INFO] ------------------------------------------------------------------------
user@localhost:/home/user/Documentation$
```

As soon as the assembly process has finished there will be a file named `documentation.html` 
located at /home/user/Documentation/target/doc, which contains the documentation.

## More Information

* [Bugtracker](http://datamanager.kit.edu/bugtracker/thebuggenie/)

## License

The Documentation is licensed under the Apache License, Version 2.0.


