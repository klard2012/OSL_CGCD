# OSL_CGCD

Programa para la deconvolución de curvas OSL utilizando el método CGCD.

## Autor
**EDWIN JOEL PILCO QUISPE**  
Email: edwinpilco10@gmail.com

## Descripción
Este paquete permite analizar y deconvolucionar curvas OSL (Optically Stimulated Luminescence) usando el método CGCD. Incluye herramientas para procesar archivos Excel, ajustar curvas y guardar resultados.

## Instalación
Puedes instalar el paquete desde PyPI:

```bash
python -m pip install OSL_CGCD
```

O instalarlo localmente desde el archivo `.whl` generado:

```bash
cd dist
python -m pip install osl_cgcd-0.1.1-py3-none-any.whl
```

## Uso básico
Crea un script y utiliza los módulos incluidos:

```python
from OSL_CGCD import modulo
# Ejemplo de uso: ejecutar funciones de análisis
```

## Estructura del paquete

- `modulo1.py`: Deconvolución de curvas OSL a partir de archivos Excel. Permite seleccionar el archivo a procesar y guarda los resultados en la carpeta `deconvolution_results`. Combina los resultados de varias columnas en un solo archivo continuo para análisis posterior.


## Publicación en PyPI
Para publicar una nueva versión:
1. Actualiza la versión en `setup.py`.
2. Construye el paquete:
	```bash
	python -m build
	```
3. Sube el paquete:
	```bash
	python -m twine upload dist/*
	```

## Requisitos
- Python >= 3.6
- Paquetes recomendados: numpy, scipy, matplotlib, pandas, prettytable

## Licencia
Este proyecto es de uso libre para fines académicos y personales.
