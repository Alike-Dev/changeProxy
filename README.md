# changeProxy
Script creado para cambiar el proxy de la Terminal en Ubuntu 20.04

Desarrollado por Alejandro Sosa Pérez, estudiante de 2do año, Universidad Ciencias Informáticas de Cuba.

17-dic-2021

Crear en el directorio $HOME las siguientes carpetas

	+chproxyfiles
	  +configuracionProxy1
    +configuracionProxy2
    +....
	
Y asi sucesivamente todos las configuraciones que desee

Dentro de cada directorio copie los archivos que se utilizan para
configurar el proxy para el terminal con las configuraciones deseadas

	/etc/apt/apt.conf
	/etc/environment
	/etc/bash.bashrc

Si va a agregar mas de 2 configuraciones de proxy deberia cambiar
la estructura del "if"  

##  **Importante!!!**
Copiar este archivo en la ruta /usr/bin para que pueda ser 
ejecutado el script en cualquier directorio.
