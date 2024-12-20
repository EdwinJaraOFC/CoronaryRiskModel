# CoronaryRiskModel
<p align="justify">CoronaryRiskModel es un modelo predictivo diseñado para identificar el riesgo de enfermedades coronarias utilizando datos demográficos, conductuales y de salud. Este modelo tiene como objetivo ser una herramienta clave para predecir problemas cardiovasculares de manera temprana y contribuir a estrategias de prevención más eficaces.</p>

## Contexto del desarrollo
<p align="justify">El desarrollo de este modelo y análisis fue realizado inicialmente en Google Colab, un entorno que facilita la ejecución de notebooks y permite el uso de recursos en la nube. Posteriormente, todo el trabajo fue consolidado y organizado en este repositorio para mayor accesibilidad, documentación y estructura.</p>

<p align="justify">Google Colab se utilizó debido a su flexibilidad y facilidad para trabajar con grandes volúmenes de datos y diferentes modelos de aprendizaje automático. Sin embargo, todo el código, junto con los datos y resultados, se han integrado aquí para que puedan ser ejecutados localmente si se desea.</p>

## Visualización en Google Colab
<p align="justify">Si deseas explorar el código y el análisis en su entorno original, puedes acceder al notebook ejecutado en Google Colab mediante el siguiente enlace:</p><a href="https://colab.research.google.com/drive/17lT_uRnLIMA4gGrw1OgcxTQ7_Z6BFhs2?usp=sharing">https://colab.research.google.com/drive/17lT_uRnLIMA4gGrw1OgcxTQ7_Z6BFhs2?usp=sharing</a> 

<p align="justify">Google Colab proporciona un entorno en la nube que permite ejecutar el código sin necesidad de configuración local. Esto es útil para revisar el modelo, los gráficos generados y el análisis de manera interactiva.</p>

## Estructura del repositorio

```bash
CoronaryRiskModel/
├── data/                   # Carpeta con los datasets utilizados en el análisis
│   ├── train.csv           # Dataset de entrenamiento
│   ├── test_public.csv     # Dataset de prueba público
│   ├── test_private.csv    # Dataset de prueba privado
│
├── notebooks/              # Carpeta que contiene el notebook principal
│   ├── CoronaryRiskModel.ipynb  # Notebook con el análisis y desarrollo del modelo
│
├── results/             # Carpeta con los resultados generados por los modelos
│   ├── resultados.csv      # Archivo final con las predicciones combinadas
│
├── .gitignore              # Archivos y carpetas ignorados por Git
├── LICENSE                 # Licencia del proyecto
└── README.md               # Información general y documentación del proyecto
```
