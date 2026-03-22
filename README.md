# Análisis de Riesgo Crediticio
## Dataset: Give Me Some Credit — Kaggle (2011)

Análisis exploratorio y segmentación de clientes por perfil de riesgo crediticio, 
usando datos reales de 150,000 clientes de una institución financiera de EE.UU. 
Contexto: post-crisis financiera 2008.

## 🛠️ Stack Tecnológico

- **Python** (Pandas, Matplotlib, Seaborn)
- **Power BI** (Dashboard interactivo)
- **Google Colab** (Entorno de desarrollo)

## 📁 Estructura del Proyecto
```
analisis-riesgo-crediticio/
│
├── notebook/     → Análisis completo en Python
├── dashboard/    → Dashboard en Power BI
└── datos/        → Dataset procesado
```

## 🔧 Limpieza de Datos

- 19.8% de clientes sin ingreso declarado → imputado con mediana
- 4 columnas con decimales incorrectos → corregidas a enteros
- 28,994 clientes con DebtRatio imposible → capeado en 10
- 2,277 registros con ingreso < $100 → excluidos de visualizaciones

## 💡 Principales Hallazgos

- Solo el **6.7%** de clientes entró en mora — dataset desbalanceado
- Clientes de **Alto Riesgo** tienen **22x** más probabilidad de default
- **19.8%** de clientes sin ingreso declarado — limitación clave del dataset
- **35,137 clientes** con DebtRatio > 1 — posible sobreendeudamiento

## 📊 Segmentación por Perfil de Riesgo

| Segmento | Clientes | Tasa de Mora |
|---|---|---|
| Bajo Riesgo | 112,436 (75%) | 2.3% |
| Riesgo Medio | 31,736 (21.2%) | 14.3% |
| Alto Riesgo | 5,828 (3.9%) | 50.7% |

## 🏦 Recomendaciones de Negocio

1. **Monitoreo preventivo** → 31,736 clientes de Riesgo Medio requieren seguimiento activo
2. **Alerta temprana** → activar cuando cliente supere 75% de utilización de crédito
3. **Revisión de ingresos** → 19.8% sin ingreso registrado representa un punto ciego

## 👤 Autor

**Herles Daniel Lopez Bancho**
Data Analyst BI | Estudiante Ing. de Sistemas
[LinkedIn](https://linkedin.com/in/daniel-lopez-572680194)
