# Testing con Junit

Este es un ejemplo sencillo de pruebas unitarias usando Junit 5

Observa que este proyecto no tiene ninguna clase con el método `main`, no nos hace falta. Además, tampoco tiene ningún `scanner` ni ningún `print`.

Haz un fork de este proyecto en tu repositorio de Github y contesta a las siguientes preguntas:

1. ¿Qué sentido puede tener este proyecto y para que lo podrías usar?
Este proyecto sirve para sumar y dividir numeros, si nos referimos a la prueba de caja negra, sirve para comprobar que estas opciones funcionan correctamente, sin esta prueba nos tirariamos horas para ver un simple error que no damos por hecho
2. Revisa las pruebas de la suma y comenta lo que te parezca de interés
En las pruebas de la suma veo que hay 4 pruebas, una de `"sumarPositivos"`, otra de `sumarPositivosMal`, `sumar`y `dividirPorZeroExcepcion`, veo que en la prueba sumar positivos mal, da error porque al ejecutarla se espera un 4 pero en realidad da un 5.
3. Realiza un estudio de caja negra de la división e implementa las pruebas en junit: Se realizará en markdown.
Para hacer la prueba he añadido unos métodos más para comprobar que la division funcionara con negativos y positivos.

## Instrucciones

El alumno deberá hacer un fork de este proyecto e implementar la solución solicitada (preguntas y código).

>Se deberá utilizar este fichero, y los artefactos de código del proyecto, para resolver el ejercicio.


**Si no se puede acceder al repositorio la evaluación del ejercicio será de 0. No se evaluarán entregas modificadas/entregadas fuera del plazo establecido en la tarea**