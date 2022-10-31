# example_package_nagore_ainhoa3333
Con este paquete se puede realizar un an�lisis descriptivo con estad�sticos y distintas visualizaciones.

Se ha seguido la siguiente estructura de carpetas y archivos:

1. Carpeta general
En esta carpeta se encuentran las siguientes carpetas y archivos.
 
  1.1. Carpeta dist
  
  1.2. Carpeta src
  En esta carpeta se encuentra la siguiente carpeta:
    
    1.2.1. Carpeta example_package_nagore_ainhoa
    Dentro de esta se encuentran los siguientes 3 archivos .py

	1.2.1.1. Archivo __init__.py
	Es necesario para poder importar correctamente el directorio como un paquete, asimismo, debe estar vac�o.

	1.2.1.2. Archivo functions.py
	Se encuentra la clase generada para la librer�a. Cuenta con diferentes funciones para llevar a cabo el an�lisis exploratorio de los datos a partir de un archivo csv como input.
	- Null_Zeros, devuelve como output una tabla con las siguientes columnas; Nan values, Nan percentage (%), Zero values y Zero percentage(%). 
	- Repeated_Rows, devuelve una tabla con las filas duplicadas en caso de haberlas.
	- Repeated_Columns, devuelve una tabla con las columnas duplicadas en caso de haberlas.
	- Duplicates_UniqueValues, devuelve una tabla con los valores duplicados en caso de haberlos.
	- Numeric_Variables, con esta funci�n se grafica la distribuci�n, devuelve descriptivos de las variables num�ricas.
	- Categorical_Variables, devuelve gr�ficas para las variables categ�ricas.
	- Descriptives, devuelve un resumen de todas las funciones anteriores.

  1.3. Archivo LICENSE
  La licencia del paquete. Esta indica a los usuarios que instalen el paquete los t�rminos bajo los que pueden utilizarlo. En este caso se ha usado la licencia MIT ya que al ser de software libre permisiva pone muy pocas limitaciones en su reutilizaci�n y posee excelente compatibilidad de licencia. Asimismo, es compatible con muchas licencias copyleft y ni tiene copyright, lo que permite su modificaci�n.

  1.4. Archivo Pruebas.ipynb
  Se hace uso de la librer�a con el csv que se le indique como input. Para su uso se requiere una instalaci�n de la librer�a. Una vez instalada se llama a las distintas funciones para poner en funcionamiento la librer�a.

  1.5. Archivo pyproject.toml
  Se divide en 3 apartados:
	
    1.5.1. Build system
    - Requires: los paquetes necesarios para instalar la librer�a y poder hacer uso de ella
    - Build-backend: el nombre del objeto Python que se utilizar�n para realizar la construcci�n.

    1.5.2. Project
    - Name: nombre del paquete
    - Versi�n: versi�n del paquete creado
    - Authors: autores del paquete
    - Description: breve descripci�n de lo que hace este paquete
    - Readme: el archivo readme
    - Classifiers: el �ndice y descarga algunos metadatos adicionales sobre el paquete.

    1.5.3. Project.urls
    Se encuentran los urls tanto de github, como de bug tracker.
    This package will consist on some functions to generate a descriptive analysis.

