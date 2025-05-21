# 📊 Segmentación Estratégica de Clientes para el Producto 24 - Clustering + Dashboard
## Año: 2025
Este proyecto aplica técnicas de clustering y modelos predictivos para optimizar la asignación de recursos en el área de Ingeniería de Riesgos, segmentando clientes asegurados en dos grupos: aquellos que requieren atención estratégica y los que pueden ser gestionados mediante canales masivos.

---

## 🎯 Objetivo

Optimizar el relacionamiento con los clientes del *Producto 24* mediante segmentación basada en KPIs como valor asegurado, siniestralidad y fidelización.

---

## 🧰 Herramientas

- Python (pandas, sklearn, seaborn, matplotlib)
- Jupyter Notebook
- SQL (pandasql)
- Power BI (dashboard final)
- Excel (.xlsx original)
- Streamlit (interfaz local para QA interna, opcional)

---

## 🔍 Metodología

### 📁 Limpieza y transformación:
- Filtrado de clientes con Producto 24
- Tratamiento de nulos según contexto
- Log-transform y normalización de variables continuas
- Reducción de dimensionalidad con PCA

### 🧪 Modelos utilizados:
- **KMeans** para segmentación (Cluster 0: masivo, Cluster 1: estratégico)
- **KNN** para predicción de probabilidad de siniestro (prob_siniestro)
- Criterios de enriquecimiento: número de productos asegurados

---

## 🧠 Criterios de Segmentación Final

- **Relación Estratégica**: Cluster = 1 y prob_siniestro > 0.7 o > 4 productos
- **Acercamiento Masivo**: el resto

### 🧮 Asignación operativa:
- 468 clientes: estratégicos (visita personalizada)
- 680 clientes: masivos (contacto vía email/webinar)
- Recursos asignados: 7 ingenieros x 100h mensuales → capacidad cubierta

---

## 📊 Dashboard

Dashboard en Power BI que permite:
- Visualizar portafolio por ciudad, sector y producto
- Explorar variables clave: prima emitida, valor asegurado, siniestralidad
- Mapear clusters y categorías de atención

📷 Capturas recomendadas:
- `Capturas/dashboard_producto24.png`
- `Capturas/mapa_clusters_pca.png`
- `Capturas/tabla_segmentacion.png`

---

## 📂 Estructura del repositorio

📁 Capturas/
📁 notebooks/
📁 sql/
📁 data/
📄 README.md

## 🧠 Conclusiones

- Asignación óptima de recursos basada en datos.
- Identificación clara de clientes estratégicos.
- Incorporación de lógica predictiva para robustecer las decisiones.
- Interfaz de visualización clara, comprensible y accionable.

---

## 🙋 Sobre mí

👨‍💻 Sergio Martínez  
*Data Scientist | Machine Learning | Automatization*  
📫 smartinezx99@gmail.com | [LinkedIn](https://www.linkedin.com/in/sergio-mart%C3%ADnez-b26301176/)
