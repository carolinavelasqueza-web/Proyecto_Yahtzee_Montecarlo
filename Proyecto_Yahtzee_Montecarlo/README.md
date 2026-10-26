# Simulación de Yahtzee mediante Montecarlo

**Actividad didáctica 2 – Módulo 1**  
**Programa:** Ingeniería de Software y Datos  
**Estudiante:** Elisabeth Martínez Hernández

## Objetivo
Simular partidas de Yahtzee para dos jugadores y analizar las puntuaciones mediante el método de Montecarlo.

## Archivos
- `yahtzee_montecarlo.py`: código fuente de la simulación.
- `Martinez_Elisabeth_Montecarlo.docx`: documento técnico.
- `resultados_simulacion.txt`: resultados de las pruebas con 100, 1.000 y 5.000 partidas.

## Requisitos
- Python 3.9 o superior.
- Matplotlib para generar la gráfica.

Instalación de la dependencia:
```bash
pip install matplotlib
```

## Cómo ejecutar
Desde la terminal, en la carpeta del proyecto:
```bash
python yahtzee_montecarlo.py
```

El programa simula partidas, muestra promedios y proporciones de victoria, compara distintas cantidades de iteraciones y genera una gráfica.

## Metodología y estrategia
Cada dado toma un valor entero entre 1 y 6 con igual probabilidad. Cada jugador completa trece categorías de puntuación y puede lanzar hasta tres veces por turno. La estrategia automática conserva los dados de la cara más repetida y selecciona al final la categoría disponible que otorgue más puntos. Es una estrategia sencilla para la simulación y no una estrategia óptima.

## Método de Montecarlo y Teoría de los Grandes Números
El programa repite partidas independientes y calcula promedios y proporciones de victoria. Al aumentar el número de iteraciones, las estimaciones suelen estabilizarse, aunque no tienen que ser idénticas entre ejecuciones ni cambiar siempre en la misma dirección.

## Nota sobre la guía inicial
Este proyecto documenta una implementación propuesta. Para describir con exactitud las modificaciones respecto de la guía de la docente, debe compararse con el archivo original de esa guía.

## Referencias
- Hasbro. Yahtzee Classic: Instructions and rules. https://instructions.hasbro.com/en-ca/instruction/yahtzee-classic
- Dinov, I. D., Christou, N., & Gould, R. (2009). Law of Large Numbers: The Theory, Applications, and Technology-based Education. https://pmc.ncbi.nlm.nih.gov/articles/PMC3095954/
- Solitaired. Yahtzee. https://solitaired.com/yahtzee
