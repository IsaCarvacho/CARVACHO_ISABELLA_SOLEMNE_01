# CARVACHO_ISABELLA_SOLEMNE_01

## Solemne 01 Pensamiento Computacional

### La artista
La artista que elegí para este cuadro fue ***@the_oblivious_mind*** en instagram. Su trabajo consta de usar todo el lienzo con distintas figuras y técnicas artísticas. Sus cuadros tiene riqueza de texturas, colores, formas e incluso volúmenes.

### Su trabajo
![The Oblivious Mind](https://i0.wp.com/breathethinklove.com/wp-content/uploads/2025/04/the-oblivious-mind1-2-edited.jpg?resize=968%2C968&ssl=1)

__Haz click en la imagen para conocer más de su trabajo__
[![Link](https://i.pinimg.com/736x/0f/82/ba/0f82ba20fdeaeb3177f44c0726dae434.jpg)](https://www.instagram.com/the_oblivious_mind?igsh=MTJsaXI0ZW9sczc5ZQ==)

### Mi reversión de la artista
Para mi trabajo busqué imitar la variedad de figuras, los círculos de borde negro con figuras adentro y sectorización de las figuras. Pero manteniendo una paleta de colores dentro de los azules por gusto personal y para diferenciarlo del trabajo de la artista. 

### Proceso de creación
Comencé por los elementos que consideraba más importantes, los círculos de borde negro. Ya que para mi con estos se puede generar un orden dentro del lienzo y ver si las proporciones estan correctas. 

![1](https://i.pinimg.com/736x/42/dd/d2/42ddd2d52df52d491b4468ffc6f62621.jpg)

Luego la generación de las líneas horizontales y verticales para poder diagramar mejor el lienzo. Después comencé a generar las figuras de arriba hacia abajo.

![2](https://i.pinimg.com/736x/0b/63/34/0b633478750ae3b0103e6a9741558bf6.jpg)

En la parte inferior generé las figuras de izquierda a derecha para poder facilitar la generación de las nuevas a través de sumas
y restas según cuanto se movia el x y el y. Dejé los triángulos que se encuentran dentro del círculo para el final. 

![4](https://i.pinimg.com/736x/0b/63/34/0b633478750ae3b0103e6a9741558bf6.jpg)

### Problemas en el proceso
Durante el proceso lo más difícil fue la generación de arcos, por los angulos que se necesitaban, los cuadriláteros, por ser irregulares pero al mismo tiempo debían ser simétricos, y además los triángulos de adentro de los círculos, ya que la mitad tenía la totalidad de sus datos diferente
entre sí. Para estos problemas solo fue ir probando dato a dato cuanto se movia con x número, también recordar que cada dato tenía su función, por ejemplo si la figura estaba muy angosta, y necesitaba que fuera más gruesa, no era necesario tocar el x,y. 

Otro problema fue fuera de lo que es programar en si, a veces por error mio, o tratando de mdificar la figura, borraba algunos datos y de memoria no me los sabía, pero para eso por suerte llevaba una nota en mi celular donde rellenaba todos los datos en paralelo. 

### Códigos usados (Junto con su comentario)

1. createCanvas(x1,x2): Crear el lienzo. Valores corresponden a ancho y alto
2. background(x1,x2,x3): Código de color del lienzo
3. angleMode(DEGREES): Cambia la ubicación del grado 0° a la derecha al centro para la construcción de arcos
4. stroke(x): Definir un borde con código de color para las siguientes figuras
10. noStroke(): Se asigna para que la figura no tenga borde
11. strokeWeight(x): /Asignarle un grosor x para el borde de las siguientes figuras
12. strokeCap(ROUND/SQUARE/PROJECT);//Define la forma final del borde
13. fill(x1, x2, x3): Rellenar con código de color las siguientes figuras
14.  noFill(): Quitar el relleno de las siguientes figuras
5. line(x1,y1,x2,y2); Generar una línea. x e y indican el inicio y final de la línea
6. rect(x,y,ancho,alto): Rectángulo. x e y corresponde a la esquina superior izquierda. Siguiente par de números corresponde a ancho y alto
7. circle(x,y,diámetro): Círculo perfecto. x e y del centro de la figura, luego diámetro
8. triangle(x1,y1,x2,y2,x3,y3): Triángulo. Cada par de números corresponde al x,y de cada esquina
9. quad(x1,y2,x2,y2,x3,y3,x4,y4): Generar un cuadrilátero. Cada par de números corresponde a una esquina del cuadrilátero
15.  arc(x,y,w,h,start,stop): Primer par corresponde a x e y, centro del circulo en que está inscrito el arco. Segundo par son w y h, ancho y alto. Tercer par son start y stop, donde incia los ángulos del arco

### Resultado del ***Coding***

**Haz click en la imagen para ir a mi proyecto en Github**

[![Proyecto](https://i.pinimg.com/736x/be/d2/99/bed299d0b2b2acba5ccacba65cf0369f.jpg)](https://editor.p5js.org/IsaCarvacho/sketches/ACN_n__FO)

