## Memory

###Xms and -Xmx

`-Xms` sets the initial and minimum Java heap size. The Java heap (the “heap”) is the part of the memory where blocks of memory are allocated to objects and freed during garbage collection.

`-Xmx` sets the maximum Java heap size. The Java heap (the “heap”) is the part of the memory where blocks of memory are allocated to objects and freed during garbage collection. Depending upon the kind of operating system you are running, the maximum value you can set for the Java heap can vary.

Format: `-Xms:<size>[g|G|m|M|k|K]`

e.g: `-Xms:1G`

ref:
* https://docs.oracle.com/cd/E13150_01/jrockit_jvm/jrockit/jrdocs/refman/optionX.html

###-XX:+UseCompressedOops
TODO

ref: 
* http://javarevisited.blogspot.com/2012/06/what-is-xxusecompressedoops-in-64-bit.html
* [Oracle doc: compressed oops](http://docs.oracle.com/javase/7/docs/technotes/guides/vm/performance-enhancements-7.html)

