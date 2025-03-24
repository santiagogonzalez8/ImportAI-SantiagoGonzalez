# ImportAI: Optimización de Importación y Venta con IA

**Autor**: Santiago González  
**Curso**: Inteligencia Artificial - Generación de Prompts  
**Comisión**: 84165  

## Introducción
**Nombre del proyecto**: ImportAI  
Este proyecto busca optimizar la importación y venta de productos en Uruguay utilizando técnicas de *Fast Prompting* con modelos de inteligencia artificial, específicamente Google Gemini.

## Presentación del problema a abordar
El problema elegido es la **dificultad para identificar categorías de productos rentables y proveedores confiables en el mercado uruguayo**, así como la creación de presentaciones visuales atractivas para maximizar ventas. Esto es una problemática porque:  
- Los emprendedores y pequeños negocios en Uruguay enfrentan alta competencia y márgenes ajustados al importar productos.  
- La falta de datos específicos y accesibles dificulta la toma de decisiones informadas sobre qué importar y cómo venderlo.  
- Es relevante desarrollar una solución porque optimizar estas decisiones puede reducir costos, aumentar ganancias y fortalecer el comercio local en un contexto económico competitivo.

## Desarrollo de la propuesta de solución
La solución se vincula al desarrollo de modelos de IA mediante el uso de *Fast Prompting* para obtener respuestas rápidas y precisas de Google Gemini. Los prompts están diseñados para:  
1. Identificar categorías de productos con alta demanda y baja competencia.  
2. Estimar márgenes de rentabilidad para categorías específicas.  
3. Sugerir proveedores confiables en plataformas como Temu o Amazon.  
4. Generar descripciones de imágenes optimizadas para ventas.  

Estos prompts se implementan en un entorno de Google Colab, aprovechando la API gratuita de Gemini para procesar información y ofrecer soluciones prácticas en las siguientes etapas del proyecto.

## Justificación de la viabilidad del proyecto
El proyecto es técnicamente viable porque:  
- **Tiempo**: Se desarrolla en pocas horas, ya que usa una API gratuita y prompts predefinidos, sin necesidad de entrenar modelos complejos.  
- **Recursos**: Solo requiere acceso a internet, Google Colab (gratis) y una API key gratuita de Google Gemini, lo que lo hace accesible con recursos mínimos.  
- **Elecciones**: Elegí Gemini por su nivel gratuito, facilidad de integración y capacidad para responder prompts específicos, lo que asegura resultados rápidos y útiles para el contexto uruguayo.

## Objetivos
- Identificar tres categorías de productos con alta demanda y baja competencia en Uruguay.  
- Estimar márgenes de rentabilidad potenciales para categorías seleccionadas.  
- Recomendar proveedores confiables para importar productos.  
- Proponer descripciones visuales atractivas para optimizar la presentación de productos en ventas.

## Metodología
El proyecto se llevará a cabo mediante:  
- **Definición de prompts**: Creación de cuatro prompts cortos y específicos para obtener respuestas útiles en menos de 150 tokens cada una.  
- **Implementación en Colab**: Uso de Google Colab para ejecutar el código que conecta con la API de Gemini y procesa los prompts.  
- **Validación**: Revisión manual de las respuestas para asegurar coherencia y utilidad.  
- **Justificación**: Este enfoque es eficiente, gratuito y aprovecha la capacidad de Gemini para analizar tendencias generales y ofrecer soluciones prácticas.

## Herramientas y tecnologías
- **Herramientas**: Google Colab, Google Gemini (modelo `gemini-1.5-flash`), GitHub.  
- **Técnicas de prompting**: *Fast Prompting*, usando prompts concisos con un mensaje de sistema ("You are a helpful assistant for product import optimization") y mensajes de usuario claros.  
- **Justificación**: *Fast Prompting* reduce el uso de tokens, optimiza costos (aunque es gratuito) y asegura respuestas rápidas y relevantes.

## Implementación
El código se desarrolla en Google Colab y usa la API de Google Gemini con la clave `AIzaSyBRYO6V85ESKBcJA2f7HB3zbWK0_cfkOz4`. A continuación, el enlace al notebook y los prompts implementados:

### Enlace al Google Colab
[ImportAI en Google Colab](https://colab.research.google.com/drive/1UyuzcVuy1hVFW8DTPI_AEM8VLLTyMyaT?usp=sharing)

### Prompts y código
1. **Prompt 1**: "Dame una lista corta de 3 categorías de productos con alta demanda y baja competencia en Uruguay, basándote en tendencias generales."  
2. **Prompt 2**: "Estima el margen de rentabilidad potencial para estas categorías en Uruguay: Ropa deportiva, Accesorios electrónicos, Juguetes educativos."  
3. **Prompt 3**: "Sugiere proveedores confiables en Temu o Amazon para accesorios electrónicos y juguetes educativos, considerando calidad y presentación."  
4. **Prompt 4**: "Describe una imagen optimizada para vender accesorios electrónicos en Uruguay: usa colores vibrantes y un fondo atractivo para captar atención."  

El código completo está en el `.ipynb` subido al repositorio y en el enlace de Colab. Además, se incluye una imagen generada en Nightcafe:  
[Imagen en Nightcafe](https://creator.nightcafe.studio/studio?open=creation&panelContext=%28jobId%3ADy7na3ujD9zx7SDiWA5T%29)

### Instrucciones
1. Abre el enlace en Google Colab.  
2. Ejecuta todas las celdas para ver las respuestas de Gemini.  
3. Revisa los resultados y la imagen en Nightcafe.
