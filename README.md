# Práctica de OpenCV — Carlos

La guía institucional se repite en su parte obligatoria. El mini reto propio simula una placa con seis componentes, gradiente de iluminación y ruido gaussiano; examina Canny, contornos y máscaras.

Este proyecto conserva el código que produjo las figuras y cifras del informe. Las escenas son sintéticas y no representan capturas de cámara. El cuaderno es autónomo y se puede abrir en Google Colab; no se atribuye a Colab una ejecución que no se hizo allí.

## Archivos

- Carlos_OpenCV_Informe.pdf: informe de entrega en PDF.
- Carlos_OpenCV.ipynb: cuaderno con salida guardada.
- Script .py: ejecución desde línea de comandos.
- resultados.json y CSV/PNG: mediciones y evidencias de la ejecución.
- main.tex y archivo Overleaf .zip: fuente editable del informe.

## Repetir el experimento

Instala las dependencias con python -m pip install -r requirements.txt y ejecuta:

    python practica_opencv.py --persona Carlos --salida resultados

En Colab, instala las dependencias que falten y ejecuta el cuaderno de arriba abajo. La corrida reconstruye la carpeta resultados. Para comparar, revisa los CSV/JSON sin modificar la partición de prueba.

Informe en Overleaf: https://www.overleaf.com/project/6aca7002f204bda3f88d8a04
