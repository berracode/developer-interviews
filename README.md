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

### Iteradores y Streams
- Uso de iterator y ListIterator
- ¿Qué son los Streams?
- Metodos intermedios y finales en Streams



