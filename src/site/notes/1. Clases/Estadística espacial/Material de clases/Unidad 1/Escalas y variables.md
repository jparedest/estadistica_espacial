---
{"dg-publish":true,"permalink":"/1-clases/estadistica-espacial/material-de-clases/unidad-1/escalas-y-variables/","tags":["gardenEntry"],"noteIcon":"","dg-note-properties":{}}
---

---

# Medición

La medición es un proceso inherente a toda investigación, sea esta cualitativa o cuantitativa. Es un proceso vital en el análisis estadístico.

**La medición se define generalmente como:**

La asignación de valores a propiedades de objetos (o eventos) según reglas bien definidas. También se puede entender como la estimación de la magnitud de cierta propiedad de uno o más objetos, personas, variables, elementos del espacio geográfico, con la ayuda de un sistema métrico específico (instrumento de medición, escala y unidades de medición).
![Pasted image 20260622181504.png](/img/user/1.%20Clases/Estad%C3%ADstica%20espacial/Material%20de%20clases/Unidad%201/Adjuntos/Pasted%20image%2020260622181504.png)
 
Es importante destacar que no medimos objetos, personas o colectividades tal cual; medimos **propiedades observables de ellas**, como el peso o el rendimiento laboral. La validez, consistencia y confiabilidad de los datos medidos dependen, en gran parte, de la escala de medición adoptada.

## El Concepto de Escala de Medición

La manera en que se asignan los valores a los objetos y eventos determina el tipo de escala de medición.

Una escala de medición es el conjunto de los posibles valores que una cierta variable puede tomar. Es un continuo de valores ordenados correlativamente.

El nivel en que una variable es medida (la escala) es crucial, ya que este determina:
1. Sus propiedades matemáticas inherentes.
2. El tipo de operaciones matemáticas que pueden usarse.
3. Las fórmulas y procedimientos estadísticos que se emplearán en el análisis de datos y la prueba de hipótesis. 

## Propiedades del Sistema Numérico

En 1946, el psicólogo **Stanley Smith Stevens** publicó un artículo fundamental en la revista Science titulado *"On the Theory of Scales of Measurement"*. Este trabajo estableció una clasificación que sigue siendo la base para entender la medición en diferentes campos de las  ciencias.

![Pasted image 20260622181729.png](/img/user/1.%20Clases/Estad%C3%ADstica%20espacial/Material%20de%20clases/Unidad%201/Adjuntos/Pasted%20image%2020260622181729.png)

Para clasificar las escalas, **Stevens** estableció las <mark style="background: #BBFABBA6;">propiedades</mark> del sistema numérico que están asociadas con la medición:
### 1. Identidad
Cada número posee un significado particular que lo distingue de los otros. En términos formales se expresa: si A ≠ B, entonces el número asignado a A debe ser diferente del número asignado a B. 

**Ejemplo:** Municipio de Toluca: código 106, Municipio de Metepec: código 051.

### 2. Magnitud
Los números tienen un orden inherente (ascendente o descendente). En términos formales se expresa: si A > B, entonces el número asignado a A debe ser mayor que el número asignado a B.

**Ejemplo:** Ciudad pequeña: población < 50 000, ciudad media: 50 000 < población < 500 000, ciudad grande: población > 500 000.

### 3. Igualdad de Intervalos (o Distancia)

La diferencia entre los números en cualquier punto de la escala es la misma (por ejemplo, la diferencia entre 10 y 20 es igual a la diferencia entre 100 y 110). En términos formales se expresa: La diferencia entre A y B es igual a la diferencia entre C y D si: (A - B) = (C - D).

**Ejemplo:** La diferencia de temperatura entre 10°C y 20°C es la misma que entre 25°C y 35°C (ambas diferencias son de 10°C)

### 4. Cero Absoluto
El punto cero representa la ausencia total de la propiedad que se está estudiando. El cero no es arbitrario sino que indica que la magnitud de la propiedad es nula.

**Ejemplo:** Densidad poblacional = 0 habitantes/km² significa ausencia total de población.

| Propiedad          | Permite afirmar           | Operación matemática             |
| ------------------ | ------------------------- | -------------------------------- |
| Identidad          | A ≠ B                     | Igualdad, desigualdad (=, ≠)     |
| Magnitud           | A > B o A < B             | Relaciones de orden (<, >, ≤, ≥) |
| Intervalos iguales | (A-B) = (C-D)             | Suma, resta (+, -)               |
| Cero absoluto      | A = 2B significa el doble | Multiplicación, división (×, ÷)  |

# Escalas de medición

Stevens propuso que todas las mediciones en ciencia se pueden clasificar en cuatro tipos de escalas, cada una con propiedades progresivamente más restrictivas y, por tanto, más informativas y que, en términos estadísticos, se agrupan en dos categorías principales:

| Categoría                  | Escalas           |
| -------------------------- | ----------------- |
| Categóricas o Cualitativas | Nominal y Ordinal |
| Numéricas o Cuantitativas  | Intervalo y Razón |

> La escala nominal es la más elemental y la de razón la más completa. La propiedad de una escala incluye todas las propiedades de la escala anterior.

![Pasted image 20260622182314.png\|500](/img/user/1.%20Clases/Estad%C3%ADstica%20espacial/Material%20de%20clases/Unidad%201/Adjuntos/Pasted%20image%2020260622182314.png)

<small>Fuente: Merli, Giampaolo Orlandoni. "Escalas de medición en Estadística." Telos: Revista de Estudios Interdisciplinarios en Ciencias Sociales 12.2 (2010): 243-247.</small>

## A. Escala Nominal

Es la forma más rudimentaria de medir. Las unidades de estudio se agrupan en clases excluyentes según una propiedad.
En la escala nominal los números se usan meramente como identificadores, etiquetas o nombres. 
La elección de los números es arbitraria y no reflejan orden o jerarquía. Solo cumplen una función de clasificación y no pueden manipularse aritméticamente.

#### Propiedades:
1. **Relación Matemática:** Equivalencia (=) o no equivalencia (≠).
2. **Operación Permitida:** Conteo. Imagina que usas etiquetas de color para clasificar a las personas (rojo, azul, verde). Solo puedes contar cuántas hay de cada color, pero no puedes sumar los colores.
3. **Estadísticos Comunes:** Frecuencias y Moda.

##### Ejemplos:  
Género, nacionalidad, colores, grupos sanguíneos.

![Pasted image 20260622183723.png](/img/user/1.%20Clases/Estad%C3%ADstica%20espacial/Material%20de%20clases/Unidad%201/Adjuntos/Pasted%20image%2020260622183723.png)

## B. Escala Ordinal

Se logra cuando las observaciones pueden colocarse en un orden relativo (jerarquía) con respecto a la característica evaluada.

#### Propiedades: 
1. Se emplea para identidad y magnitud.
2. La distancia o el intervalo entre los puntos de la escala no es constante y no puede determinarse. Es como clasificar a los corredores en una carrera (1º, 2º, 3º). Sabe quién llegó antes y quién después (orden), pero no sabe si el 1º y el 2º llegaron muy juntos o con una gran diferencia (la distancia no es uniforme).
3. La operación de sustracción no tiene significado. Solo las relaciones "mayor que", "menor que" e "igual a" tienen significado.

##### Ejemplos: 
- Nivel socioeconómico, nivel educativo, rangos militares, clasificación de satisfacción (ej. bajo, medio, alto). 
- La cobertura de la maleza en un campo, donde la diferencia entre el nivel 3 y 2 no se sabe si es la misma que entre el nivel 2 y 1.

![Pasted image 20260624114640.png\|600](/img/user/1.%20Clases/Estad%C3%ADstica%20espacial/Material%20de%20clases/Unidad%201/Adjuntos/Pasted%20image%2020260624114640.png)

## C. Escala de Intervalo

Representa magnitudes con la propiedad de igualdad de la distancia entre puntos de la escala. Permite medir la distancia existente entre cada valor.
#### Propiedades: 
1. Cumple con Identidad, Magnitud e Igualdad de Intervalos.
2. Cero Arbitrario: El valor cero no es absoluto y no representa la ausencia de la característica medida.
3. Operaciones Permitidas: Suma y Resta tienen significado. La multiplicación y división no son apropiadas debido a la ausencia de un cero absoluto. Es como medir la temperatura en Celsius. Puede saber que la diferencia entre 10°C y 20°C es la misma que entre 20° C y 30° C (intervalos iguales), pero 0°C no significa ausencia de calor, por lo que no puede decir que 20° C es el doble de calor que 10° C (cero arbitrario).
4. Estadísticos Comunes: Media aritmética y Varianza.

##### Ejemplos: 
Temperatura en grados Celsius o Fahrenheit.

![Pasted image 20260624115148.png\|400](/img/user/1.%20Clases/Estad%C3%ADstica%20espacial/Material%20de%20clases/Unidad%201/Adjuntos/Pasted%20image%2020260624115148.png)

## D. Escala de Razón o Proporción

Es el nivel de medición más completo. Tiene todas las propiedades de las escalas anteriores y, además, posee el cero absoluto (o real).

#### Propiedades: 
1. El cero representa la ausencia total de la magnitud que se está midiendo.
2. Operaciones Permitidas: Se puede realizar cualquier operación lógica y aritmética (incluyendo multiplicación y división). 
3. Permite hacer comparaciones como proporciones y decir cuántas veces es más grande un objeto que otro. Es como medir la altura. 0 metros significa ausencia de altura (cero absoluto). Puede decir que una persona de 2 metros es el doble de alta que una de 1 metro.

##### Ejemplos: 
Peso, longitud, distancia, ingresos, precios, población, densidad.

> [!summary] Recuerda que
> Las variables **cualitativas** o categóricas utilizan la escala nominal u ordinal.
Las variables **cuantitativas** o numéricas pueden utilizar escala nominal, ordinal, de intervalo o de razón.
 
