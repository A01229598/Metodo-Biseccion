# Metodo-Biseccion
Este es uno de los métodos más sencillos y de fácil intuición para resolver ecuaciones en una variable, también conocido como Método de Intervalo Medio.1 Se basa en el teorema del valor intermedio (TVI), el cual establece que toda función continua f en un intervalo cerrado [a,b] toma todos los valores que se hallan entre f(a) y f(b). Esto es que todo valor entre f(a) y f(b) es la imagen de al menos un valor en el intervalo [a,b]. En caso de que f(a) y f(b) tengan signos opuestos, el valor cero sería un valor intermedio entre f(a) y f(b), por lo que con certeza existe un p en [a,b] que cumple f(p)=0. De esta forma, se asegura la existencia de al menos una solución de la ecuación f(x)=0.

El método consiste en lo siguiente:

Debe existir seguridad sobre la continuidad de la función f(x) en el intervalo [a,b]
A continuación se verifica que f(a)f(b)<0
Se calcula el punto medio m del intervalo [a,b] y se evalúa f(m) si ese valor es igual a cero, ya hemos encontrado la raíz buscada
En caso de que no lo sea, verificamos si f(m) tiene signo opuesto con f(a) o con f(b)
Se redefine el intervalo [a, b] como [a, m] ó [m, b] según se haya determinado en cuál de estos intervalos ocurre un cambio de signo
Con este nuevo intervalo se continúa sucesivamente encerrando la solución en un intervalo cada vez más pequeño, hasta alcanzar la precisión deseada
