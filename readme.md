# Cabeceras
# cabecera h1
## cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

# underlines
Underline 1
------------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~. 
- aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada. 
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item desordenado. 
- Esto es un item desordenado.
- Esto es un item desordenado.

# Links
- <a href="http://www.google.com">Esto es un link en HTML</a>
- [Esto es un link en Markdown](http://www.google.com)

# Imagenes
![Logo gitHub](https://1000marcas.net/wp-content/uploads/2020/02/GitHub-Logo.jpg)

# code snippets
codigo JSON
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

codigo JAVASCRIPT
```Javascript
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

export  $initHighlight;
```

# tablas

| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Maxi   | Burgos   | 2353      |   
| Tomas  | Tompson  | 4535      |

# citas
Esto es un texto referente a una cita que pondremos debajo.
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.

# Lineas divisoras
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otr texto divididos por guiones bajos

___

# saltos de linea
Esto es nuestri primero parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.