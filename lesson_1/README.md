# Lesson 1: Project Planning & Scope Estimation with CrewAI

Este módulo cubre la configuración inicial, ejecución e inspección de métricas para una tripulación multi-agente (*Crew*) orientada a la planificación y estimación de proyectos de software.

## 🎯 Objetivos de la Lección
- Configurar agentes y tareas utilizando esquemas estructurados en archivos YAML.
- Integrar **Google Gemini** a través del SDK `google-genai` y la librería `LiteLLM`.
- Implementar un flujo asíncrono de ejecución de tareas (`kickoff_async`).
- Calcular costos operativos y consumo de tokens mediante `UsageMetrics`.
- Aplicar patrones de programación defensiva para la extracción de resultados (Pydantic / JSON fallback).
- Renderizar los resultados de tareas e hitos (*milestones*) en tablas HTML utilizando **Pandas**.

---

## 🛠️ Requisitos y Entorno
El proyecto está configurado para ejecutarse en el entorno virtual **`crew_env`** (Python 3.11.18) para garantizar la compatibilidad de librerías científicas y de IA.

### Variables de Entorno
Asegúrate de contar con un archivo `.env` en la raíz del proyecto con la clave correspondiente:
```env
GEMINI_API_KEY=tu_api_key_aqui