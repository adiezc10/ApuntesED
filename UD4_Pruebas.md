# UD4 - Diseño y realización de pruebas

- [UD4 - Diseño y realización de pruebas](#ud4---diseño-y-realización-de-pruebas)
  - [1. Introducción a las pruebas de software](#1-introducción-a-las-pruebas-de-software)
  - [2. Estrategia de las pruebas de software](#2-estrategia-de-las-pruebas-de-software)
    - [2.1. Pruebas unitarias](#21-pruebas-unitarias)
    - [2.2. Pruebas de integración](#22-pruebas-de-integración)
    - [2.3. Pruebas de sistema](#23-pruebas-de-sistema)
    - [2.4. Pruebas de validación](#24-pruebas-de-validación)
  - [3. Diseño de casos de prueba](#3-diseño-de-casos-de-prueba)
    - [3.1. Pruebas estructurales o de caja blanca](#31-pruebas-estructurales-o-de-caja-blanca)
      - [Prueba de camino básico](#prueba-de-camino-básico)
      - [Prueba de bucles](#prueba-de-bucles)
      - [Prueba de flujo de datos](#prueba-de-flujo-de-datos)
    - [3.2. Pruebas funcionales o de caja negra](#32-pruebas-funcionales-o-de-caja-negra)
      - [Particiones](#particiones)
      - [Análisis de valores límite](#análisis-de-valores-límite)
      - [Conjetura de errores](#conjetura-de-errores)
    - [3.3. Aplicación de las técnicas de dinseño de casos de prueba](#33-aplicación-de-las-técnicas-de-dinseño-de-casos-de-prueba)
  - [4. Documentación de pruebas](#4-documentación-de-pruebas)
  - [5. Herramientas de depuración](#5-herramientas-de-depuración)
  - [6. Pruebas automáticas](#6-pruebas-automáticas)
    - [6.1. Tratamiento de excepciones](#61-tratamiento-de-excepciones)
    - [6.2. Anotaciones](#62-anotaciones)
    - [6.3. Análisis de resultados](#63-análisis-de-resultados)

-------------------------------------------
- Depuración = debugger
- Caja blanca = caminos básicos, tablas de decisión y casos de prueba
- Caja negra = partición equivalente y tablas de casos de prueba
- Combinar caja blanca y caja negra
- Pruebas de rendimiento: Junit 5
-----------------------------------

## 1. Introducción a las pruebas de software
Las pruebas de software forman parte de una de las fases del ciclo de vida del software y tratan de detectar defectos cometidos en fases anteriores.

El objetivo de las pruebas de software es la validación y verificación del mismo. 
- **Validación**: se realiza al finalizar por completo el desarrollo para determinar si satisfacen los requisitos especificados. 
- **Verificación**: se realiza al final de cada fase para comprobar el cumplimiento de los requisitos de esa fase.

> **Ejemplo de la importancia de realizar pruebas de código**
> 
> ARIANE 5 es un cohetede un solo uso diseñado para colocar satélites en órbita geoestacionaria y para enviar cargas a órbitas bajas. El vuelo 501 (04/06/1996) fue la primera prueba de vuelo del sistema de lanzamiento del Ariane 5. Fracasó porque 37 segundos después del lanzamiento, la lanzadera explotó debido al mal funcionamiento del software de control. El motivo de la explosión fue un fallo de software, el módulo de control no se había probado lo suficiente.
>
> Vídeo: [TBT Launch: Ariane 5 Flight 501 (6-4-1996)](https://www.youtube.com/watch?v=fCnO-UYF3co).

Esisten dos aspectos a los que hay que prestar atención para realizar pruebas en el software, en ellos hay que considerar:
1. La **estrategia de aplicación de las pruebas**, donde se fijan los elementos que van testear. (Punto 2 de esta unidad)
2. Las **técnicas de diseño de casos de prueba** que se van a utilizar para cada uno de los elementos seleccionados. (Punto 3 de esta unidad)

Otro concepto importante relacionado con las pruebas de código es la **depuración**, que es el proceso de identificar y corregir errores de programación.​ Es conocido también por el término inglés _debugging_, cuyo significado es "eliminación de bugs", manera en que se conoce informalmente a los errores de programación.

## 2. Estrategia de las pruebas de software
Las pruebas siempre se empiezan porlas partes pequeñas de la aplicación y se va incrementando poco a poco el alcance. Las pruebas que se suelen realizar son unitarias, de integración, de sistema y de validación y suelen realizarse secuencialmente.

### 2.1. Pruebas unitarias
Las pruebas unitarias son las primeras a las que se somete nuestro software y prueban las clases u objetos de nuestro código. En programación orientada a objetos, además de las clases tendremos que probar los métodos individualmente.

### 2.2. Pruebas de integración
En las pruebas de integración se comprueba si las clases que forman nuestro programa funcionan correctamente cuando interactuan. Se pueden realizar siguiendo dos estrategias diferentes:
- Prueba basada en hebra: integra el conjunto de clasees requeridas para responder a una entrada concreta.
- Prueba basada en uso: primero prueba el funcionamiento de las clases independientes y después el de las dependientes de las anteriores.

### 2.3. Pruebas de sistema
Las pruebas de sistema comprueban el funcionamiento de un sistema integrado de hardware y software para comprobar si cumplpe los requisitos especificados. Se comprueban los requisitos funcionales y no funcionales, la documentación de usuario y el rendimiento del programa.

Las pruebas de sistema se pueden agrupar en:
- Pruebas de recuperación: 
- Pruebas de seguridad: 
- Pruebas de esfuerzo:
- Pruebas de rendimiento:
- Pruebas de despliegue:

### 2.4. Pruebas de validación
Modelo en V

## 3. Diseño de casos de prueba


> Práctica 1: caja blanca

### 3.1. Pruebas estructurales o de caja blanca

#### Prueba de camino básico

#### Prueba de bucles

#### Prueba de flujo de datos


### 3.2. Pruebas funcionales o de caja negra

> Práctica 2: caja negra

#### Particiones

#### Análisis de valores límite

#### Conjetura de errores

### 3.3. Aplicación de las técnicas de dinseño de casos de prueba

> Practica 3: combinar caja blanca y negra

## 4. Documentación de pruebas


## 5. Herramientas de depuración

> Práctica 4: debugger

## 6. Pruebas automáticas

Práctica 5: JUnit 5 

### 6.1. Tratamiento de excepciones

### 6.2. Anotaciones

### 6.3. Análisis de resultados
