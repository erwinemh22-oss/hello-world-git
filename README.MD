# Cabeceras
# Cabecera H1 
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underline 1 casita
-----------

Underline 2 casita
============
# Formatos de enfacis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bol o strong**de la primera forma.
- formato __bol o strong__de la segunda forma.
- formato ~~tachado~~. formato normal.
- aqui podemos usar formato *italica*, pero tambien **bold** y ~~tachado~~

# listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
# listas desordenadas
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a haref="http://www.google.com">Este es un link en HTML<a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://cdn.pixabay.com/photo/2022/01/30/13/33/github-6980894_1280.png)

# Code snippets
 ```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
 ```
 Codigo en JavaScrip
 ```JavaScript
 function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}
 ```
 # Tablas
 | Nombre | Apellido | Documento |
 | ------ | -------- | --------- | 
 | Erwin | Miranda | 75896402|
 | Gessler | Miranda | 73948123|

  # Citas
  Esto es un texto referente que pondremos debajo:
  > Esto es una Cita.
  
  Esto es otro texto que no se relaciona con la cita Anterior.
  > Esto es otra Cita.

  # Lineas orizontales o Divisoras
  Esto es un texto que sera dividio por una linea divisora usando guiones

  ---
  Esto es otro texto dividido por una linea divisora usando asteriscos 

  ***
  Esto es otro texto dividido por una linea divisora usando guion bajo 

  ___

  # Saltos de linea
  Esto es nuestro primer parrafo.

  Esto es nuestro segundo parrafo.

  Esto es nuestro tercer parrafo.
  - Lista