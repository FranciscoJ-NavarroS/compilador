# compilador 
Consigna:

1. Análisis Lexicográfico:

           1.1.          Identificar las palabras reservadas.
           1.2.          Construir diagrama de transiciones para reconocer los componentes léxicos del lenguaje.
           1.3.          Generar la tabla de transiciones.
           1.4.          Implementar la tabla en Java.
           1.5.          Declarar directivas jlex (patrones – expresiones regulares).
           1.6.          Mostrar código generado por la herramienta.
           1.7.          Probar la ejecución de la entrada de estudio.
           
2. Análisis Sintáctico:

           2.1.          Diseñar una gramática no ambigua del lenguaje.
           2.2.          Generar el árbol de análisis sintáctico de la entrada de estudio.
           2.3.          Crear los diagramas de sintaxis.
           2.4.          Implementar la gramática en Java.
           2.5.          Diseñar Analizador Sintáctico Descendente con retroceso, construir la tabla de análisis sintáctico y analizar la entrada de estudio.
           2.6.          Comprobar si es LL(1) (si no lo es, hacer las modificaciones pertinentes para convertirla en LL(1)).
           2.7.          Construir su tabla de análisis y verificar si la entrada de estudio es analizada correctamente.
           2.8.          Diseñar Analizador Sintáctico Ascendente con retroceso, construir la tabla de análisis sintáctico y analizar la entrada de estudio.
           2.9.          Construir el autómata y la tabla de análisis SLR.
           2.10.          Analizar la entrada de estudio.
           2.11.          Construir la Tabla de Tipos.
           2.12.          Construir la Tabla de Símbolos.
           2.13.          Declarar directivas cup (gramática).
           2.14.          Mostrar código generado por la herramienta.
           2.15.          Probar la ejecución de la entrada de estudio.
           2.16.          Obtener conclusiones.


Descripción general de nuestro compilador:

·El único tipo de datos es entero.

·Todos los identificadores son declarados implícitamente y con una longitud de 32 caracteres.

·Los ID deben comenzar con una letra y un están compuestos por letras y dígitos.

·Hay dos tipos de sentencias.

·Asignación: ID := expresión;
La expresión es infinita y se construye con identificadores, constantes los operadores + y - los paréntesis están permitidos.Pueden estar o no.

ENTRADA/SALIDA:

·Leer(lista de IDs);
·Escribir(lista de expresiones)
·Cada sentencia termina con un punto y coma ; el cuerpo del programa está delimitado por inicio y fin.
