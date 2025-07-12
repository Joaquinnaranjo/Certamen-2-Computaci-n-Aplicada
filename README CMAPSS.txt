# CMAPSS Dataset Analysis - FD001 to FD004

Este repositorio contiene un script general para analizar los cuatro datasets principales del sistema de simulación CMAPSS 
(Commercial Modular Aero-Propulsion System Simulation), desarrollado por la NASA para estudios de mantenimiento predictivo de motores aeronáuticos.

## 📂 Contenido

- `cmapss_analysis.py`: Script principal que carga, prepara y visualiza los datasets FD001 a FD004.
- `README.md`: Descripción general del repositorio.

## 🧪 ¿Qué hace el script?

- Carga los archivos `train_FD00X.txt` desde una ruta especificada por el usuario.
- Elimina columnas vacías del archivo original.
- Asigna nombres de columnas según el formato estándar de CMAPSS.
- Calcula el Remaining Useful Life (RUL) para cada unidad simulada.
- Grafica la cantidad de registros por unidad en cada dataset.

## 🔧 Cómo usar

1. Descarga los archivos `train_FD001.txt` a `train_FD004.txt`


2. Modifica las rutas en `cmapss_analysis.py`:

```python
file_fd001 = "RUTA/A/TU/ARCHIVO/train_FD001.txt"


Requisitos
Python 3.8+

pandas

numpy

matplotlib

seaborn


NASA CMAPSS dataset: simulación de condiciones de falla para motores aeronáuticos, 
útil para desarrollar y probar modelos de mantenimiento predictivo.

📌 Este repositorio sirve como base para análisis exploratorio, visualización 
y preparación de datos previos a la modelación en proyectos de pronóstico de fallas.
