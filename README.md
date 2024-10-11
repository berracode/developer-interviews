# Preguntas para desarrollador Java

El proposito de este repositorio es listar **temas** sobre los cuales se realizan preguntas, comunmente, en entrevistas técnicas para cargos relacionados a  Java.

Encontras las siguientes categorias de preguntas:

1. Fundamentos de programación y POO
2. Conceptos básicos de Java
3. Estructuras de datos en Java
4. Conceptos avanzados de Java

Nota: *Claramente no están todas las preguntas que podrían hacer, sin embargo hay unas preguntas comunes.*

## 1. Fundamentos de programación y POO

### Programación orientada a objetos

- Encapsulamiento, herencia, polimorfismo, abstracción
- ¿Qué son las clases y Objetos?
- ¿Qué es un constructor?
- Modificadores de acceso
- diferencias entre clase abstracta e interfaz
- Herencia multiple y cómo java la maneja.
- Composición vs herencia

### Fundamentos de programación

- Estructuras de control
- Recursividad
- Manejo de excepciones

## 2. Conceptos básicos de Java

### Componentes del ecosistema Java
- Diferencias entre JDK, JVM y JRE
- ¿Java es compilado? ¿Qué es el bytecode?

### Palabras reservadas
- ¿Qué es final, static, this, super, trasient y volatile? y para qué se usan.
- Diferencia ente una variable final, static y final static.
- ¿Qué es y para que sirve syncronized?
- Diferencias entre == e equals.
- Si tengo lo siguiente:
```java
var s1 = "hola";
var s2 = "hola";

s1 == s2; //¿TRUE O FALSE?

var s3 = new String("hola");
var s4 = new String("hola");

s3 == s4; // ¿TRUE O FALSE?
s3.equals(s4); //¿TRUE O FALSE?

```

### Manejo de excepciones

- Checked vs unchecked
- Uso de Try-catch-finally
- diferencias entre throw y throws


## 3. Estructuras de datos en Java

### Java Collections Framework
- Diferencias entre List, Set y Map y qué son.
- ArrayList vs LinkedList ¿cuándo es mejor usar uno u otro?
- HashMap vs TreeMap vs LinkedHashMap
- HashSet, TreeSet y LinkedHashSet,¿cómo funcionan y qué diferencias tienen?
- ¿Qué ocupa más memoria un ArrayList o una LinkedList?

### Iteradores y Streams
- Uso de iterator y ListIterator
- ¿Qué es Streams?
- Metodos intermedios y finales en Streams

### Sobre algoritmos
- Eficiencia de tiempo de operaciones comunes (Big O)

## 4. Conceptos avanzados de Java

### Memoria en Java
- Tipos de memoria en Java
- Garbage collector (G1, Serial, Parallel, ZGC)
- String Pool

### Hilos y concurrencia
- Conceptos básicos sobre concurrencia e hilos
- Diferencias entre Thread y Runnable en Java
- ¿Cómo asegurar un un recurso compartido entre varios hilos?
- ¿Cómo gestionar los bloqueos?
- Uso de synchronized, volatile, y locks
- Paquetes de concurrencia o frameworks: ExecutorService, ForkJoinPool
- Estructuras o clases concurrentes en Java
- Diferencia entre clases concurrentes y clases thread safe

### Programación funcional

- Lambdas
- API Streams
- ¿Qué son las interfaces funcionales? Uso de Fuction, Supplier, Predicate, Consumer y su variantes BI.

### Java IO y NIO
- Manejo de archivo con IO y NIO
- Diferencias entre IO bloqueante y no-bloqueante

### Optimización en la JVM

- Preguntas relacionadas a como optimizar rendimiento en Java
- Herramienats de profiling, ¿qué son y para que sirven?



## CONTINUARA...

