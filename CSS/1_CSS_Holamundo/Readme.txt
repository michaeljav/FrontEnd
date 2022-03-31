https://www.youtube.com/watch?v=wZniZEbPAzk&ab_channel=HolaMundo

resumen important
12:39 Selectores (.class #id)
23:37 Comentarios (/**/)
25:44 Colores (#000,#000000,rgb(),rgba(),opacity(transparence0-1))
32:00 Border(-style,-color,)
34:41 Border en profundidad
37:21 Unidades de medida
44:19 Background
56:11 Box model, margin, padding, overflow
01:04:56 outline, text-align, text-decoration, text-shadow
01:08:52 Fuentes custom
01:11:34 Links y sus estados
01:15:15 Listas
01:18:48 Tablas
01:24:13 Display, max-width y position
01:35:01 Float
01:43:11 inline-block
01:45:19 Centrar un elemento


+++++++CARGAR ARCHIVO STYLE CSScss dentro de la etiqueta html
style dentro del archivo html
archivo externo
++++++++SELECTORES
tag html(p,div,etc)
id #
class . 
div p "hijos de div "
div h2, div h3
* "solo reemplaza colores si no han sido definido por otra propiedad de color"

+++++++COMENTARIO
//
/**/
+++++++COLOR
color:
>6 y 3 caracteres. La usencia de todos los colores
      es el negro y presencia de todos los colores es el blanco 
>Hexadecimal y RGB
>>Hexadecimal -> rango 0 negro-f rojo
color: #000; 
>Primer digito f=rojo
>Segundo digito f=verde
>tercer digito f=azul
color:#000000
>2 Primeros digito f=rojo
>2 Segundos digito f=verde
>2 terceros digito f=azul
>>RGB
>rango 0-255
>color:rgb(rojo,verde,azul)
>color:rgba(red,green,blue,transparence)
>intensidad o transparencia de 0(transparence) to 1 (solido)
>la transparencia permite que se vean elementos detras de el
>opacity: 0(transparence) to 1 (solido) -transparencia del elemento completo
++++++++BORDER A ELEMENTOS HTML
>borders:5px black dotted
>>grosor del border
>>color
>>style del border.-
>>>doted,dashed,solid,double,groove,ridge,inset,outset,none,hidden
>>>(groove,ridge,inset,outset)asignados a valores tridimencionales
>>border-style: profundidad
>>border-color:
>>border-radious
>>border-width
+++++UNIDAD DE MEDIDA
>>>Medidas absolutas que no van a cambiar 
>Pixel:equivale a uno o mas pixel de la pantalla. unpixel xvale a a 4 de las luces
>1cm : centimetro
>5mm:milimetro, mitad de un centrimerro
>1in: pulgada
>1pt: punto, un 72 abo de pultadas
>pc: picas, 12 puntos
>>>Medidas relativas:
>>en estas medidas se toma como base un elemento. Ejemplo : el >>tamano de la fuenta que posee la etiqueta HTML 
>2em: 2 veces el tamano de la fuente (font-size:--) del padre que lo contiene.
>2rem: relativo pero al tamaño de la fuente del elemento raiz el cual es HTML. Por defecto  el tamano es de 16px. 1rem =16px, 2rem =32px, so on
++++++BACKGOUND
>background-color:
>background-image: url('/img/coffe.png')
>background-size: auto,cover,contain: el valor que debe tener de manera automatica
+++++++MARGIN
>son espacios fuera del elemento
+++++++PADDING
>escio dentro del elemento
++++++Overflow
>por default is visible
+++++BOX MODEL CSScss /*No contempla ni el paddin border ni margin por lo cual para identificar el tamano de un elemento hay que sumar el ancho del  padding border marging*/
>Overflow:visible(default content in the box),hidden,scroll
>outline: un border fuera del border y antes del margin y tiene las mismas propiedades que el borde.
++++++TEXT-ALIGN
>/* text-align: left; default value */
> /* text-align: center; */
>/* text-align: right; */
>/* text-align: justify;
>text-decoration:none; default
>text-decoration: underline; */
> text-decoration: line-through;
> text-decoration: overline;
> text-shadow:3px 5px 4px blue ;
 >text-shadow: moveToRight,movoToBottom, blur o difuminado, color; 






