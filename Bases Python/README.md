# Bases de Python
Es importante entender las bases del lenguaje de programación Python para poder trabajar de mejor manera con todos los analisis y procesos que aplicaremosa los diferentes datos, como por ejemplo:

##1. Ciclos: For y While
Son estructuras que permiten repetir un bloque de código múltiples veces.

For: Se usa cuando sabes cuántas veces quieres repetir algo o para recorrer elementos (como una lista de precios de acciones de Disney o Walmart).

While: Se ejecuta mientras una condición sea verdadera (útil en simulaciones donde no se sabe cuándo se alcanzará un umbral).

Importancia: En este rubro son esenciales para iterar sobre datasets, entrenar modelos épica tras épica o automatizar tareas repetitivas de limpieza de datos.

## 2. Funciones: Motivación, Parámetros y Recursividad
Las funciones son bloques de código reutilizables que realizan una tarea específica.

Motivación: Evitan repetir código, haciendo que los proyectos sean más limpios y fáciles de mantener.

Parámetros: Son las "entradas" que recibe la función (por ejemplo, pasarle un set de datos y un valor de alfa a un modelo ARIMA).

Recursividad: Es cuando una función se llama a sí misma para resolver problemas que pueden dividirse en subtareas idénticas (muy común en algoritmos de búsqueda y estructuras de árboles).

Importancia: Permite simplificar los análisis, creando funciones personalizadas para calcular el Gini o la Entropía sin reescribir la lógica cada vez.

## 3. Álgebra Booleana y Condicionales
Es la lógica detrás de la toma de decisiones del programa (if, else, elif).

Álgebra Booleana: Uso de operadores como AND, OR y NOT para evaluar si algo es Verdadero o Falso.

Condicionales: Permiten que el código tome caminos distintos. Si se cumple una condición (ej. la precisión del modelo es > 90%), el programa hace una cosa; si no, hace otra.

Importancia: Es la base de los Árboles de Decisión. Todo el criterio de división de datos se basa en estas reglas lógicas para clasificar información.

## 4. Cadenas, Listas y Tuplas
Son las estructuras donde se guarda la información (contenedores de datos).

Cadenas (Strings): Texto puro. Importante para manejar nombres de columnas o etiquetas en gráficas de Seaborn.

Listas: Colecciones mutables (puedes cambiar sus elementos). Son el estándar para guardar secuencias de datos que vas a procesar.

Tuplas: Colecciones inmutables (no cambian). Se usan por seguridad para datos que deben permanecer constantes, como las coordenadas de una ubicación o parámetros fijos de hardware.

Importancia: Estas estructuras son utiles en la manipulación de datos, por ejemplo para utilizar Pandas, se necesita entender cómo se estructuran las listas y tuplas para organizar la información de registros bursátiles.
