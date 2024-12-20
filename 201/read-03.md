# CSS Layout  

## 1.¿Qué es el box model en CSS y cuáles son sus componentes principales?

el box model define la funció de las diferentes partes de una caja para crear una caja que puedas ver en tu página. Sus componentes son: margen, borde, relleno y contenido. 

## 2.¿Cuál es la diferencia entre box-sizing: content-box y box-sizing: border-box, y cómo afecta esto al diseño de una página web?

box-sizing:content-box solo incluye el contenido a comparación de box-sizing: border-box que incluye el contenido, el relleno y el borde.

Con content-box es posible que tus elementos ocupen mas espacio por si tienen bordes y relleno.
Con border-box los elementos siempre respetaran su tamaño total definido lo que evitará problemas de alineación.

## 3.¿Cuáles son las propiedades principales que se utilizan para configurar un contenedor flex y cómo afectan la disposición de los elementos dentro de él?

- display:flex
- justify-content 
- align-items 

Permiten organizar los elementos en columna.

## 4.¿Cómo se utiliza la propiedad flex para controlar el tamaño y el crecimiento de los elementos flexibles dentro de un contenedor? 

- flex-basis: Especifica el tamaño flexible. 
- flex-shrink: Especifica como se reducira el elemento en relación con el resto de los artículos flex.
- flex-grow: Especifica el factor de crecimiento del espacio restante dentro del contenedor. 

## 5.¿Cuáles son las diferencias entre los formatos de color RGB, RGBA, hexadecimal y HSL en CSS, y en qué situaciones sería más conveniente utilizar cada uno?

- RGB: Es preciso y facil de trabajar con valores exactos. Lo usaria en situaciones donde requiera colores exactos.
- RGBA: Añade transparencia al RGB. Lo usaria cuando quiera ponerle capa superpuestas o efectos de opacidad. 
- Hexadecimal: Compacto y ampliamente compatible. 
- HSL: Soporta transparencoa y es intuitivo al crear variacion de colores.


