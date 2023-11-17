##Paso 1: Redirigete a la carpeta del proyecto
## Paso 2: Cree el ambiente virtual
python -m venv myenv
## Paso 3: Activar el entorno virtuaal
myenv\Scripts\activate
### Observacion: si esta en MacOs o Linux debe usar:
source myenv/bin/activate
## Paso 4: Instalar las libretas del archivo requirements.txt
pip install -r requirements.txt
## Paso 5: Luego descargar el csv mas reciente de la siguiente url:
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/
## Paso 6: ejecutar la aplicacion
phyton get_excel_resumen_es.py