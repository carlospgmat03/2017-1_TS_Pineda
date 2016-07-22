Objetivos: 
==========

Enseñar algunas herramientas de programación eficientes y modernas
para poder atacar problemas actuales. Escogemos Julia y git
como herramientas fundamentales para hacer este curso, pues 
deseamos tener un marco común. También deseamos enseñar a 
_colaborar_ de manera eficiente.

Saber como se piensa cuando se hace investigación, es decir de manera 
no lineal y sin un camino claro. 

Aprender elementos de información cuántica.

* Ojo, estandarizar la definicion de los objetos,nerrar lso qubits, que es el qubit cero, el primer elemento del array es 1 o es 0 

Temario (16 semanas):
=====================
0. Introduccion, plan general, evaluación (tareas binarias)
   * Instalación de git 

   Introducción al curso: temario, evaluación etc. Platicar objetivos de la
   clase y la forma en que se trabajará, mencionar lo de las tareas binarias.
1. Git
   * Comandos basicos: add, commit, push, pull y clone
   * Pull request y merging

2. Git
2. Git prima
3. Julia (diagonalizacion, hablar de RMT, o del mapeo logistico)
   * Sintaxis
   * Jupyper-notebook
     * Markdown
     * Yo uso la version de anaconda, esta bien mantenida.
   * Librerias: Llamar y hacer
   * Usar \textit{static type}, Amaro dice que es la forma de sacarle jugo a Julia.
   * Definir funciones
   * Operadores logicos
   * Loops: definir bien el conteo de los elementos del estado.
   * Benchmarking (tic() tac()): Memoria y CPU.
   * Estandarización de objetos.
4. Julia (dibujos y ejemplos bonitos, optica cuantica)
5. Julia (bitwise operations, loops, )
6. CI Travis 
7. Benchmark velocidad y memoria en Julia
******
1. Sistemas de 1 qubit, esfera de Bloch, numeración en sistemas
   de n qubits. 
1. Traza parcial, programación de traza parcial y significado físico de la traza.
   Estados enredados, valores esperados en estados de Bell. 

8. Estados de n qubits y compuertas de un qubit, tomografia
9. Compuertas de dos qubits y algun ejemplo, entaglement swaping?
10. Concatenacion de compuertas, cadena con un defecto. (ver con carlos gonzales) 

Quiza en las cosas introductorias de Julia, poner algo de RMT. Quiza la P(s). 

Uno de los proyectos, puede ser construir la base simetrica para la cadena


Algunas alternativas para proyectos finales
=====================

* _Teoría de matrices aleatorias_-
  Estudiar numéricamente las propiedades espectrales de matrices aleatorias y compararlas con un espectro de una cadena inhomogénea.
* _Simular el algoritmo de Shor_-
* _Simular cluster quantum computing_-
* _Alguna alternativa propuesta por ustedes_- Pueden proponer un proyecto, pero este debe ser aceptado. Debe tener un objetivo claro y debe hacer uso de algunas herramientas propuestas en clase.
* _Una base simetrica para la cadena de Ising_- Estudiar la cadena de Ising y constuir una base que sea consistente con dicha simetría.
