# 📊 Desafío 2 – Predicción de Cancelación de Clientes

## 📌 Objetivo
Analizar los factores que influyen en la cancelación de clientes y construir modelos de Machine Learning capaces de predecir el churn, con el fin de apoyar la toma de decisiones estratégicas orientadas a la retención.

---

## 🔍 Análisis de Datos
El análisis exploratorio y dirigido permitió identificar patrones claros asociados a la cancelación:

- **Tiempo de contrato (tenure):** Clientes con menor antigüedad presentan mayor probabilidad de cancelar.
- **Gasto mensual:** Cargos mensuales elevados están asociados a un mayor churn.
- **Tipo de contrato:** Los contratos mensuales concentran la mayor tasa de cancelación.
- **Características del servicio:** Algunos servicios muestran mayor riesgo de churn, lo que sugiere oportunidades de mejora.

---

## 🤖 Modelos Implementados
Se desarrollaron y evaluaron dos modelos:

- **Regresión Logística (con estandarización):**  
  Modelo interpretable que permite entender el impacto de cada variable en la cancelación.
  
- **Random Forest (sin normalización):**  
  Modelo con mejor desempeño predictivo, capaz de capturar relaciones no lineales entre las variables.

**Resultado:** Random Forest obtuvo mejores métricas globales, mientras que la Regresión Logística aportó mayor claridad para el análisis de negocio.

---

## 🔎 Importancia de Variables
Los modelos coincidieron en que las variables más relevantes para predecir la cancelación son:
1. Tiempo de contrato  
2. Gasto mensual  
3. Tipo de contrato  

Estas variables explican gran parte del comportamiento de churn observado.

---

## 🎯 Conclusiones y Estrategias de Retención
La cancelación de clientes responde a patrones predecibles y medibles. Con base en los resultados, se proponen las siguientes acciones:

- **Retención temprana:** seguimiento y beneficios para clientes nuevos.
- **Optimización de precios:** revisión de planes con altos cargos mensuales.
- **Incentivos a contratos largos:** promover planes anuales o bianuales.
- **Mejora del servicio:** priorizar segmentos con mayor riesgo de churn.

---

## ✅ Conclusión Final
El uso de modelos de Machine Learning permitió identificar los principales factores que influyen en la cancelación y construir herramientas predictivas confiables. Estos resultados facilitan la implementación de estrategias de retención más efectivas y basadas en datos, contribuyendo a mejorar la fidelización y la rentabilidad del negocio.
