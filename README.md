\documentclass{article}
\usepackage{graphicx}

\title{\textbf{BetaBank - Predicción de Churn de Clientes}}
\author{}
\date{}

\begin{document}

\maketitle

\section*{📊 Descripción}

Cada mes, BetaBank enfrenta la pérdida de clientes. En un mundo donde retener usuarios es más rentable que adquirir nuevos, necesitamos adelantarnos a sus decisiones.

Este proyecto desarrolla un modelo de \textit{machine learning} capaz de predecir qué clientes abandonarán el banco pronto, permitiendo tomar medidas preventivas.

\section*{🎯 Objetivo}

Construir un modelo con un \textbf{F1 score} $\geq 0.59$ para clasificar clientes en riesgo de churn. Además, evaluar la métrica \textbf{AUC-ROC} para comparar el desempeño del modelo.

\section*{🏆 Resultados}

\begin{itemize}
    \item \textbf{Modelo utilizado:} \texttt{DecisionTreeClassifier} con hiperparámetros optimizados y un umbral personalizado de $0.16$.
    \item \textbf{F1 Score obtenido:} $0.597$ (superando el umbral mínimo).
    \item \textbf{Precisión:} $0.579$ \quad \textbf{Recall:} $0.615$ (balance óptimo).
    \item \textbf{AUC-ROC:} $0.767$ (buena capacidad de discriminación).
\end{itemize}

La curva ROC confirma que el modelo supera la aleatoriedad, permitiendo identificar clientes en riesgo con alta efectividad.

\vspace{1cm}

\textbf{📌 Con estos insights, BetaBank puede implementar estrategias para evitar la fuga de clientes y mejorar su retención.}

\end{document}
