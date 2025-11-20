# Taller07

## Construcción de programas usando estructuras repetitivas WHILE y DO-WHILE

* En su asignatura ***Fundamentos computacionales***, resolvió *(análisis, diseño de algoritmos, flujograma, prueba de escritorio, etc.)*, algunos problemas con estructuras de control repetitivas. El objetivo a continuación es codificar similares algoritmos, pero en el lenguaje de programación de alto nivel **JAVA**. 
* Programar/codificar en el lenguaje de alto nivel Java *(en el IDE NetBeans)*, sus soluciones a cada uno de los problemas listados a continuación dadas las siguientes instrucciones: 
    1. Clone este repositorio en su **PC** local `git clone URL_del_repo` 
    2. En su ***IDE*** cree un nuevo proyecto de tipo ***Java Application*** con el siguiente nombre: ***Proyect-APEB1-Taller07*** eligiendo como localización del proyecto, el repositorio *(carpeta)* clonada localmente en el *paso anterior*.
    3. Para cada problema, genere una clase/programa java independiente pero dentro del único proyecto (*Java App* creado en el *paso anterior*). No olvide nombrar cada clase con el número del problema y un nombre representativo de la solución. Ejemplo: ***Ejercicio01_AdivinaNumero***
    4. Finalizado el taller *(o cada ejercicio)*, sincronice los cambios de su **PC** local a este repositorio remoto de **GitHub**, con los comandos: `git add .` `git commit -m "Mensaje de la versión"` `git push`
* Verifique sus soluciones con las técnicas de compilación, ejecución y depurado de programas.
* Documente las soluciones con los bloques: (1.-) ***Documentación del problema***, y (2.-) ***Evidencia del funcionamiento y resultados***. Para ello, al inicio y final como parte de la codificación (en comentarios /** ), copiar y pegar el enunciado del problema, y al final, los resultados obtenidos de consola **RUN**. Ejemplo: 

```java
/**
 * Ejercicio 01: "Texto del enunciado del ejercicio/problema...."
 * @author NombreAutor
 * @version 1.0
 */

public class Ejercicio01_AdivinaNumero {
    //AQUÍ AGREGUE TODO SU CÓDIGO...
}

/***
 * EVIDENCIA DEL RUN:
 * Pegue aquí la evidencia de la ejecución del .java
 */
 ```

### Listado de problemáticas:
---

### Ejercicio01
---
**Adivina un número:** Dada la dinámica de juego computacional, programar una solución que genere un número entero aleatorio entre ***1-N***, y solicite al usuario lo adivine; dé pistas si es que el usuario falla, advirtiendo la cantidad de intentos restantes. Si es que no logra adivinar, muestre el mensaje **"GAME OVER"**. 

### Problema02
---
**Serie numérica 1:** Realizar un programa Java que permita presentar en pantalla la siguiente secuencia:

```
	1/10
	2/11
	3/12
	4/13
	5/14
	6/15
```

---

### Problema03
---
**Serie numérica 2:**  Realizar un programa Java que permita presentar en pantalla la siguiente secuencia:

```
	5/10
	10/12
	15/14
	20/16
	25/18
	30/20
```

---

### Problema04
---
**Nómina empresa:**  Realizar un programa Java que permita pedir por teclado el nombre de 5 empleados. Por cada empleado se debe solicitar el nombre, numero de días trabajados y costo del día trabajo. Calcular el valor a cancelar por la empresa para cada empleado. **Presentar un reporte como el siguiente:**

|  NOMBRE| NUMERO DE DÍAS TRABAJADOS | COSTO DEL DÍA| CANTIDAD A CANCELAR|
| --- | --- | ----- | --- |
| Nombre 1 | 10 |   $2.5 | $25 |
| Nombre 2 | 11 |   $2 | $22 |
| Nombre 3 |  9  |  $3  | $27 |
| Nombre 4 |  5  |   $4 | $20 |
| Nombre 5 | 12 |   $2 | $24 |

---

### Problema05
---
**Equipo de futbol:**  Generar una solución que permita ingresar jugadores de fútbol; por cada jugador se debe solicitar:

  -	Nombre el jugador
	- 	Posición en el campo de juego
	- 	Edad
	- 	Estatura

El ciclo de ingreso de información deberá terminar cuando el usuario lo decida. Se debe imprimir el siguiente reporte ***(usar una cadena de acumulación)***:

```
Listado de Jugadores
1. Alexander Dominguez -Arquero-, edad 32, estatura 1.95
2. Xavier Arreaga -Defensa-, edad 24, estatura 1.85
3. Moisés Caicedo -Mediocentro-, edad 19, estatura 1.88
4. Ángel Mena -Delantero-, edad 32, estatura 1.75
5. Michael Estrada -Delantero-, edad 27, estatura 1.93
Promedio de edades:  26.8
Promedio de estaturas: 1.87
```

---

### Problema06
---
**Reporte de notas:** Generar un programa Java que permita ingresar 4 estudiantes; por cada uno de ellos ingresar el nombre del estudiante, el promedio de ciclo. Presentar el siguiente reporte

| NOMBRE DEL ESTUDIANTE | PROMEDIO | ESTADO |
| --- | --- | ----- |
| Estudiante 1 | 10 |   Aprobado |
| Estudiante 2 | 6.9 |   Reprobado |
| Estudiante 3 | 7 |   Aprobado |
| Estudiante 4 | 5 |   Reprobado |

>**Atención**: con base al valor del promedio, usted debe asignar en cada registro el ESTADO de: ***Aprobado*** o ***Reprobado***.

---

### Problema07
---
**Factura de compras:** Una empresa de comercialización de computadoras realiza el proceso de venta haciendo un descuento por tipo de cliente:

- Si es cliente tipo 1 hay un descuento del 10%
- Si es cliente tipo 2 hay un descuento del 20%
- En caso que sea otro tipo de cliente, no hay descuento.

Generar un proceso que permita ingresar 7 ventas: por cada venta preguntar los siguiente datos:

- Nombre del cliente
- Costo de la computadora _(solo se vende una computadora por transacción)_
- Tipo de cliente

Presentar el siguiente reporte:

Cliente tipo 1, compra computadora con precio $100

---

### Problema08
---
**Serie numérica 3:** Generar e imprimir la siguiente serie y su sumatoria:
```
sumatoria = -(1/1)+(1/2)-(1/3)+(1/4)-(1/5)+(1/6)-(1/7)+(1/8)-(1/9)+(1/10)
```
