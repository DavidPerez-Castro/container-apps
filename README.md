#Entorno de desarrollo integrado

Docker con Anaconda y Spyder.

Docker-Compose para ejecutar aplicaciones de multiples contenedores.

Instale la aplicación spyder-desktop en su directorio del proyecto:

 curl https://raw.githubusercontent.com/compdatasci/spyder-desktop/master/spyder_desktop.py -outfile spyder_desktop.py
 
Para ejecutar contenedores en Docker-Compose utilice el siguiente comando:

 docker compose up
 
Para abrir Spyder ejecute el siguiente comando:

 python spyder_desktop.py -p
 
Para abrir un servidor Jupyter Notebook de Anaconda e interactuar a través de su navegador:

 http://localhost:8888
 
Y deberá colocar el password que le genera el docker-compose para iniciar sesión en Jupyter Notebook.
