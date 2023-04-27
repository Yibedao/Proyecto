Se descarga git y se instala en el pc.
Recordamos tildar la opción de "git bash here" y seleccionamos la opción de visual studio as git default editor. 
Abrimos el git entrando a nuestra carpeta en visual studio, picamos en terminal.
Seleccionamos el "+" y seleccionamos "git bash" y borramos el otro. 
Configuramos el usuario con: git config --global user. name "Elisa"
El email con: git config --global user.email elidosamon@gmail.com
Corroboramos si quedó impacatada con: git config user.name, y git config user.email
-------
Usamos el comando (por primera y única vez): git init. Con esto estaremos trabajando en el "working directory" que es donde se generan las lineas de código. Debe aparecer (master) al final. 
Para pasar nuestros archivos a la stating area, usamos el comando: git add (nombre del archivo)
Podemos revisar el status para asegurarnos que todo está donde queremos. 
Después pasamos todo al "repository" con el comando: git commit -m "incoporamos git a nuestro root"
Al terminar de commitear se nos genera una versión nueva y nos pocisiona en el "working directory" de forma automática. 
------
Para controlar los estados de mis archivos/directorio se hace con el comando: git status