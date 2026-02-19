# Laboratorio-1-analisis_estadisticos 
En este laboratorio analizamos señales fisiológicas de ECG empleando herramientas de estadística descriptiva y modelos de ruido. El propósito es comprender tanto las propiedades propias de la señal como la influencia del ruido, evaluando aspectos como la relación señal-ruido (SNR).

---
<h1 align="center"><i><b>PARTE A DEL LABORATORIO</b></i></h1>

+ **importación de librerias y carga de señal**
```python
!pip install wfdb
import matplotlib.pyplot as plt
import numpy as np
import wfdb
import pandas as pd
import os
from scipy.stats import norm
import seaborn as sns
```
Se instalan la libreria `wfdb` para leer archivos locales (.hea, .dat, etc.) del directorio de trabajo. 
Se importan diferentes librerias necesarias para desarrollar el código con sus funciones.
