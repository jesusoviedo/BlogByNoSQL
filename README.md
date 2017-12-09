MongoDB-Java Blog
================

## Prerrequisitos

Para compilar la aplicación Blog de MongoDB-Java, necesita tener:

- [JDK 1.7](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html) (no se recomienda el JDK 1.9 y 1.8)
- [Maven](https://maven.apache.org/)
- [Spark framework](http://sparkjava.com/)
- [Template Freemarker](http://freemarker.apache.org/)

## Compilacion en Maven:
```
cd <carpeta_proyecto>
mvn package
mvn compile ó mvn compile assembly:single

```

## Ejecutar desde la terminal
```
cd <carpeta_proyecto>
mvn compile exec:java -Dexec.mainClass=uaa.java.avanzado.BlogController
```

## Notas

- IDE utilizado para el Proyecto: [Eclipse](http://www.eclipse.org/downloads/) 
