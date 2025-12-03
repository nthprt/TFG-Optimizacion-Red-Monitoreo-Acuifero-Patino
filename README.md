# Análisis Multiobjetivo de Selección Óptima de Pozos de Monitoreo de Agua Subterránea

## Descripción

Este repositorio contiene la implementación de algoritmos evolutivos multiobjetivo para el diseño óptimo de redes de monitoreo de calidad del agua subterránea en el acuífero Patiño, Paraguay.

El trabajo compara sistemáticamente dos algoritmos de optimización multiobjetivo:
- **NSGA-II** (Non-dominated Sorting Genetic Algorithm II)
- **MOEA/D** (Multi-Objective Evolutionary Algorithm based on Decomposition)

### Objetivos de Optimización

El modelo optimiza simultáneamente tres funciones objetivo:
1. **Eficiencia Nash–Sutcliffe (NSE)** — maximizar la precisión de la representación espacial de la calidad del agua.  
2. **Proporción de pozos públicos** — maximizar la accesibilidad operativa priorizando pozos de acceso público.  
3. **Entropía de Shannon** — maximizar la uniformidad en la distribución geográfica de los pozos.

---

## Trabajo de Tesis

**Título:** Análisis Multiobjetivo de Selección Óptima de Pozos de Monitoreo de Agua Subterránea.  
**Autores:**  
- Elías Fernando Cristaldo Ruíz  
- Nathaly Lorena Prieto Meza

**Tutores:**  
- D.Sc. Liz Báez  
- D.Sc. Christian von Lücken

**Institución:** Facultad Politécnica, Universidad Nacional de Asunción  
**Año:** 2025

---

## Estructura del repositorio

```txt
TFG-Optimizacion-Red-Monitoreo-Acuifero-Patino/
├── nsga2.py
├── moead.py
├── data/                 # (opcional) datos de entrada: rásters, tablas, shapefiles
├── results/              # (opcional) resultados, figuras y reportes
├── notebooks/            # (opcional) notebooks con análisis y gráficas
├── LICENSE
└── README.md
