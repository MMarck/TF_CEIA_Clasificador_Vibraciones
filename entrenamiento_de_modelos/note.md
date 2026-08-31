numero de parametros: 36

## Seleccion de features
* ALL
* SHAP
* Pearson
* Personalizado1 (solo_tiempo)
* Personalizado2 (solo_frecuenciales)

## metrica a evaluar (optimizar)

* recall
* val_f1_score
* precision
* accuracy

## Balanceo de datos
* SMOTE
* Custom data aumentation


# Combinaciones:
en esta ocasion solo nos centraremos en la optimizacion de la métrica recall.

1. ALL - RECALL - smote (no ejecutada, dado que es una combinacion con resultados conocidos)
2. ALL - recall - Custom data aumentation (no ejecutada, dado que es una combinacion con resultados conocidos)
3. pearson - recall - smote
4. pearson - recall - Custom data aumentation
5. pearson - recall - smote + Custom data aumentation

6. shap - recall - smote + Custom data aumentation
7. shap - recall - smote
8. shap - recall - Custom data aumentation




## Mejores RUNS

LSTM_agregados_v7_2026-08-28_16-41
CNN_Agregados_v7_2026-08-28_16-40
RNN_agregados_v7_2026-08-28_17-22
XGBoost_Agregados_v7_2026-08-28_16-40
DNN_agregados_v7_2026-08-28_15-53