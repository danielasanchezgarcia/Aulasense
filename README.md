# AulaSense — Monitoreo Inteligente de Aulas

**Proyecto académico | Universidad Politécnica de Querétaro**

## Descripción

AulaSense es una propuesta de sistema IoT para monitorear las condiciones de las aulas mediante sensores que registran variables como temperatura, humedad, ocupación y calidad del aire.

Este repositorio documenta el análisis del diseño original y cuatro propuestas para mejorar la distribución de responsabilidades entre clases, así como una propuesta de arquitectura final integrada.

## Integrantes y propuestas

| Integrante | Propuesta | Archivo |
|---|---|---|
| David Atilano Quiroz | Arquitectura por capas | `02-propuestas/david-capas/01_david_capas.ipynb` |
| Ricardo Ordaz Aguilar | Arquitectura orientada a eventos | `02-propuestas/ricardo-eventos/02_ricardo_eventos.ipynb` |
| Javier Olguín Narváez | Adaptadores y estrategias para sensores | `02-propuestas/javier-sensores/03_javier_sensores.ipynb` |
| Daniela Sánchez García | Separación de registro y consultas | `02-propuestas/daniela-consultas/04_daniela_consultas.ipynb` |

## Organización del repositorio

- **01-analisis-original:** análisis de las responsabilidades y problemas del diseño original.
- **02-propuestas:** propuestas individuales, prototipos y diagramas.
- **03-comparacion-final:** comparación de las cuatro arquitecturas, propuesta integrada y diagrama final.
- **04-evidencias:** registro de aportaciones individuales y enlaces a los Pull Requests.

## Propuesta final

Después de comparar las alternativas, se propone una arquitectura modular por capas que integra:

- Adaptadores para diferentes sensores IoT.
- Procesamiento de mediciones y comunicación mediante eventos.
- Servicios separados para registro y consultas.
- Componentes especializados para alertas, reportes y visualización.

Esta arquitectura busca mejorar la cohesión, reducir dependencias innecesarias y facilitar el mantenimiento, las pruebas y la ampliación del sistema.

La propuesta integrada es conceptual; los notebooks individuales representan prototipos de las alternativas estudiadas.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Matplotlib
- Git y GitHub

## Archivos principales

**Análisis original:** `01-analisis-original/diseno_original.ipynb`

**Comparación final:** `03-comparacion-final/comparacion_arquitecturas.ipynb`

**Evidencias:** `04-evidencias/EVIDENCIAS.md`

## Evidencias de colaboración

Los commits y Pull Requests permiten consultar el historial de participación de cada integrante.

Consultar el [documento de evidencias](04-evidencias/EVIDENCIAS.md) o la [sección de Pull Requests](https://github.com/danielasanchezgarcia/Aulasense/pulls?q=is%3Apr+is%3Aclosed).

## Conclusión

El trabajo permitió analizar diferentes formas de organizar las clases de AulaSense y proponer una estructura más modular, mantenible y extensible, considerando las aportaciones individuales de los cuatro integrantes.
