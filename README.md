# Laboratorio 4 - Segmentación de imágenes con técnicas de agrupación
**Caso:** DermAlpes

## Integrantes

- Samuel Molina Luna
- Daniel Pardo Pardo

## Descripción

Se segmentan lesiones de piel en imágenes dermatoscópicas (ISIC 2016, Tarea 1) mediante K-means aplicado a una representación por píxel que combina color (RGB) y posición (x, y), ponderadas por los parámetros β y λ. Se elige el número de clusters K con el coeficiente de silueta, se define un criterio automático para decidir qué clusters corresponden a la lesión y se construye una máscara binaria. La configuración se ajusta con 15 imágenes y se evalúa sin modificaciones en 5 imágenes de prueba, usando Dice como métrica principal y V-measure como complementaria. Finalmente, se analizan las limitaciones del enfoque y los riesgos de falsos positivos y falsos negativos para DermAlpes.