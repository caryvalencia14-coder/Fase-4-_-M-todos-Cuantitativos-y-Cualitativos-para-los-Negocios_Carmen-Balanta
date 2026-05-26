# Inteligencia Estrategica de Negocio: Optimizacion de Seguros Parametricos Mediante IA y Analitica Avanzada (Fase 4)

**Estudiante:** Carmen Elena Balanta Valencia  
**Curso:** Metodos Cuantitativos para la Toma de Decisiones  
**Fecha:** Mayo de 2026  

---

## Descripcion del Proyecto
Este repositorio contiene el desarrollo de la Fase 4 (Pipeline de Analitica de Negocios). El objetivo central de la investigacion es aplicar un flujo metodologico avanzado de Ciencia de Datos para evaluar el panorama cientifico, tecnologico y de mercado de la implementacion de Inteligencia Artificial (IA) y Teledeteccion Satelital en el sector de los seguros agricolas basados en indices o parametricos. 

A traves de este pipeline, se transforman datos de literatura cientifica indexada en conocimiento estrategico para mitigar el riesgo de base (basis risk) y disenar modelos de toma de decisiones de alto impacto en el sector corporativo asegurador.

---

## Ecuacion de Busqueda Avanzada (Pasos 1 y 3)
Para garantizar la reproducibilidad del estudio, los datos estructurados se extrajeron de la base cientifica Scopus aplicando la siguiente consulta avanzada, disenada para correlacionar el dominio fintech/climatico con las tecnologias de analitica predictiva:

> TITLE-ABS-KEY ( ("index insurance" OR "index-based insurance" OR "parametric insurance") AND ("artificial intelligence" OR "machine learning" OR "deep learning" OR "big data" OR "satellite" OR "remote sensing") )

---

## Dinamica Temporal de la Literatura (Datos Reales de Scopus)
De acuerdo con la auditoria empirica realizada sobre el archivo historico recopilado (analisis_publicaciones.xlsx), la evolucion de la produccion cientifica en este campo demuestra un crecimiento consolidado en la ultima decada, registrando su pico de actividad en el ano 2025:

| Ano de Publicacion | Volumen de Articulos Indexados |
| :---: | :---: |
| 2008 | 1 |
| 2010 | 2 |
| 2012 | 3 |
| 2014 | 7 |
| 2015 | 3 |
| 2016 | 10 |
| 2017 | 3 |
| 2018 | 6 |
| 2019 | 13 |
| 2020 | 11 |
| 2021 | 14 |
| 2022 | 21 |
| 2023 | 15 |
| 2024 | 16 |
| 2025 | 25 (Maximo Historico) |
| 2026 | 12 (Ventana de analisis parcial en curso) |

---

## Arquitectura del Pipeline Analitico Implementado

### 1. Mapeo Cientifico Estructural (Paso 5)
Utilizando la herramienta Bibliometrix y la interfaz Biblioshiny en R, se evaluaron las redes de co-citacion de autores y la estructura conceptual del dominio. El mapa tematico situa los terminos "remote sensing", "satellite data" e "index insurance" dentro del cuadrante de Temas Motores, demostrando que la evolucion del sector depende de la tecnologia de observacion espacial.

### 2. Mineria de Texto y Analisis de Sentimiento - NLP (Paso 6)
A traves del entorno de Python (Carmen.ipynb), se consumieron modelos de lenguaje preentrenados alojados en la infraestructura de Hugging Face para procesar los resumenes (abstracts) cientificos de Scopus utilizando el modelo Qwen2.5-7B-Instruct.
* Hallazgo: Se detecto una polaridad predominantemente positiva y neutral en torno a la viabilidad de la teledeteccion. Las zonas de sentimiento negativo revelaron los cuellos de botella del mercado: el riesgo de base matematico y la sensibilidad de las polizas a la precision y eleccion de las fuentes meteorologicas tradicionales.

### 3. Modelamiento Estadistico (PDF) y Machine Learning Predictivo (Pasos 7 y 8)
En el cuaderno Untitled5.ipynb, la serie temporal de publicaciones fue sometida a una prueba de bondad de ajuste de Kolmogorov-Smirnov (SciPy.Stats), arrojando los siguientes resultados de p-valor:
* Ajuste de Distribucion Normal: p-valor = 0.7310
* Ajuste de Distribucion Exponencial: p-valor = 0.5508

Estadisticamente, la prevalencia del ajuste Normal indica una fase de maduracion conceptual estable en torno a una media central en los ultimos anos. Basado en esto, se entreno una Red Neuronal Artificial (ANN) secuencial en TensorFlow para modelar las dinamicas de la serie historica. El modelo predice un flujo constante de entre 20 y 25 publicaciones cientificas anuales para el periodo 2026-2028, confirmando que el mercado se encuentra en una ventana de oportunidad optima para el escalado e inversion comercial antes de la saturacion del sector.

---

## Informe Ejecutivo de Inteligencia de Negocios y Estrategia (Paso 9)
Actuando bajo la interpretacion estrategica del modelo de lenguaje avanzado (LLM), los datos empiricos y las curvas de adopcion se tradujeron en tres estrategias corporativas aplicables para una firma aseguradora de frontera:

* Estrategia 1 (Integracion Multifuente / Mitigacion de Riesgo): Desarrollar una plataforma propietaria de ingesta de datos que combine sensores remotos satelitales (frecuencias Sentinel/Landsat) con estaciones meteorologicas IoT en tierra y modelos de aprendizaje profundo (Deep Learning), reduciendo los fallos de correlacion en las polizas parametricas detectados en la literatura cientifica.
* Estrategia 2 (Automatizacion de Liquidacion / Smart Contracts): Disenar e implementar polizas indexadas autoejecutables mediante contratos inteligentes basados en tecnologia Blockchain que se liquiden de forma autonoma en menos de 48 horas tras la validacion del umbral climatico por la IA, eliminando los costos de administracion y peritaje tradicional en campo.
* Estrategia 3 (Penetracion del Mercado Agro-Fintech Verde): Lanzar lineas de microseguros indexados de bajo costo orientados a pequenos agricultores vinculados a lineas de credito verde, utilizando la capacidad de escala masiva que ofrece el monitoreo satelital continuo automatizado.

---

## Matriz de Indicadores Clave de Rendimiento - KPIs (Paso 10)

Para evaluar el desempeno e impacto corporativo de las estrategias disenadas, se establece la siguiente matriz de control cuantitativo:

| Estrategia Relacionada | Nombre del KPI | Formula de Calculo | Meta Operativa (Target) |
| :--- | :--- | :--- | :---: |
| 1. Integracion Multifuente | Precision del Indice de Siniestralidad | (1 - (Reclamaciones no correlacionadas / Total de Siniestros)) * 100 | >= 95% |
| 2. Automatizacion Operativa | Tiempo Promedio de Desembolso (TAT) | Fecha de Pago - Fecha del Evento Climatico | <= 48 horas |
| 3. Mercado Agro-Fintech Verde | Tasa de Crecimiento de Cartera Indexada | ((Polizas Ano Actual - Polizas Ano Anterior) / Polizas Ano Anterior) * 100 | +30% Anual |

---

## Conclusiones del Informe Tecnico
La convergencia de metodos cuantitativos avanzados demuestra que el sector de los seguros basados en indices esta sufriendo una metamorfosis estructural impulsada por la IA. El cumplimiento del pipeline analitico propuesto en esta Fase 4 dota a la organizacion de herramientas predictivas confiables para liderar el sector agroclimatico global y resolver problemas historicos como la brecha de cobertura ante eventos climaticos extremos.

---
