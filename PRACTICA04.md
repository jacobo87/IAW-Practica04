# Creación de una segunda máquina virtual para Apache.
> IES Celia Viñas (Almería) - Curso 2020/2021 
> Módulo: IAW - Implantación de Aplicaciones Web 
> Ciclo: CFGS Administración de Sistemas Informáticos en Red 

## Script front-end

Para la creación de otro segundo **servidor Apache**, seguimos los siguientes pasos:
- Descargamos el repositorio con las herramientas necesarias.
Hacemos un "**git clone**" con el enlace al repositorio donde tengamos alojadas las herramientas que vamos a necesitar.
- [Enlace repositorio con herramientas necesarias.][GitHub]
- Ejecutamos el script previamente configurado.

## El Script ejecutará los siguientes pasos
#### Instalación de la Apache
1. Actualizamos la lista de paquetes.
2. Instalación del servidor web Apache.
3. Instalación de los módulos necesarios de PHP.
#### Instalación de la aplicación web
4. Clonación del repositorio de la aplicación.
	- [Repositorio.][Repo]
5. Movemos el contenido del repositorio al home del directorio html.
6. Configuramos el archivo php de la aplicación.
7. Eliminamos el archivo Index.html de apache.
8. Cambiamos los permisos.
#### Inslación de herramientas adicionales
9. Descargamos Adminer
10. Instalación de GoAccess.
11. Creamos el directorio stats.
12. Lazamos el proceso en segundo plano.
13. Copiamos el archivo de configuracion de apache.
14. Opcional, instalación cliente MySQL.
 - apt install mysql-client-core-8.0


[GitHub]: https://github.com/jacobo87/IAW-Practica04
[Repo]: https://github.com/josejuansanchez/iaw-practica-lamp