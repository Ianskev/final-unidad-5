# Proyecto Unidad 5
  - Ian Kevin Condori Flores

# Metodo de uso para instalar el Proyecto
 - clonar el repositorio y crear un entorno virtual, una ves activado el entorno virtual
   instalar las librerias especificadas `pip install -r requirements.txt`
 - Crear las migraciones y migrar hacia la base de datos escogida
 - `python manage.py makemigrations` y despues `python manage.py migrate`
 - Puede crear un superusuario con el sgte comando (tiene que tener el env activado y estar dentro de la carpeta del proyecto
  al nivel de manage.py) `python manage.py createusperuser`
