cat > README.md << 'EOF'
# 📊 Análisis de Riesgo Crediticio
## Dataset: Give Me Some Credit — Kaggle (2011)

Análisis exploratorio y segmentación de clientes por perfil de riesgo crediticio, usando datos reales de 150,000 clientes de una institución financiera de EE.UU.

## 🛠️ Stack Tecnológico
- **Python** (Pandas, Matplotlib, Seaborn)
- **Power BI** (Dashboard interactivo)
- **Google Colab** (Entorno de desarrollo)

## 📁 Estructura del Proyecto
- `notebook/` → Análisis completo en Python
- `dashboard/` → Dashboard en Power BI
- `datos/` → Dataset procesado

## 💡 Principales Hallazgos
- Solo el **6.7%** de clientes entró en mora
- Clientes de **Alto Riesgo** tienen 22x más probabilidad de default
- **19.8%** de clientes sin ingreso declarado — limitación clave del dataset

## 📊 Segmentación
|   Segmento   |    Clientes    | Tasa   |
|              |                | de Mora|
|--------------|----------------|--------|
| Bajo Riesgo  | 112,436 (75%)  | 2.3%   |
| Riesgo Medio | 31,736 (21.2%) | 14.3%  |
| Alto Riesgo  | 5,828 (3.9%)   | 50.7%  |
EOF
