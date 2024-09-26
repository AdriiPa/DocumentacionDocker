# DocumentacionDocker
Documentacion proceso de instalacion de Odoo con Docker Compose

1. Configurar Odoo con Docker Compose
     1.1 Crear el archivo docker-compose.yml
         Primero creo una carpeta para el proyecto (docker-odoo). Despues creo el archivo docker-compose.yml.
         Tambien creo la carpeta dev-addons para añadir los modulos personalizados(dam2) y la carpeta config-odoo con la configuracion de odoo personalizada.
2. Iniciar los contenedores.
   Para iniciar los contenedores usare el siguiente comando en la carpeta de proyecto: docker-compose up -d.
3. Crear Modulo Base.
   3.1 Inicio en DockerDesktop la carpeta de docker Odoo.
       Accedo a la terminal y me dirijo a la carpeta dev-addons y me creo el modulo usando el siguiente comando: scaffold dma2.
   3.1. Descomentar codigo de archivos del modulo creado.
       Descomento una serie de archivos que se encuentran en dam2, siguiendo los codigos de la carpeta subida a este repositorio.
4. Acceder a Odoo.
  Una vez hecho lo anterior, accedo a Odoo usando localhost y el puerto que hemos definido (localhost:8069:8069)
  Si todo ha salido correctamente se abrira la aplicacion de Odoo en nnuestro navegador y tendre que introducir usuario y contraseña.
  Una vez que me encuentro dentro de Odoo me dirijo a ajustes y activo el modo desarrollador.
  Una vez hecho esto, busco el modulo creado (dam2) y lo activo.
  Ya podre acceder a el.
5. Conclusion.
   Es un proceso tedioso y hay que tener cuidado con la configuracion de los archivos del modulo a la hora de descomentar.
   En caso de hacer todo correctamente, como se encuentran los archivos de este repositorio, y que no funcione, lo mejor es borrar todo y volver a empezar. 
   
   
