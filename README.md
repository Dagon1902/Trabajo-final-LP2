# Trabajo Final LP2: Detector de Fraude en E-commerce

Este proyecto desarrolla un prototipo para la detección de anomalías y fraude en plataformas de e-commerce mediante técnicas de web scraping y análisis de datos.

## 👥 Integrantes
- Pariona Huarhuachi, Misael Gabriel: missaph
- Chamilco Carhuamaca, Diego: Dagon1902
- Marca Andia, Hernan Joel: JoelMarcaA

## 📋 Descripción del Reto
El sistema identifica patrones de fraude (precios engañosos, descripciones falsas) mediante la recolección y comparación de datos, aportando al entendimiento de la desinformación en el comercio electrónico.

## 🛠️ Tecnologías
- Python (Selenium, Pandas)
- Web Scraping automatizado
- Análisis de datos en Jupyter Notebooks

## ⚙️ Estrategia y Ética
- **Fuentes:** eBay (fuente primaria de datos) y Apple (fuente secundaria para validación técnica).
- **Consideraciones Éticas:** El proyecto se limita a la extracción de datos públicos, sin recopilar información personal (PII) y respetando los términos de servicio. Debido a bloqueos agresivos, se implementó una estrategia de simulación de datos (Mocking) explicada en el informe técnico.

## 🚀 Cómo ejecutar
1. Clona este repositorio.
2. Instala las dependencias: `pip install selenium pandas webdriver-manager`
3. Ejecuta el notebook `Final- Parte 1.ipynb` para realizar la extracción y el análisis.

## 🧠 Reflexión sobre el uso de LLMs
El uso de LLMs permitió acelerar la creación del script base. Sin embargo, la lógica de arquitectura y la resolución de problemas ante bloqueos (Error 403) fueron validados manualmente por el equipo, demostrando que la supervisión humana es indispensable en tareas de scraping real.

## 📁 Estructura del proyecto
- `/`: Archivos raíz, README y Jupyter Notebooks.
- `dataset_iphone17_ebay.csv`: Dataset crudo.
- `analisis_iphone17_tabla.csv`: Resultado procesado para análisis.
