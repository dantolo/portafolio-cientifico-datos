# 🏙️ ¿Dónde invertir en Guadalajara?

Este proyecto analiza el mercado inmobiliario de casas en Guadalajara, Jalisco, México, para detectar colonias con alto potencial de inversión utilizando técnicas de scraping, análisis de datos y visualización avanzada.

## 📌 Objetivo

Ayudar a inversionistas a identificar zonas con alta rentabilidad inmobiliaria mediante el análisis de propiedades y sus precios por metro cuadrado.

---

## 🧠 Tecnologías utilizadas

- **Python** (Pandas, NumPy, Regex, Geopy)
- **Selenium** (scraping automatizado)
- **Google Colab** (procesamiento en la nube)
- **Tableau** (visualización)
- **Excel** (validación cruzada)
- **GitHub** (repositorio de desarrollo)

---

## 📊 Proceso

### 1. Scraping
- Extracción automatizada de datos 
- Se recopilan: Título, Precio, Superficie, Colonia, Descripción.

### 2. Limpieza y preparación
- Limpieza de precios y superficies.
- Eliminación de duplicados y valores atípicos (< $200,000 MXN).
- Normalización de nombres de colonias (sin stopwords, mayúsculas, etc.).
- Cálculo de **precio por metro cuadrado**.

### 3. Clasificación de propiedades
- Se clasifican en 5 niveles de rentabilidad:
  - Muy Alta Rentabilidad
  - Alta Rentabilidad
  - Promedio
  - Baja
  - Muy Baja

Esto se basa en su comparación con el precio promedio por m² de su colonia.

### 4. Visualización de datos
Se crearon 3 dashboards públicos con Tableau:

1. 🔗 [Precio promedio por colonia](https://public.tableau.com/app/profile/dante.alexis.ibarra.franco/viz/DndeinvertirenGuadalajara/Dashboard1)
2. 🔗 [Distribución de rentabilidad](https://public.tableau.com/app/profile/dante.alexis.ibarra.franco/viz/DndeinvertirenGuadalajara2/Dashboard12)
3. 🔗 [Clasificación de propiedades](https://public.tableau.com/app/profile/dante.alexis.ibarra.franco/viz/DndeinvertirenGuadalajara3/Dashboard3)

---

## 📁 Archivos clave

📄 Código scraper: [`scraper_inmuebles24.py`](https://github.com/dantolo/portafolio-cientifico-datos/blob/main/proyecto-02-rentas-gdl/codigo-py-scrapper/scraper_inmuebles24.py)  
📊 Datos limpios: [`datos_propiedades_limpias.csv`](https://github.com/dantolo/portafolio-cientifico-datos/blob/main/proyecto-02-rentas-gdl/datos_propiedades_limpias.csv)  
📓 Análisis exploratorio: [`Analisis_Casas.ipynb`](https://github.com/dantolo/portafolio-cientifico-datos/blob/main/proyecto-02-rentas-gdl/Analisis_Casas.ipynb)  
📘 Informe visual completo: [`Informe_Analisis_Rentas_GDL.pdf`](https://github.com/dantolo/portafolio-cientifico-datos/blob/main/proyecto-02-rentas-gdl/Informe_Analisis_Rentas_GDL.pdf)


---

## 🤝 Contribuciones

Este proyecto fue desarrollado por [Dante Alexis Ibarra Franco](https://www.linkedin.com/in/dantealexisibarra/), apasionado por los datos, la visualización y la inversión inteligente.

---

## 🚀 ¿Qué sigue?

Estamos planeando una versión 2.0 usando **Streamlit** para hacer una app web interactiva con IA para detectar oportunidades de compra automáticamente.

¡Estén atentos!
