# MobileSAM

MobileSAM es una variante optimizada del modelo de segmentación Segment Anything Model (SAM), desarrollada con el objetivo de adaptarse a dispositivos móviles y entornos con recursos computacionales limitados. Esta versión ligera conserva la compatibilidad con el pipeline original de SAM, pero introduce un codificador de imágenes más eficiente que reduce drásticamente el tamaño del modelo y los requerimientos de procesamiento, sin comprometer la calidad de los resultados.

Gracias a esta optimización, MobileSAM es capaz de ofrecer segmentación de imágenes casi en tiempo real, lo que lo convierte en una solución ideal para aplicaciones interactivas. Su entrenamiento se llevó a cabo utilizando una sola GPU y un subconjunto del 1% del conjunto de datos original de SAM (aproximadamente 100.000 imágenes). Esta eficiencia en el entrenamiento y la inferencia permite ampliar el uso de modelos de segmentación avanzados a contextos antes inaccesibles por limitaciones de hardware.
