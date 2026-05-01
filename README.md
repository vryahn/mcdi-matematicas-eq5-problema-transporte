# INFOTEC MCDI Matemáticas 2026-1 — Equipo 5
## Problema del Transporte: Formulación Primal-Dual, Representación en Grafos y Aplicaciones

Proyecto final de la actividad de reporte de investigación sobre el **Problema del Transporte** para la asignatura **Matemáticas 2026-1** de la **Maestría en Ciencia de Datos (INFOTEC)**.

Este repositorio documenta el estudio del Problema del Transporte desde una perspectiva teórica y computacional. Integra el reporte en LaTeX/PDF, el notebook con la implementación en Python y los recursos gráficos utilizados en el documento final.

---

## Descripción del proyecto

El trabajo desarrolla el Problema del Transporte como un modelo clásico de programación lineal y lo analiza desde tres enfoques complementarios:

- **Formulación primal** del transportista.
- **Formulación dual** del embarcador e interpretación de **precios sombra**.
- **Representación mediante grafos bipartitos** y su relación con redes de flujo.

Además, se incluyen ejemplos aplicados para mostrar cómo el modelo puede utilizarse en escenarios reales de optimización logística y distribución de recursos.

---

## Contenido del repositorio

La estructura principal del repositorio es la siguiente:

```text
.
├── img/
├── LICENSE
├── README.md
├── Reporte_Equipo5.tex
├── Equipo_5__Problema_del_Transporte.pdf
├── transporte_equipo5.ipynb
└── notebook_ejecutado.pdf
```

### Archivos principales

- **`Reporte_Equipo5.tex`**  
  Archivo fuente principal del reporte en LaTeX.

- **`Equipo_5__Problema_del_Transporte.pdf`**  
  Versión final compilada del reporte.

- **`transporte_equipo5.ipynb`**  
  Notebook con la implementación computacional de los ejemplos desarrollados en el proyecto.

- **`notebook_ejecutado.pdf`**  
  Exportación en PDF del notebook ejecutado, útil como evidencia complementaria del análisis computacional.

- **`img/`**  
  Carpeta con las figuras e imágenes utilizadas en el reporte.

---

## Objetivo

El objetivo de este repositorio es ofrecer una referencia reproducible y bien documentada del Problema del Transporte, conectando:

- Teoría de programación lineal.
- Dualidad y análisis económico.
- Teoría de grafos.
- Resolución computacional con Python.

---

## Casos de estudio

El proyecto incluye dos aplicaciones principales del modelo:

1. **Logística de última milla en e-commerce**  
   Se modela la distribución óptima de inventario entre centros de distribución y destinos de demanda, minimizando el costo total de transporte.

2. **Distribución de agua en emergencia con restricciones complejas**  
   Se incorporan restricciones operativas adicionales, como rutas bloqueadas, capacidades máximas y prioridades obligatorias, para representar un escenario más realista.

---

## Herramientas utilizadas

- **Python**
- **PuLP**
- **Jupyter Notebook**
- **LaTeX**
- **GitHub**

---

## Cómo usar este repositorio

### 1. Consultar el reporte final

El documento principal del proyecto se encuentra en:

- `Equipo_5__Problema_del_Transporte.pdf`

Ahí se presenta el desarrollo teórico, metodológico y aplicado del trabajo.

### 2. Ejecutar el notebook

Para reproducir los resultados computacionales:

1. Abrir el archivo `transporte_equipo5.ipynb`.
2. Instalar las dependencias necesarias.
3. Ejecutar las celdas en orden.

Ejemplo de instalación:

```bash
pip install pulp matplotlib networkx
```

> Dependiendo de la versión final del notebook, algunas bibliotecas pueden no ser estrictamente necesarias en todas las secciones.

### 3. Compilar el reporte en LaTeX

Si deseas compilar el documento desde el archivo fuente:

```bash
pdflatex Reporte_Equipo5.tex
pdflatex Reporte_Equipo5.tex
```

> La compilación puede requerir que la carpeta `img/` permanezca en la misma ubicación relativa que el archivo `.tex`.

---

## Reproducibilidad

Este repositorio fue organizado para conservar en un solo lugar:

- El documento fuente del reporte.
- La versión final en PDF.
- El notebook con los experimentos.
- Los recursos gráficos necesarios para reconstruir el trabajo.

De este modo, el proyecto puede revisarse, compilarse y reutilizarse con mayor facilidad.

---

## Integrantes

**Equipo 5**

- Andrés Rangel
- Santiago Mendoza
- David Rodríguez
- Bryan Rodríguez

---

## Contexto académico

- **Institución:** INFOTEC  
- **Programa:** Maestría en Ciencia de Datos  
- **Asignatura:** Matemáticas 2026-1  
- **Actividad:** Reporte de investigación  
- **Tema:** Problema del Transporte  

---

## Licencia

Este repositorio se distribuye bajo la licencia **MIT**.  
Consulta el archivo [LICENSE](./LICENSE) para más detalles.