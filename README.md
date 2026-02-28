# Testing con Junit

Este es un ejemplo sencillo de pruebas unitarias usando Junit 5

Observa que este proyecto no tiene ninguna clase con el método `main`, no nos hace fatal. Además, tampoco tiene ningún `scanner` ni ningún `print`.

Haz un fork de este proyecto en tu repositorio de Github y contesta a las siguientes preguntas:

1. ¿Qué sentido puede tener este proyecto y para que lo podrías usar?
    Creo que si tiene sentido dentro de una empresa, porque te deja practicar todo el desarrollo que estamos practicando ahora. Además creo que se podria enseñar al cliente como una prueba de que nuestros desarrollos sí funcionan, y creo que la calculadora es fácil de entender para un cliente. 
2. Revisa las pruebas de la suma y comenta lo que te parezca de interés
    En CalculadoraTest, hay tres pruebas de "Suma", una que corresponde a sumarPositivos, como un método que funciona correctamente, mientras que sumarPositivosMal, no lo hace correctamente porque el resultado esperado no es 4. Abajo puedo ver lo que se le podría llamar un conjunto de pruebas a mi parecer, me parece curioso ya que solo con un metodo puedes hacer muchisimas pruebas (obviamente creo que hay conjuntos de pruebas MUCHISIMO más grandes), entonces las posibilidades de esto me parecen increibles e ilimitadas.
3. Realiza un estudio de caja negra de la división e implementa las pruebas en junit: Se realizará en markdown.
Para las pruebas, he hecho una de dividirPositivos, dividirNegativos, dividirNegativoPositivo y dividirPositivoNegativo, estas dos ultimas son las que creo que son más importantes, ya que depende de donde pongas el número a dividir te da un resultado u otro, taambién, me he quedado pensando lo de throws OperacionNoValidaException, y he llegado a la conclusion de que hay que ponerla en los metodos de dividir ya que el método tiene que "entender" que no se puede dividir por 0, por esa Excepcion he supuesto que no hacia falta hacer un método a parte para dividir 0/0 y que de error.  




## Instrucciones

El alumno deberá hacer un fork de este proyecto e implementar la solución solicitada (preguntas y código).

>Se deberá utilizar este fichero, y los artefactos de código del proyecto, para resolver el ejercicio.


**Si no se puede acceder al repositorio la evaluación del ejercicio será de 0. No se evaluarán entregas modificadas/entregadas fuera del plazo establecido en la tarea**