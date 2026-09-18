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

- LSTM_agregados_v7_2026-08-28_16-41
    - SMOTE + SHAP
    - Features(3): ["mean_frequency","rms_frequency","standard_deviation"]
- CNN_Agregados_v7_2026-08-28_16-40
    - SMOTE + SHAP
    - Features(3): ["mean_frequency","rms_frequency","standard_deviation"]
- RNN_agregados_v7_2026-08-28_16-06
    - Custom_data_aumentation + SMOTE + PEARSON
    - Features(10): ["mean_amplitude","slope_sign_change","skewness","hoc3","hoc4","rms_frequency","envelope_rms","mean_kurtosis_trend_derivative","min_kurtosis_variance","max_kurtosis_variance"]
- XGBoost_Agregados_v7_2026-08-28_16-40
    - SMOTE + SHAP
    - Features(10): ["mean_frequency","rms_frequency","standard_deviation"]
- DNN_agregados_v7_2026-08-28_15-53
    - Custom_data_aumentation + PEARSON
    - Features(10): ["mean_amplitude","slope_sign_change","skewness","hoc3","hoc4","rms_frequency","envelope_rms","mean_kurtosis_trend_derivative","min_kurtosis_variance","max_kurtosis_variance"]

