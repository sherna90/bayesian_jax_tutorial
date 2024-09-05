# Inferencia Bayesiana potenciada por JAX

JAX es una biblioteca de Python que proporciona cálculo numérico de alto rendimiento, diferenciación automática y compilación justo a tiempo (JIT), lo que la convierte en una potente herramienta para la inferencia bayesiana. 

1. Cálculo numérico: Compatible con NumPy. Las funciones JAX operan sobre matrices NumPy, lo que permite una integración perfecta con el código y las estructuras de datos existentes. Sin embargo, JAX utiliza operaciones vectorizadas, lo que acelera significativamente los cálculos, en particular para datos de alta dimensión.Al mismo tiempo, JAX puede aprovechar la potencia de GPUs y TPUs, mejorando drásticamente el rendimiento para tareas exigentes.
    
2. Diferenciación automática:  JAX calcula automáticamente gradientes de funciones, esenciales para los algoritmos de optimización y muestreo utilizados en la inferencia bayesiana (por ejemplo, descenso de gradiente, Hamiltonian Monte Carlo)
    
3. Compilación justo a tiempo: Ejecución optimizada del código: JAX compila el código a código máquina justo antes de la ejecución, optimizando el rendimiento para hardware específico.De esta forma, JAX aprovecha los procesadores y aceleradores multinúcleo, mejorando aún más la velocidad de cálculo.