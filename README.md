# Análisis de los 100 Videos Más Populares de Tecnología en BiliBili 🖥️📊

Este proyecto realiza un análisis de los 100 videos más populares en la categoría de tecnología en BiliBili, una de las principales plataformas de video de China. Se utiliza **web scraping** para obtener los datos y **Python** para procesarlos y analizarlos.

## Descripción 📄

El objetivo de este proyecto es analizar el comportamiento de los videos de tecnología más vistos en BiliBili, extrayendo información como:

- Títulos de los videos.
- Número de vistas, likes y comentarios.
- Fecha de publicación.
- Categorías y etiquetas más comunes.

Los datos se obtuvieron utilizando técnicas de **web scraping** con **BeautifulSoup** y **Requests**. Posteriormente, los datos fueron analizados en un **Jupyter Notebook**, donde se realizaron visualizaciones y estadísticas descriptivas.

## Estructura del Proyecto 📂

- **BiliBili_Project.ipynb**: Jupyter Notebook con el análisis completo.
- **requirements.txt**: Archivo con las dependencias necesarias para ejecutar el proyecto.
- **README.md**: Este archivo, con la descripción y las instrucciones del proyecto.

## Herramientas Utilizadas 🚧

- **Python**: Lenguaje principal para el scraping y el análisis.
- **Jupyter Notebook**: Para desarrollar el análisis de manera interactiva.
- **BeautifulSoup**: Para extraer datos de las páginas de BiliBili.
- **Requests**: Para realizar las solicitudes HTTP y obtener el HTML.
- **Pandas**: Para manipulación y análisis de los datos.
- **Matplotlib/Seaborn**: Para las visualizaciones.

## Instrucciones de Instalación ⚙️

Para ejecutar este proyecto en tu propio entorno, sigue los siguientes pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   cd nombre-del-repositorio
   ```

2. Crea un entorno virtual (opcional pero recomendado):
   ```bash
   python -m venv env
   source env/bin/activate  # En Windows usa `env\Scripts\activate`
   ```

3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

4. Abre el Jupyter Notebook:
   ```bash
   jupyter notebook BiliBili_Project.ipynb
   ```

## Resultados 🏆

El análisis ofrece insights sobre:

- Las temáticas más populares en los videos de tecnología.
- La relación entre la duración del video y el número de visualizaciones.
- El comportamiento de los usuarios en términos de likes, comentarios y shares.

## Próximos Pasos 🚀

- Ampliar el análisis para incluir otras categorías populares en BiliBili.
- Implementar más técnicas de scraping para obtener datos adicionales como la descripción del video o los comentarios destacados.
- Automatizar el proceso de scraping para actualizar los datos regularmente.

## Contribuciones 🤝

Las contribuciones son bienvenidas. Si tienes sugerencias, mejoras o encuentras algún problema, no dudes en abrir un "issue" o enviar un "pull request".

## Licencia 📜

Este proyecto está bajo la licencia MIT. Puedes ver los detalles en el archivo `LICENSE`.
