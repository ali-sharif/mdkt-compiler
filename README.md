# In-memory Java Compiler 

(Renamed [Trung's InMemoryJavaCompiler](https://github.com/trung/InMemoryJavaCompiler) for brevity)

Uses JDK's [runtime compiler](https://docs.oracle.com/en/java/javase/11/docs/api/java.compiler/javax/tools/JavaCompiler.html) to compile Java source code in memory. Modifications were made to Trung's original implementation of `InMemoryJavaCompiler`, to retrieve raw compiled class files in addition to the loaded classes (`Class<?>`) originally returned. 

**Note**: Please make sure you use JDK in your runtime

