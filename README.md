# 🧠 AI-Powered Image Editing: Exploring Image-to-Image with Stable Diffusion

## Descripción

Este proyecto demuestra el potencial creativo de los modelos de difusión aplicados a la edición de imágenes. Utilizando la técnica *Image-to-Image*, se parte de un boceto simple y se transforma en una escena compleja y estilizada mediante un prompt en lenguaje natural. Se explora el impacto del parámetro `strength`, que controla el grado de transformación, y se analizan los resultados visuales obtenidos.

---

## 1. Instalación y Configuración

Se utilizó un entorno Python con las siguientes librerías:

- `diffusers`
- `transformers`
- `accelerate`
- `safetensors`

El modelo fue asignado correctamente al dispositivo CUDA para garantizar eficiencia en la generación.

## 2. Cargar el pipeline Image-to-Image
Se cargó un modelo preentrenado de Stable Diffusion en un pipeline especializado para la tarea de edición de imagen.

## 3. Cargar y preparar la imagen de entrada
Se utilizó un boceto simple de un paisaje natural, descargado desde una URL y redimensionado para compatibilidad con el modelo.

## 4. Primera transformación – Boceto a Realidad
Se aplicó un prompt para transformar el boceto en una escena futurista.

## 5. Experimentando con el parámetro strength
El parámetro strength controla cuánto se transforma la imagen original. Se probaron valores de 0.6, 0.8 y 1.0 manteniendo el mismo prompt y semilla.

## 6. Análisis del trabajo
Este trabajo demuestra cómo los modelos de difusión pueden reinterpretar visualmente una imagen base mediante lenguaje natural. Cada etapa del pipeline refleja comprensión técnica y sensibilidad creativa.

---

## Conclusión
La IA generativa no solo crea desde cero, sino que también puede colaborar en la edición y transformación de ideas visuales. Este laboratorio muestra cómo un boceto puede convertirse en una obra de arte detallada y estilizada, combinando visión humana con potencia computacional.

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.

