# AmbiWorld App - Desambiguación de Palabras Chinas 

AmbiWorld es una demo interactiva desarrollada en Streamlit que visualiza los diferentes significados de palabras ambiguas en chino mandarín mediante un sistema inspirado en órbitas planetarias.

Esta app es parte de un proyecto de investigación sobre desambiguación semántica en chino, combinando procesamiento del lenguaje natural, clasificación contextual y visualización interactiva.

---

¿Qué hace?

- Permite seleccionar una palabra china ambigua.
- Muestra sus significados como planetas orbitando alrededor del término central.
- Al pasar el ratón sobre cada significado, se muestra:
  - Una frase de ejemplo en chino.
  - Su traducción al español.
  - El pinyin (pronunciación).
Y el audio

---

 Tecnologías utilizadas

- Python 3.8+
- Streamlit
- Plotly
- Pandas
- NumPy

---

## Estructura del proyecto

ambiworld_app.py         # Código principal de la app
datos.csv                # Dataset de palabras ambiguas y ejemplos
Audio                    # carpeta de audios generados
imagenes/                #  futuras extensiones visuales

---

 Requisitos de instalación

pip install streamlit plotly pandas numpy

---

## ¿Cómo ejecutar la aplicación?

1. Coloca el archivo ambiworld_app.py y archivos con datos.csv en el mismo directorio.
2. Abre tu terminal o consola.
3. Ejecuta:

streamlit run ambiworld_app.py

4. Se abrirá automáticamente en el navegador predeterminado (http://localhost:8501).

---

Objetivo del proyecto

AmbiWorld busca hacer accesible y visual la comprensión de las múltiples acepciones de palabras ambiguas en chino, utilizando una representación gráfica intuitiva y educativa.
Apoya tanto a estudiantes de chino como a investigadores en procesamiento de lenguaje natural.

---

🎧 Archivos de audio

La aplicación incluye audios en formato `.mp3` con pronunciaciones en **chino mandarín**, asociados a cada palabra ambigua.  
Estos archivos permiten escuchar la palabra y su pinyin dentro de la app AmbiWorld.

📂 Carpeta: `/app/audio/`  
🎧 Detalles técnicos y enlace de descarga: [readme-audios](app/audio/readme-audios)
Se incluyen cien audios de ejemplo.
Los audios completos utilizados en la versión original del proyecto pueden solicitarse a la autora.

🔍 Posibles Aplicaciones
	•	Aprendizaje de idiomas asistido por IA.
	•	Mejora de traductores automáticos multilingües.
	•	Clasificación semántica de texto.
	•	Modelos de comprensión del lenguaje aplicados a la educación.

⸻

👩‍💻 Autora

Tatiana Beresaluze García
Estratega en Inteligencia Artificial, Innovación y Marketing Digital
📧 tatiana.beresaluze@gmail.com


⸻

🧭 Licencia

Este proyecto se publica con fines educativos y de investigación.
Licencia: MIT License © 2025 Tatiana Beresaluze

