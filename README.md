# Generación Automatizada de Diseños de Casas Modernas

## Índice

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Objetivos](#objetivos)
- [Metodología](#metodología)
  - [Recopilación de Datos](#recopilación-de-datos)
  - [Procesamiento de Texto](#procesamiento-de-texto)
  - [Generación de Imágenes](#generación-de-imágenes)
- [Herramientas y Tecnologías](#herramientas-y-tecnologías)
- [Implementación](#implementación)
- [Resultados](#resultados)
- [Conclusiones](#conclusiones)
- [Referencias](#referencias)
- [Ejemplo de Prompts](#ejemplo-de-prompts)

## Descripción del Proyecto

Este proyecto se centra en el desarrollo de un sistema que utiliza inteligencia artificial para generar descripciones detalladas y visualizaciones de diseños de casas modernas basadas en los requisitos del cliente. Aprovechando la API de OpenAI (ChatGPT-3.5 Turbo) y la herramienta de generación de imágenes Hotpot, se busca facilitar la visualización y comunicación de conceptos arquitectónicos, mejorando la interacción entre los estudios de arquitectura y sus clientes.

## Objetivos

- **Generar descripciones textuales detalladas** de diseños de casas modernas basadas en los requisitos y preferencias del cliente.
- **Convertir descripciones textuales en imágenes arquitectónicas** utilizando Hotpot, proporcionando visualizaciones precisas y personalizadas.

## Metodología

### Recopilación de Datos

- **Requisitos del Cliente:** Se recopila información detallada a través de entrevistas, cuestionarios y ejemplos de inspiración proporcionados por el cliente. Esto incluye estilo, tamaño, distribución y características deseadas.
- **Inspiración y Referencias:** Se obtienen ejemplos y referencias de diseños que el cliente considera atractivos, asegurando que el diseño final cumpla con sus expectativas.

### Procesamiento de Texto

- **Análisis de Requisitos:** La API de ChatGPT-3.5 Turbo analiza los datos del cliente para generar descripciones textuales detalladas del diseño arquitectónico.
- **Generación de Descripciones:** Las descripciones incluyen detalles sobre la distribución, materiales, estilo y características específicas de la casa moderna, reflejando con precisión las preferencias del cliente.

### Generación de Imágenes

- **Conversión de Descripciones:** Se utiliza Hotpot para convertir las descripciones textuales en imágenes arquitectónicas detalladas y visualmente atractivas.
- **Personalización Visual:** Las imágenes generadas se personalizan para reflejar con precisión los requisitos y preferencias del cliente.

## Herramientas y Tecnologías

- **Python:** Lenguaje de programación utilizado para el desarrollo del sistema.
- **OpenAI ChatGPT-3.5 Turbo API:** Para el análisis de datos del cliente y generación de descripciones textuales detalladas.
- **Hotpot:** Para la conversión de descripciones textuales en imágenes arquitectónicas personalizadas.
- **Plataformas de Análisis de Datos:** Para gestionar y analizar la información recopilada sobre los requisitos del cliente.

## Implementación

1. **Recopilación de Datos:** Se recoge información detallada sobre los requisitos y preferencias del cliente.
2. **Análisis con ChatGPT-3.5 Turbo:** Utilización de la API de ChatGPT-3.5 Turbo para generar descripciones textuales detalladas.
3. **Generación de Imágenes con Hotpot:** Conversión de las descripciones en imágenes arquitectónicas.
4. **Integración del Contenido:** Las descripciones y las imágenes se combinan en presentaciones coherentes y atractivas para el cliente.
5. **Pruebas y Ajustes:** Evaluación y ajuste de las descripciones e imágenes generadas en base a la retroalimentación del cliente.

## Resultados

- **Diseños Arquitectónicos Personalizados:** Se crean descripciones textuales y visualizaciones que reflejan fielmente los requisitos del cliente.
- **Mejora en la Comunicación con el Cliente:** Se observa una mejora significativa en la comprensión del cliente sobre los diseños propuestos.
- **Retroalimentación de Clientes:** La retroalimentación obtenida se utiliza para mejorar y ajustar el sistema en futuras iteraciones.

## Conclusiones

La implementación de este sistema automatizado ha demostrado ser eficaz para mejorar la comunicación entre estudios de arquitectura y clientes, proporcionando descripciones detalladas y visualizaciones precisas. Esto ha resultado en una mayor satisfacción del cliente y en un proceso de diseño más optimizado y centrado en la innovación.

## Referencias

- **Estudios sobre Comunicación en Arquitectura:** Investigación sobre los beneficios de la visualización y comunicación efectiva en el diseño arquitectónico.
- **Documentación de OpenAI:** Guías y documentación técnica sobre el uso de las APIs de ChatGPT-3.5 Turbo.
- **Hotpot:** Información y documentación sobre la generación de imágenes utilizando Hotpot.

## Ejemplo de Prompts

### Prompt General

"Necesito crear una descripción detallada del diseño de una casa moderna basada en los requisitos del cliente. El cliente desea una casa de [tamaño] metros cuadrados, con un estilo [moderno/minimalista/otro], y prefiere características como [características específicas: grandes ventanales, techos altos, espacios abiertos, etc.].

Por favor, genera una descripción textual que incluya:

- Una explicación detallada del diseño exterior e interior de la casa.
- Descripciones de los materiales y acabados a utilizar.
- Distribución de los espacios y las características específicas que desea el cliente.
- Sugerencias para elementos visuales que podrían complementar el diseño."

### Ejemplo de Prompt Específico

"Estoy desarrollando un diseño para una casa moderna de 200 metros cuadrados. El cliente desea un estilo minimalista con grandes ventanales, techos altos y espacios abiertos. La casa debe tener 3 habitaciones, 2 baños, una cocina abierta y un salón espacioso. Además, el cliente prefiere utilizar materiales sostenibles como madera reciclada y concreto pulido.

Por favor, genera una descripción textual detallada del diseño, incluyendo:

- Una descripción del exterior de la casa, destacando los grandes ventanales y los materiales sostenibles.
- Descripciones detalladas de cada habitación, incluyendo la distribución y el mobiliario sugerido.
- Ideas para la decoración interior que sigan el estilo minimalista.
- Sugerencias para imágenes que podrían ayudar a visualizar el diseño."
