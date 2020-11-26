# Fórmulas y funciones en Hojas de Cálculo en Google Drive

Gracias a las fórmulas y funciones podemos manejar los datos de manera eficiente. Sin éstas, nuestras hojas de cálculo serían como documentos de texto. Veamos la definición de cada una:

-   **Fórmulas**: expresiones matemáticas que, escritas en una celda, devuelven el resultado requerido en la propia celda.
-   **Funciones**: *Una función es una fórmula predefinida que realiza los cálculos utilizando valores específicos en un orden particular. Una de las principales ventajas es que ahorran tiempo porque ya no es necesario que la escribas tú mismo.* [Fuente: www.gcfaprendelibre.org](http://www.gcfaprendelibre.org/tecnologia/curso/microsoft_excel_2010/explora_las_funciones_basicas_de_excel_2010/1.do)

A continuación profundizaremos en la utilización de cada una.

## Creando fórmulas

Toda fórmula comienza con el símbolo = seguido de una expresión matemática. En dicha expresión utilizaremos casi siempre números mezclados con referencias a otras celdas para realizar nuestros cálculos. Los operadores matemáticos disponibles son los siguientes:
-   Suma +
-   Resta -
-   Multiplicación \*
-   División /
-   Exponente \^

Por supuesto, la complejidad de las funciones a utilizar puede variar. Si vamos a crear fórmulas más complejas conviene recordar el orden de las operaciones:

1.  Operaciones limitadas por paréntesis.
2.  Potencias.
3.  Multiplicaciones y divisiones.
4.  Suma y resta.

Recuerda que, ante operaciones del mismo nivel, éstas se realizan de izquierda a derecha.

Vamos con un ejemplo sencillo. En las celdas A1, A2 y A3 tienes losvalores 5 8 y 12 respectivamente. ¿Cuál sería el resultado de la siguiente fórmula escrita en A4? =3\*(A2-A1)\^2-A3. Vayamos por partes:
-   A2-A1 = 3
-   3\^2 = 9
-   3\*9 = 27
-   27-A3 = 15

![Ejemplo de fórmula](https://raw.githubusercontent.com/catedu/curso-google-drive/master/images/Creando_fórmulas.png)

**Un consejo**: no hace falta que escribas A2 cuando te toque ponerla en la función; clica sobre la celda y se incluirá automáticamente. En la imagen de la derecha puedes ver el ejemplo sobre la propia hoja de cálculo.

## Funciones

![Elementos de unafunción](https://raw.githubusercontent.com/catedu/curso-google-drive/master/images/Elementos_de_una_función.png)

Una función, al igual que las fórmulas, debe empezar con un signo =. Escribe después el nombre de la función y los argumentos, éstos últimos entre paréntesis. ¡Habrás creado tu primera función! Los valores o las celdas dentro de los paréntesis van separadas por *dos puntos*(:) o *punto y coma*(;).

![Uso de ; y : en funciones](https://raw.githubusercontent.com/catedu/curso-google-drive/master/images/Seleccionando_celdas_en_funciones.png)

-   *Dos puntos* crea una referencia a un rango de celdas. Por ejemplo, =SUM(A1:B3) sumará los datos existentes en las celdas A1,A2,A3,B1,B2 y B3.
-   *Punto y coma* separa valores individuales, referencias y rangos de celdas. Por ejemplo, =SUM(A1:A3;C1:C3;D4;4)

¿Quieres acceder a las funciones más utilizadas y muchas más? Pulsa en el botón de acceso rápido a las funciones ![Botón funciones](https://raw.githubusercontent.com/catedu/curso-google-drive/master/images/105px-Boton_funciones.png). Clicando sobre ellas las introducirás directamente en la celda. [En *Más funciones* podrás ver todas las que ofrece Hojas de Cálculo de Google.](https://support.google.com/docs/table/25273?hl=es%7C).

¿Sabías que puedes [dar nombre a un rango deceldas](https://support.google.com/docs/answer/63175?hl=es). Si lo haces tu función =AVERAGE(B2:B26) podría quedar así =AVERAGE(Notas)* *También puedes utilizar funciones dentro de otras funciones, es decir, [funciones anidadas](https://support.google.com/docs/answer/46977?hl=es)