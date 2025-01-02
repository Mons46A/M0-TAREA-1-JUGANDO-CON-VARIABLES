# 01 - Variables

## Mesa de trabajo: Duración 50 minutos

En esta práctica deberás crear un proyecto en Java para trabajar con clases y practicar la declaración de variables, tipos de datos, casting, boxing y unboxing.

---

### **Ejercicio 1: Crear una clase y declarar variables**

**Objetivo:** Configurar un entorno de desarrollo, declarar variables de diferentes tipos e imprimirlas en consola.

**Indicaciones:**

1. Crea un proyecto en Java de nombre `Practica-1-Variables` que contenga un paquete llamado `Variables` y finalmente una clase llamada `DeclaraVariables` con un método principal. Recuerda que el método principal se puede crear al momento de crear la clase. *(Pista: inicia con `public static…`)*.

2. Dentro de la clase, crea las siguientes variables según tu criterio para:
   - Almacenar el nombre de una mascota.
   - Almacenar un número con 3 decimales.
   - Almacenar el valor del dólar que se mantenga constante.
   - Almacenar el valor de Pi con los primeros 7 decimales.
   - Almacenar el valor de Euler con los primeros 15 decimales.

3. Dentro de la clase, imprime en consola las variables creadas. *(Pista: inicia con `System.out…`)*.

---

### **Ejercicio 2: Corrección de errores en declaración de variables**

**Objetivo:** Transcribir un código con varias declaraciones de variables y corregir los errores que se encuentren, aplicando lo aprendido en clase sobre tipos de datos y sintaxis.

**Indicaciones:**

Crea una segunda clase llamada `CorrigeVariables` con su correspondiente método principal.

1. Transcribe el siguiente código que contiene la declaración de variables y después corrige las que así lo requieran:

```java
Double a = 9;
int b = ‘B’;
String c = “Colombia”;
char d = ‘A’;
foat e = 832248M;
int 1numero;
String nombre-persona;
double edad;
int pesoReal = Double.parseDouble(peso);
int double = 96;
edad = 25;
int x = 45;
int y = 14;
String g = k;
```

Es importante que sepas que si una variable cuenta con un error de declaración o de valor, IntelliJ subraya con *zigzag rojo* y los errores pueden ser:
   - Errores de tipo: La variable fue creada del tipo equivocado para el valor que va almacenar.
   - Errores en el nombre de las variables: Las variables son muy sensibles al no respetar las condiciones para crear variables.
   - Omitir el punto y coma final: Java obliga al cierre de una sentencia por medio del punto y coma, para reconocer cuando inicia la próxima sentencia
   - Valor erróneo asignado a la variable: La variable cuenta con un valor no esperado, algo similar al primer error presentado Errores de tipo, por ejemplo: la edad de una persona nunca puede ser negativa, si se declara la variable *int edad = -15* no existe error de tipo, porque el tipo de dato es correcto, sin embargo, el valor asignado no lo es. 
   - Los errores de tipo son detectados generalmente al momento de la compilación; sin embargo, IntelliJ ayuda mucho a identificarlos mientras se escribe el código. En el caso de los errores de asignación, generalmente no se detectan, hasta que el programa es ejecutado.

---

### **Ejercicio 3: En este ejercicio, te enfocarás en el casting (casteo) de variables en Java. Aprenderás a convertir entre diferentes tipos de datos, tanto primitivos como objetos, utilizando diversas técnicas de casteo.**

*Objetivo:* es practicar cómo manejar y transformar datos en tu código, asegurando que los tipos de datos sean correctos para operaciones específicas y evitando errores de conversión.

**Indicaciones:**

1. Crea una nueva clase llamada CasteoVariables, con su respectivo método principal.

2. Declara la variable que corresponda al casteo que se solicita:
   + Convierte un valor de tipo String a int
   + Convierte un valor de tipo String a double
   + Convierte un valor de tipo int a String
   + Convierte un valor de tipo double a String
   + Realiza un casting de double a int y de int a double.
   + Convierte un valor de tipo String a boolean y viceversa.
   + Realiza un casting entre float, long, y byte.

3. Practica el boxing y unboxing implícitos entre int y Integer.
   + **Paso 1:** Declara una variable de tipo int y asigna un valor.
   + **Paso 2:** Usa auto-boxing para convertir el int a Integer y almacena el resultado en una variable de tipo Integer.
   + **Paso 3:** Usa unboxing para convertir el Integer de nuevo a int y almacena el resultado en una variable de tipo int.
   + **Paso 4:** Imprime las variables para verificar los valores.

4. Practica el boxing y unboxing con diferentes tipos primitivos y sus correspondientes clases envolventes.
   + **Paso 1:** Declara una variables de los siguientes tipos primitivos: float, double, boolean.
   + **Paso 2:** Usa boxing para convertir cada tipo primitivo a su correspondiente clase envolvente: Float, Double, Boolean.
   + **Paso 3:** Usa unboxing para convertir cada clase envolvente de nuevo a su tipo primitivo.
   + **Paso 4:** Imprime todas las variables para verificar 
---
