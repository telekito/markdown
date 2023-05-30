# Sintaxis avanzada

Además de la sintaxis básica de Markdown, hay algunas funcionalidades avanzadas que puedes utilizar para hacer que tus documentos sean más interesantes y legibles. En esta sección, aprenderás sobre algunas de estas funcionalidades.

- [Sintaxis avanzada](#sintaxis-avanzada)
  - [Imágenes](#imágenes)
  - [Tablas](#tablas)
  - [Alineación en Tablas](#alineación-en-tablas)
  - [Código](#código)


--------------
--------------
## Imágenes
En Markdown, puedes agregar imágenes a tus documentos utilizando el siguiente formato:

```markdown
![texto alternativo de la imagen](URL de la imagen)
```

El texto alternativo es una descripción de la imagen que se mostrará si la imagen no se puede cargar por algún motivo. Por ejemplo:

![Logo de Insight]()

![Logo de Insight](images/Insight-Logo.png)

```markdown
!![Logo de Insight](images/Insight-Logo.png)
![Logo de Insight]()
```

--------------
--------------

## Tablas
En Markdown, puedes crear tablas utilizando barras verticales (|) y guiones (-). El primer renglón de la tabla es el encabezado, y los siguientes renglones son las filas de la tabla. Por ejemplo:

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| ------------ | ------------ | ------------ |
| Fila 1, Col 1 | Fila 1, Col 2 | Fila 1, Col 3 |
| Fila 2, Col 1 | Fila 2, Col 2 | Fila 2, Col 3 |

```markdown
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| ------------ | ------------ | ------------ |
| Fila 1, Col 1 | Fila 1, Col 2 | Fila 1, Col 3 |
| Fila 2, Col 1 | Fila 2, Col 2 | Fila 2, Col 3 |
```

--------------
--------------

## Alineación en Tablas

En Markdown, también puedes alinear el contenido de las celdas de tus tablas. Puedes especificar la alineación usando los siguientes caracteres:

- :- para alinear a la izquierda y agregar una línea debajo del encabezado
- :-: para centrar
- -: para alinear a la derecha y agregar una línea debajo del encabezado
Por ejemplo, aquí hay una tabla con diferentes alineaciones:

| Nombre     | Apellido    | Edad |
| :--------- | :---------: | ---: |
| Juan       | Pérez       |  25  |
| Ana        | García      |  30  |
| José       | Rodríguez   |  28  |

```markdown
| Nombre     | Apellido    | Edad |
| :--------- | :---------: | ---: |
| Juan       | Pérez       |  25  |
| Ana        | García      |  30  |
| José       | Rodríguez   |  28  |
```
--------------
--------------

## Código
En Markdown, puedes resaltar el código utilizando comillas invertidas (`) para el código en línea, o tres comillas invertidas consecutivas (```) para bloques de código. Por ejemplo:

Código en línea: 

`print("Hola, mundo")`
```markdown
`print("Hola, mundo")`
```


Bloque de código:
```dotnet
static void Main(string[] args)
{
    Console.WriteLine("Código de ejemplo");
}
```

```markdown
```dotnet
static void Main(string[] args)
{
    Console.WriteLine("Código de ejemplo");
}
\```
```



[Volver](README.md)