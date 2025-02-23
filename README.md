# 📊 BetaBank - Predicción de Churn de Clientes  

## 🚀 Descripción  

Cada mes, BetaBank enfrenta la pérdida de clientes. En un mundo donde retener usuarios es más rentable que adquirir nuevos, necesitamos adelantarnos a sus decisiones.  

Este proyecto desarrolla un modelo de *machine learning* capaz de predecir qué clientes abandonarán el banco pronto, permitiendo tomar medidas preventivas.  

## 🎯 Objetivo  

Construir un modelo con un **F1 score** $\geq 0.59$ para clasificar clientes en riesgo de churn.  
Además, evaluar la métrica **AUC-ROC** para comparar el desempeño del modelo.  

## 🏆 Resultados  

- **Modelo utilizado:** `DecisionTreeClassifier` con hiperparámetros optimizados y un umbral personalizado de `0.16`.  
- **F1 Score obtenido:** $0.597$ (superando el umbral mínimo).  
- **Precisión:** $0.579$ | **Recall:** $0.615$ (balance óptimo).  
- **AUC-ROC:** $0.767$ (buena capacidad de discriminación).  

La curva ROC confirma que el modelo supera la aleatoriedad, permitiendo identificar clientes en riesgo con alta efectividad.  

📌 Con estos insights, BetaBank puede implementar estrategias para evitar la fuga de clientes y mejorar su retención.  
