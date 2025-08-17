# README

Markdown es un lenguaje de marcado ligero que permite formatear texto utilizando texto plano con una sintaxis sencilla y fácil de leer.

## Encabezados y listas ordenadas.
Para los encabezados se usan varios # en dependencia de que tipo de encabezado sea, para las listas ordenadas se antepone el número con un punto.

# 1. H1
## 2. H2
### 3. H3
#### 4. H4
##### 5. H5
###### 6. H6

## Tipos de texto y listas desordenadas
Para hacer listas desordenadas simplemente debe anteponerse un -, + o *.

- **Bold**: __Envolver entre__  ** o __.
+ *Italika*: _Envolver entre_  * o _.
* ~~Tachado~~: ~Envolver entre~ ~~ o ~. 
- ***Italika y bold***: ***Envolver entre*** ***.
+ <sub>Subscript:</sub> <sub>Envolver entre la etiqueta</sub> <sub>.
* <sup>Superscript:</sup> <sup>Envolver entre la etiqueta</sup> <sup>.
- <ins>Subrayado:</ins> <ins>Envolver entre la etiqueta</ins> <ins>.

## Entrecomillado
>Para entrecomillar texto solo se debe anteponer un >.

## Citado de código
Para citar código en medio de una línea se envuelve en backticks, como si quisiera decir `print()`.

Para que sea multilínea se envuelve en triple backticks.
```
const variable = 'Texto';
console.log(variable);
```

## Color
El texto se envuelve entre backticks se puede usar de varias formas, como:
* HEX: `#0969DA`
* RGB: `rgb(9, 105, 218)`
* HSL: `hsl(212, 92%, 45%)`

(Funciona en Issues,PRs y Discussions).

## Vínculos
Para crear vínculo se escribe el texto entre [] y enseguida el enlace entre (). [Pruébalo.](https://github.com/TuiCibrian)

También están los enlaces de sección y los vínculos relativos, para eso leer [aquí.](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links)

## Imágenes
Se usa ![](), dentro de los corchentes va un texto alternativo y en los paréntesis el enlace.
![Pingüino](https://www.faunia.es/content/dam/fau/images/descubre-faunia/planea-tu-visita/animales/aves/pingu%CC%88ino-papu%CC%81a/Pinguino-papua-Animales-Faunia-4.jpg)

## Listas anidadas
Simplemente con tab se pueden anidar listas
* Punto 1
    + Subpunto 1
        - Subpunto menor

## To-do list
Para tareas no completadas - [ ]:
- [ ] Tarea incompleta

Para completas -[x]:
- [x] Tarea completa

Si la descripción comienza por parétensis se usa \:

- [ ] \(Descripción que empieza con paréntesis.)

## Menciones
Se usa @nombreDeUsuario

## Notas al pie
Nota al pie[^1].

Segunda nota al pie[^2].

[^1]: Hola.
[^2]: Para toda la documentación oficial de Markdown presione [aquí.](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links)

## Alertas
> [!NOTE]
> Para poner notas se escribe '> [!NOTE]'

> [!TIP]
> Para poner tips se escribe '> [!TIP]'

> [!WARNING]
> Para poner advertencias se escribe '> [!WARNING]'

> [!CAUTION]
> Para poner precauciones se escribe '> [!CAUTION]'

<!--## Comentarios  -->

## Ignorar formato de Markdown
Usando \ antes del \*caracter\* de Markdown.

