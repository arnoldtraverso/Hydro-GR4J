# 🌊 Hydro-GR4J

**hydro-GR4J** es una implementación en R del modelo hidrológico conceptual **GR4J (Génie Rural à 4 paramètres Journalier)**. Este repositorio está orientado a fines académicos y de investigación, permitiendo simular caudales diarios a partir de datos de precipitación y evapotranspiración.

## 📌 Objetivos

- Implementar el modelo GR4J de forma clara y reproducible en R.
- Facilitar el entendimiento de la estructura conceptual del modelo.
- Proporcionar ejemplos prácticos con datos hidrológicos reales.
- Servir como base para ejercicios de calibración y evaluación del modelo.

## 🔧 Estructura del modelo GR4J

El modelo GR4J se basa en una representación simplificada del ciclo hidrológico, con solo **cuatro parámetros**:

1. `X1`: Capacidad del depósito de producción (mm)
2. `X2`: Coeficiente de intercambio (mm/día)
3. `X3`: Capacidad del depósito de ruta (mm)
4. `X4`: Tiempo de concentración del flujo de salida (días)

Su estructura incluye:
- Un módulo de producción (almacenamiento y generación de escorrentía).
- Un módulo de transferencia (ruteo y retardo del caudal generado).

## 📁 Contenido del repositorio

