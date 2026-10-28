# Taller práctico de análisis de datos con Pandas
## Ventas en librerías y tiendas culturales — Letras y Café

Proyecto académico en Python y Jupyter Notebook que resuelve los ejercicios del enunciado usando `ventas_libreria_cultural.csv`.

## Contenido
- `analisis_ventas_libreria.ipynb`: notebook con explicación y solución de los ejercicios.
- `ventas_libreria_cultural.csv`: dataset de entrada.
- `requirements.txt`: dependencias de Python.
- `.gitignore`: archivos y carpetas locales que no deben versionarse.

## Requisitos
- Python 3.10 o superior recomendado.
- Visual Studio Code con las extensiones **Python** y **Jupyter**, o Jupyter Notebook instalado.

## Instalación en Windows (PowerShell)
Abre esta carpeta en Visual Studio Code y, en la terminal integrada, ejecuta:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Si PowerShell no permite activar el entorno, puedes instalar las dependencias usando `python -m pip install -r requirements.txt` sin activarlo.

## Ejecución
1. Abre `analisis_ventas_libreria.ipynb` en VS Code.
2. Selecciona el kernel de Python del entorno `.venv` (si lo creaste).
3. Ejecuta las celdas en orden con **Run All**.
4. El CSV debe permanecer en la misma carpeta del notebook.

También puedes ejecutar desde la terminal:

```powershell
jupyter notebook analisis_ventas_libreria.ipynb
```

## Hallazgos de verificación inicial
El archivo recibido contiene 1.012 filas y 8 columnas; hay 12 filas duplicadas completas, 50 valores ausentes en `Precio_Lista` y 89 en `Descuento_Aplicado`. El notebook verifica estos datos al ejecutarse; los resultados se obtienen del archivo adjunto, no están codificados como valores fijos.

## GitHub
Antes de subirlo, crea un repositorio público en GitHub. Desde la terminal, en esta carpeta:

```bash
git init
git add .
git commit -m "Agregar análisis de ventas con Pandas"
git branch -M main
git remote add origin URL_DE_TU_REPOSITORIO
git push -u origin main
```

Reemplaza `URL_DE_TU_REPOSITORIO` por la dirección real del repositorio que crees. No subas el entorno virtual `.venv/` ni configuraciones personales de `.vscode/`. El CSV se incluye porque es el dataset requerido para ejecutar el análisis.
