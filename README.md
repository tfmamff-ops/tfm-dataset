# tfm-dataset
Dataset – Verificación de rotulado farmacéutico

Este conjunto de datos contiene 320 imágenes utilizadas en el desarrollo y evaluación del sistema de verificación automática de codificado y rotulado farmacéutico basado en visión artificial y OCR.

Estructura del dataset
dataset/

├── DEBLAX/

├── EUTEBROL DUO/

├── LURAZIC/

├── LUSANDA/

├── PARMITAL/

├── TECNOMET/

├── TEROVAN 100/

└── TIM ASF XR/


Cada carpeta corresponde a un producto farmacéutico y contiene imágenes capturadas desde la línea de producción para un lote específico, con variaciones en iluminación, ángulo y enfoque.
Estas variaciones se utilizan para validar la robustez del modelo de visión frente a condiciones reales de inspección industrial.

Contenido de las imágenes

Formato: .jpg / .png

Resolución promedio: 1280×720 px


Subvariantes: diferencias de lote, fecha de vencimiento y codificado impreso

Uso previsto

Las imágenes se utilizan para:

Entrenamiento y validacion

Evaluación del módulo OCR para detección de lote y fecha

Análisis de precisión y robustez del sistema

Consideraciones éticas y de confidencialidad

Las imágenes fueron obtenidas en entorno controlado dentro de una planta farmacéutica, y no contienen información personal ni datos sensibles.
El uso de este dataset está limitado a fines académicos en el marco del Máster Universitario en Inteligencia Artificial – UNIR.
Queda prohibida su distribución o publicación sin autorización expresa de la empresa colaboradora.

Referencia en el TFM

Este conjunto de datos se describe en el Anexo A – Codigo fuente y datos analizados.
