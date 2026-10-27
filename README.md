# El algoritmo contra el estilo: Análisis técnico de la detección de IA en la literatura contemporánea

Este repositorio contiene una investigación empírica e ingeniería inversa sobre la fiabilidad de las herramientas de detección de Inteligencia Artificial (específicamente Pangram 4.1), utilizando como caso de estudio la novela *Donde el agua trabaja* de David Silva Rojas.

## 📌 Objetivo de la Investigación
Demostrar mediante manipulación controlada de LLMs (Gemini 3.1 Pro) que los detectores de IA evalúan métricas estadísticas (perplejidad y ráfaga sintáctica) y no el proceso creativo. El análisis evidencia que utilizar plataformas como Pangram como fuente única y definitiva para declarar el uso de Inteligencia Artificial en textos narrativos de largo aliento —los cuales poseen intenciones estilísticas, desarrollo de personajes y complejidad estructural— constituye un error metodológico y periodístico.

## 📂 Estructura del Repositorio
- `/reporte_principal`: Contiene el análisis completo en PDF.
- `/evidencia_pangram`: Reportes originales de Pangram exportados en PDF que documentan los falsos positivos y negativos.
- `/datos_y_prompts`: Transcripciones y comandos exactos utilizados para vulnerar el algoritmo.

## 📊 Hallazgos Principales
1. **Manipulación Iterativa:** Tras 9 iteraciones de ingeniería de prompts, un texto 100% sintético fue clasificado por Pangram como "100% escrito por humanos".
2. **Ceguera Editorial:** La corrección de estilo manual por un editor humano sobre un texto de IA resulta invisible para el detector.
3. **El Control del Prompt:** El estilo narrativo dictado a la IA (ej. minimalista y seco vs. adjetivación densa) determina directamente el margen de fallo del detector.

## ⚖️ Aviso Legal y Uso Legítimo (Fair Use)
El presente proyecto ha sido desarrollado con fines estrictamente académicos y de investigación tecnológica. La utilización y modificación algorítmica de fragmentos correspondientes al primer capítulo de la novela *Donde el agua trabaja* (2026), del autor David Silva Rojas y publicada por Editorial Almadia, se realiza bajo el amparo del derecho de cita y las doctrinas de uso legítimo, incluyendo lo estipulado en el Artículo 148 de la Ley Federal del Derecho de Autor en México. Este análisis no persigue ningún fin de lucro ni constituye una obra derivada destinada a su explotación comercial.
