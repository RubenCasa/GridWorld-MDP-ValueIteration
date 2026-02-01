
#  GridWorld MDP - Value Iteration

Implementación de un entorno **GridWorld 12×12** modelado como **Proceso de Decisión de Markov (MDP)** y resuelto mediante el algoritmo **Value Iteration**.

##  Contenido del Proyecto

| Sección | Descripción |
|---------|-------------|
| **Parte A** | Diseño del entorno GridWorld con obstáculos, trampas y meta |
| **Parte B** | Modelado formal como MDP (Estados, Acciones, Transiciones, Recompensas) |
| **Parte C** | Resolución con Value Iteration y visualización de política óptima |
| **Parte D** | Análisis comparativo desde múltiples estados iniciales |

##  Configuración del Entorno

Tamaño: 12 × 12 celdas Obstáculos: 6 celdas (barreras físicas) Trampas: 2 celdas (recompensa: -100, terminal) Meta: 1 celda en (11,11) (recompensa: +100)


## Parámetros del MDP

| Parámetro | Valor | Descripción |
|-----------|-------|-------------|
| γ (gamma) | 0.95 | Factor de descuento |
| Recompensa por paso | -1 | Incentiva caminos cortos |
| Penalización trampa | -100 | Estado terminal negativo |
| Recompensa meta | +100 | Estado terminal positivo |

##  Ejecución

```bash
# Instalar dependencias
pip install numpy matplotlib jupytext

# Ejecutar notebook
jupyter notebook AA8_GridWorld_MDP.ipynb
