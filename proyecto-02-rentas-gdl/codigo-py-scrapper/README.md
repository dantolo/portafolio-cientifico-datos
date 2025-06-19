🏠 Scraper de Casas en Venta - Guadalajara (Inmuebles24 y Casas y Terrenos)
Este proyecto implementa un scraper automatizado en Python con Playwright para extraer información detallada sobre propiedades (casas y departamentos) en venta en Guadalajara, Jalisco. El objetivo es construir una base de datos estructurada de inmuebles para análisis de mercado inmobiliario.

🔧 Tecnologías utilizadas
Python 3.11+

Playwright (automatización de navegación)

Pandas (procesamiento de datos)

Regex y JSON (limpieza y parseo)

CSV para almacenamiento

📄 Qué hace el script
Se conecta a la página de CasasyTerrenos.com

Navega por hasta 80 páginas de resultados

Extrae datos en JSON directamente del frontend (no de scraping visual)

Procesa y normaliza campos como:
Título, Precio, Ubicación, Superficie, Construcción, Recámaras, Baños, Estacionamientos

Guarda los resultados en archivos .csv

Maneja errores y páginas fallidas, intentando recuperarlas al final

🧠 Funciones clave
procesar_propiedad(): Limpia y transforma cada propiedad.

extraer_datos_json(): Extrae directamente del <script> embebido en la web.

procesar_pagina(): Implementa retry inteligente y espera aleatoria.

recuperar_paginas_fallidas(): Intenta rescatar propiedades que fallaron en el primer scraping.
