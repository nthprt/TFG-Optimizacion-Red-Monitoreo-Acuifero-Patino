# Análisis multiobjetivo de selección óptima de pozos de monitoreo de agua subterránea

## Descripción

Este repositorio contiene la implementación de algoritmos evolutivos multiobjetivo para el diseño óptimo de redes de monitoreo de calidad del agua subterránea en el acuífero Patiño, Paraguay.

El trabajo compara sistemáticamente dos algoritmos de optimización multiobjetivo:
- **NSGA-II** (Non-dominated Sorting Genetic Algorithm II)
- **MOEA/D** (Multi-Objective Evolutionary Algorithm based on Decomposition)

### Objetivos de optimización

El modelo optimiza simultáneamente tres funciones objetivo:
1. **Eficiencia Nash–Sutcliffe (NSE)** — maximizar la precisión de la representación espacial de la calidad del agua.  
2. **Proporción de pozos públicos** — maximizar la accesibilidad operativa priorizando pozos de acceso público.  
3. **Entropía de Shannon** — maximizar la uniformidad en la distribución geográfica de los pozos.

---

## Trabajo de tesis

**Título:** Análisis multiobjetivo de selección óptima de pozos de monitoreo de agua subterránea.  
**Autores:**  
- Elías Fernando Cristaldo Ruíz.  
- Nathaly Lorena Prieto Meza.

**Tutores:**  
- D.Sc. Liz Báez.  
- D.Sc. Christian von Lücken.

**Institución:** Facultad Politécnica, Universidad Nacional de Asunción  
**Año:** 2025

---

## Estructura del repositorio

```txt
TFG-Optimizacion-Red-Monitoreo-Acuifero-Patino/
├── nsga2.py
├── moead.py           
├── LICENSE
└── README.md
```
##  Requisitos

### Dependencias principales
```
Python >= 3.11
pymoo >= 0.6.1.3
numpy >= 1.24.0
pandas >= 2.0.0
scipy >= 1.11.0
matplotlib >= 3.7.0
```

### Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/nthprt/TFG-Optimizacion-Red-Monitoreo-Acuifero-Patino.git
cd TFG-Optimizacion-Red-Monitoreo-Acuifero-Patino
```

2. Crear entorno virtual (recomendado):
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. Instalar dependencias:
```bash
pip install pymoo numpy pandas scipy matplotlib
```

