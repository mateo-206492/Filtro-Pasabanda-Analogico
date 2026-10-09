# Filtro Pasa-Banda Multietapa

  Este repositorio contiene el desarrollo completo de un trabajo centrado en el diseño, análisis, simulación e implementación experimental de un **filtro pasa-banda analógico multietapa**, realizado en el marco de la asignatura *Análisis de Circuitos [TB066] - FIUBA*.

## Descripción general

A partir de un diagrama de polos y ceros asignado, se calculó la función de transferencia del sistema. Luego, se diseñó un circuito electrónico en etapas utilizando filtros activos y pasivos para implementar dicha transferencia. Finalmente, se realizaron simulaciones en Python y LTspice y se validó el diseño mediante mediciones reales sobre una protoboard.

Este trabajo busca establecer un puente entre el análisis teórico de sistemas lineales y su implementación física, contrastando los resultados teóricos, simulados y experimentales.

## Contenido del repositorio

- `informe.pdf`: Informe completo del trabajo práctico con análisis numerico, analisis circuital , diagramas, gráficos y resultados.
- `códigos_python/`: Scripts en Python para:
  - Graficar respuestas al impulso, escalón, seno y cuadrada.
  - Calcular e interpolar diagramas de Bode.
  - Superponer datos experimentales con simulaciones.
- `simulaciones_LTspice/`: Archivos `.asc` con las simulaciones del circuito en el software LTspice.
- `mediciones/`: Capturas del osciloscopio, archivos CSV con datos experimentales y scripts para graficarlos.
- `enunciado/`: Documento original con el enunciado del trabajo práctico.

## Temas contemplados

- Análisis de sistemas LTI en el dominio de la frecuencia.
- Uso de la Transformada de Laplace.
- Implementación de filtros pasa-altos y pasa-bajos.
- Circuitos con amplificadores operacionales (TL081).
- Simulación numérica en Python.
- Simulación de circuitos en LTspice.
- Validación experimental con generador de funciones y osciloscopio.

## Resultados experimentales

Se verificaron las respuestas en frecuencia y en el dominio temporal del filtro mediante mediciones con osciloscopio. Los datos obtenidos se compararon con las simulaciones y análisis teóricos, mostrando un buen ajuste general con diferencias atribuibles a tolerancias de componentes y limitaciones prácticas.

## Autor

- **Mateo Acosta** – [matacosta@fi.uba.ar](mailto:matacosta@fi.uba.ar)  
  Ingeniería Electrónica | Facultad de Ingeniería - Universidad de Buenos Aires  
  

---
