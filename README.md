# 🌱 RAÍCES + DATOS: Conectando la naturaleza con la IA

**Edición:** Clubes de Ciencia México, Verano 2025 – PAZ2  
**Club:** REDES DE RAÍCES Y DATOS: CONECTANDO LA NATURALEZA CON LA IA  
**Ciudad:** La Paz, BCS  
**Fechas:** 3 al 9 de agosto de 2025  
**Modalidad:** Experimental Biológico + Computacional

---

## Descripción del Proyecto

La naturaleza tiene sus propios sistemas inteligentes.  
En este taller combinamos **ciencia marina** y **ciencia de datos** para explorar el **carbono azul** en ecosistemas costeros.

Realizamos trabajo de campo en un **manglar** midiendo variables ambientales y recolectamos **imágenes aéreas con drones**.  
Con esos datos, aplicamos **inteligencia artificial** y **aprendizaje automático** para:

- Clasificar imágenes de ecosistemas (modelo MLP)
- Predecir el **contenido de carbono** en biomasa de manglar a partir de variables como especie, diámetro (DAP) y biomasa estimada

> Uniendo naturaleza y tecnología para combatir el cambio climático.

---

## Resultados Obtenidos

### Modelo de clasificación de imágenes (MLP)
Después de 5 épocas:

| Métrica | Entrenamiento | Validación |
|---------|---------------|-------------|
| Precisión | ~97% | 80% |
| Pérdida   | ~0.07 | ~74.5 |

### Modelos predictivos de carbono
Se desarrollaron modelos de **Machine Learning** para estimar carbono en biomasa de manglar usando:

- **Decision Tree**
- **Random Forest**
- **XGBoost**

**Métrica de evaluación:** RMSE (Error cuadrático medio)

---

## Tecnologías Utilizadas

| Herramienta | Uso |
|-------------|------|
| **Python 3.x** | Lenguaje principal |
| **TensorFlow / Keras** | Red neuronal MLP para imágenes |
| **Scikit-learn** | Decision Tree, Random Forest, preprocesamiento |
| **XGBoost** | Modelo avanzado para predicción de carbono |
| **NumPy, Pandas** | Manipulación de datos |
| **Matplotlib** | Visualización de resultados |
| **Google Colab** | Entorno de ejecución (GPU T4) |

---
