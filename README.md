# Dashboard contador de filas de Excel

## Qué construí
Una aplicación web contenida en un único archivo HTML. Sirve para cargar un archivo Excel de forma local y visualizar en un dashboard la cantidad de filas que tiene cada hoja (ignorando las hojas ocultas). 

## Cómo se lo pedí
1. "tengo un archivo excel q tiene un monton de sheets quiero un dashboard, q me me muestre un count de filas q tiene cada sheet"
2. "bueno, podemos hacer que le ponga . como separador de miles, y ademas q no contemple las sheets ocultas"
3. "y la palabra fila repetida, ensucia, pongamoslo arriba, pero despues en los cuadrados, solo el numero"

## Qué funciona
La interfaz web funciona correctamente en el navegador. Al subir un archivo Excel, la librería lee los datos localmente, cuenta las filas, filtra las hojas ocultas y muestra los números con formato de miles en las tarjetas.

## Qué falta o qué falló
No hubo errores técnicos graves durante la programación, pero sí hubo que iterar el diseño visual inicial porque la palabra "filas" se repetía en cada tarjeta y ensuciaba la lectura, lo cual se corrigió en el último prompt. 

## Qué aprendí
Justo estaba haciendo un informe sobre la base de datos de usuarios de mi trabajo, y la segmentación me quedo en diferentes sheets. Hacer el count me hubiese llevado tiempo o usar algunas formulas. Con esto, se resolvió muy rápido, para cualquier archivo, y además tengo un tablero para mostrar.
