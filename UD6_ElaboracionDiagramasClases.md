# UD6 - Elaboración de diagramas de clases

- [UD6 - Elaboración de diagramas de clases](#ud6---elaboración-de-diagramas-de-clases)
  - [1. Conceptos básicos de la orientación a objetos](#1-conceptos-básicos-de-la-orientación-a-objetos)
  - [2. UML](#2-uml)
  - [3. Clases, atributos, métodos y visibilidad](#3-clases-atributos-métodos-y-visibilidad)
  - [4. Relaciones entre clases](#4-relaciones-entre-clases)
  - [5. Tipos de clases de análisis](#5-tipos-de-clases-de-análisis)
  - [6. Herramientas para la creación de diagramas de clases](#6-herramientas-para-la-creación-de-diagramas-de-clases)
  - [7. Generación de código a partir de diagramas de clases](#7-generación-de-código-a-partir-de-diagramas-de-clases)
  - [8. Generación de diagramas de clases a partir de código (ingeniería inversa)](#8-generación-de-diagramas-de-clases-a-partir-de-código-ingeniería-inversa)

El proceso de construcción de software tiene como finalidad solucionar problemas utilizando herramientas informáticas y, para obtener buenos resultados, requiere un proceso previo de análisis y especificación de requisitos. La programación orientada a objetos se enfoca en simular elementos de la realidad del problema de manera cercana a través de la abstracción de objetos. Estos objetos se caracterizan por tener un conjunto de atributos que los definen y un conjunto de operaciones que marcan su comportamiento.

## 1. Conceptos básicos de la orientación a objetos

Claves de la programación orientada a objetos:
- **Abstracción**: permite modelar la realidad mediante la creación de clases que capturan características y comportamientos similares.
- **Encapsulación**: reúne elementos relacionados en un mismo nivel de abstracción, aumentando la cohesión de los componentes del sistema.
- **Modularidad**: permite dividir una aplicación en partes independientes y reducir su complejidad.
- **Principio de ocultación**: limita el acceso a ciertas propiedades de los objetos, reduciendo la propagación de efectos colaterales cuando se producen cambios.
- **Herencia**: permite que los objetos utilicen las propiedades y comportamientos de otros objetos, formando una jerarquía.
- **Polimorfismo**: agrupa comportamientos diferentes bajo el mismo nombre, seleccionando uno u otro dependiendo del objeto que lo ejecute.
- **Recolección de basura**: se encarga de destruir automáticamente los objetos sin referencia, desvinculando su memoria asociada.

El paradigma de programación orientada a objetos tiene diversas **ventajas** en el desarrollo de software en comparación con otros paradigmas:

- Permite un desarrollo más rápido, económico y de mayor calidad gracias a la reutilización de código modular, lo que facilita la creación de aplicaciones similares y la reutilización de código.
- Mejora la calidad del sistema al hacerlo más extensible y permitir la fácil modificación de la funcionalidad de la aplicación a través de la modificación de operaciones.
- Es más fácil de modificar y mantener debido a la modularidad y encapsulación de objetos con responsabilidades independientes y claramente definidas.
- Facilita la adaptación y escalabilidad de las aplicaciones gracias a la capacidad de modificar la estructura y el comportamiento de los objetos sin tener que cambiar la aplicación completa.

## 2. UML


## 3. Clases, atributos, métodos y visibilidad

Los propósitos de una clase son definir las abstracciones y favorecer la modularidad. Una clase se describe por un conjunto de elementos que se denominan miembros y que son:
- Nombre.
- Atributos: conjunto de características asociadas a una clase. Pueden verse como una relación binaria entre una clase y cierto dominio formado por todos los posibles valores que puede tomar cada atributo. Cuando toman valores concretos dentro de su dominio definen el estado del objeto. Se definen por su nombre y su tipo, que puede ser simple o compuesto como otra clase.
- Protocolo: Operaciones (métodos, mensajes) que manipulan el estado. Un método es el procedimiento o función que se invoca para actuar sobre un objeto. Un mensaje es el resultado de cierta acción efectuada por un objeto. Los métodos determinan como actúan los objetos cuando reciben un mensaje, es decir, cuando se requiere que el objeto realice una acción descrita en un método se le envía un mensaje. El conjunto de mensajes a los cuales puede responder un objeto se le conoce como protocolo del objeto.

![](img/POO.png)

## 4. Relaciones entre clases


## 5. Tipos de clases de análisis


## 6. Herramientas para la creación de diagramas de clases


## 7. Generación de código a partir de diagramas de clases


## 8. Generación de diagramas de clases a partir de código (ingeniería inversa)

