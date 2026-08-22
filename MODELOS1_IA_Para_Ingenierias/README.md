# ENTREGA FINAL - Proyecto AI4ENG UDEA 2025-2

## Solución de Clasificación para Pruebas Saber Pro Colombia

---

## Integrantes del equipo

| Nombre completo | Cédula | Programa académico | Usuario Kaggle |
|---|---|---|---|
| **Cristian David Diez Lopez** | 000 | Ingeniería de Sistemas | cdiezlop |
| Rafael Ángel Alemán Castillo | 1038141356 | Ingeniería de Sistemas | rafa710 |
| Jonatan Romero Arrieta | 1013104268 | Ingeniería de Sistemas | jonatanromeroarrieta |

---

## Videos de Sustentación

### Video de la Entrega 2 (Avance)
* **Enlace:** [https://youtu.be/Ej9LHUxAb5Y](https://youtu.be/Ej9LHUxAb5Y)
* **Contenido:** Explicación del preprocesamiento inicial (`02 - preprocesado.ipynb`) y dificultades encontradas.

### Video de la Entrega Final (Solución y Ranking)
* **Enlace:** [(https://youtu.be/ogvx2DtyAw8)](https://youtu.be/ogvx2DtyAw8)
* **Contenido:** Explicación de la solución final (`99 - modelo solución.ipynb`), modelos de contraste (`03` y `04`) y posición en el Leaderboard de Kaggle.

---

## Contenido del Repositorio (Nomenclatura Estricta)

| Archivo | Entrega | Descripción |
| :--- | :--- | :--- |
| `01 - exploración.ipynb` | 1 | Carga, inspección de datos y análisis de la variable objetivo (`RENDIMIENTO_GLOBAL`). |
| `02 - preprocesado.ipynb` | 2 | Pipeline inicial de preprocesamiento, limpieza y generación de *features*. |
| `03 - modelo_con_preprocesado_CatBoost.ipynb` | Final | **Modelo Alternativo 1:** Estrategia CatBoost de optimización rápida con imputación por Media. |
| `04 - modelo_con_preprocesado Random_Forest con Pipeline.ipynb` | Final | **Modelo Alternativo 2:** Estrategia tradicional de Pipeline (One-Hot Encoding + StandardScaler) con Random Forest. |
| `99 - modelo solución.ipynb` | Final | **Solución Definitiva:** Modelo CatBoost optimizado (900 iteraciones, profundidad 10) con imputación por Mediana para la submission final. |

---

## Información Académica

* **Curso:** Modelos y Simulación de Sistemas
* **Semestre:** 2025-2
* **Docente:** Raúl Ramos Pollán
* **Institución:** Universidad de Antioquia
