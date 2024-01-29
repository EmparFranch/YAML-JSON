# **_YAML-JSON_**

A continuación, vamos a realizar una breve explicación sobre qué es YAML y otra sobre qué es JSON.

![Imagen 1](https://i.stack.imgur.com/1Gja6.png)


Breve explicación sobre **YAML** 

[YAML](https://en.wikipedia.org/wiki/YAML) es un formato de serialización de datos _legible por humanos_ y de fácil escritura. Aunquese desarrolló para usarse con lenguajes de programación como Python o Perl, actualmente, se utiliza para la configuración, intercambio de datos y archivos de configuración en diversas aplicaciones.
>Es comúnmente en la configuración de aplicaciones y flujos de trabajo.

## Características principales

**-Sintaxis Simple:** sintaxis simple que permite la lectura humana.

**-Estructura datos:** permite datos como listas, diccionarios (o mapeos) y enteros, flotantes, cadenas de texto y null.

**-Listas y Mapeos:** Mediante líneas con guiones y mapeos se representan con pares clave y valor.ç

**-Identación:** Para identificar la estructura jerárquica de los datos.

**-Comentarios:** Agrega comentarios utilizando '#'.

**-Herencia y anclaje:** Permite la herencia y el anclaje de datos para reutilizar valores.

**-Tipos multimedia**

## Usos comunes

**-Archivos de configuración** para aplicaciones y servicios.

**-Intercambio de datos** ya que es facilmente legible por las personas.

**-Herramientas de utomatización y orquestación** como en Ansible para describir la configuración y las tareas.

**-Escribir documentación** bien estructurada y legible.


## Ejemplo YAML

```YAML

Nombre: Empar

Edad: 33

Ciudad: Polinyà

Oficio: Orientadora laboral

Intereses:

-Padel

-Leer

-Programar con Java

```

Breve explicación sobre **JSON** 

[JSON](https://en.wikipedia.org/wiki/JSON) es un formato de intercambio de datos usado para representar información estructurada de manera legible por humanos. Aunque se desarrolló en JavaScript, hoy en día es un formato independiente del lenguaje. JSON es conocido por su simplicidad y flexibilidad.
>Es conocido por su simplicidad y facilidad de interpretación.

## Características principales

**-Sintaxis Simple:** Basada en pares clave-valor (separados por dos puntos : y los elementos se separan por comas ,.).

**-Estructura de Datos:** A
dmite objetos (conjuntos de pares clave-valor), arrays (listas ordenadas de valores), y tipos escalares como números, cadenas de texto, booleanos y null.

**-Anidamiento:** Ppermite anidar estructuras de datos dentro de otras.

**-Arrays:** Representados mediante corchetes [] y pueden contener cualquier tipo de dato.

**-Formato de Cadena de Texto:** Van entre comillas dobles.

## Usos comunes

**-Intercambio de Datos** entre un servidor y un cliente en aplicaciones web y servicios web.

**-Configuración y Almacenamiento de Datos** en sistemas y aplicaciones.

**-APIs** para la transmisión de datos debido a su legibilidad y estructura simple.
 
**-Persistencia de Datos en NoSQL** en bases de datos NoSQL, para almacenar datos en formato de documento.

**-Configuración de Servicios Web** 

## Ejemplo JSON

```JSON

{
  "Nombre": "Empar",
  "Edad": 33,
  "Ciudad": "Polinyà",
  "Oficio": "Orientadora laboral"
  "Intereses": [
    "Padel",
    "Leer",
    "Programar con Java"
  ]
}
```


## CONCLUSIÓN

>Ambos formatos para la serialización de datos tienen fortalezas y debilidades y se utilizan según el contexto, las necesidades
>de la aplicación o del proyecto y la compatibilidad con el lenguaje utiizado, puesto que los dos, son fáciles y legigles.
>Elegir uno u otro depende de los requisitos del proyecto o aplicación y se utilizan en el desarrollo de softwares y también
>para la trasmisión de datos en la web.

