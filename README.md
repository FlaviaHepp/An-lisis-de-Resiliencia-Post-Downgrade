# 🏦📉Análisis de Resiliencia Post-Downgrade

## 📌Descripción del proyecto

Este proyecto implementa una consulta SQL para analizar la resiliencia de entidades o instrumentos financieros después de un evento de downgrade crediticio.

El objetivo es evaluar cómo evoluciona el desempeño luego de una rebaja de calificación, identificando si la entidad:
- Se estabiliza
- Continúa deteriorándose
- Muestra señales de recuperación
- Este análisis permite medir impacto, duración y capacidad de recuperación ante shocks crediticios.

## 🎯Objetivos del proyecto

- Analizar el comportamiento posterior a un downgrade.
- Medir la resiliencia financiera en ventanas temporales definidas.
- Comparar desempeño pre y post evento.
- Detectar patrones de recuperación o deterioro.
- Automatizar análisis de eventos crediticios con SQL.

## 🏦Contexto financiero

Los downgrades crediticios son eventos críticos que impactan:
- Costo de financiamiento
- Confianza del mercado
- Riesgo percibido
- Decisiones de inversión

📌 Analizar la resiliencia post-downgrade es clave para:

- Gestión de riesgo
- Análisis de crédito
- Portfolio management
- Stress testing
- Regulación y compliance

## 🧠Lógica del análisis

La consulta SQL:
- Identifica la fecha del evento de downgrade.
- Define ventanas pre y post evento.
- Calcula métricas clave (precio, spreads, volúmenes, ratios).
- Mide variaciones y velocidad de ajuste.
- Clasifica el comportamiento post-downgrade, por ejemplo:
- Resiliente
- Neutro
- No resiliente

📌 La lógica es adaptable a distintos activos y métricas.

## 📊Ejemplos de insights

- Entidades que recuperan niveles previos tras un downgrade.
- Casos donde el impacto se amplifica en el tiempo.
- Diferencias de resiliencia entre sectores o regiones.
- Duración promedio del efecto negativo.

## 🛠️Tecnologías utilizadas

SQL

Compatible con:
- PostgreSQL
- SQL Server
- BigQuery
- Oracle
- MySQL (con ajustes menores)

## 📁Estructura del proyecto

├── analisis_de_resiliencia_postdowngrade.sql
└── README.md

## ▶️Cómo utilizar la consulta

Abrir el archivo analisis_de_resiliencia_postdowngrade.sql.

Configurar:
- Tabla de eventos crediticios
- Métrica de análisis
- Ventanas temporales
- Ejecutar la consulta en el motor SQL.
- Analizar resultados o integrarlos en reportes y dashboards.

## 🚀Posibles extensiones

- Comparar múltiples downgrades.
- Analizar efecto acumulado de eventos.
- Incorporar benchmark sectorial.
- Generar alertas automáticas.
- Integrar con modelos de riesgo.

## 👤Autora

Flavia Hepp
Proyecto de SQL aplicado a análisis de riesgo crediticio y eventos financieros.
