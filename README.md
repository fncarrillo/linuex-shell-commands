# linuex-shell-commands
Description of every command used on Linux kernel OS based (Debian 11)

#==============================================
#	ARCHIVOS & DIRECTORIOS
#==============================================
#
#	Crear un archivo:	
#	touch nombre_archivo
#
#	Eliminar archivo:	
#	rm nombre_archivo
#
#	Crear carpeta:		
#	mkdir nombre_carpeta
#
#	Eliminar carpeta:	
#	rmdir nombre_carpeta
#	rm -r nombre_carpeta:
#
#=============================================
#		RED
#=============================================
#
#	ip
#
#=============================================
#	GIT & GITHUB
#=============================================
#
#-------CONFIGURACION
#
#	Configurar usuario:
#	git config --global user.name "nombre"
#	
#	Configurar email:
#	git config --global user.email "correo"
#
#	Crear llaves SSH:
#	ssh-keygen -t rsa -b 4096 -C "correo"
#	(~/.ssh/id_rsa.pub)
#
#-------TRAER REPOSITORIO
#
#	Clonar repositorio:
#	git clone link-repositorio#	
#
#-------GESTIONAR CAMBIOS REPOSITORIO  LOCAL
#
#	Chequear cambios realizados:
#	git status
#
#	Agregar cambios a buffer local:
#	git add archivo
#	git add * -> agrega todos los archivos
#
#	Comentar cambios:
#	git commit -m "comentario"
#
#	Subir cambios:
#	(De local a 'rama')
#	git push origin rama
#
#-------ACTUALIZAR REPOSITORIO LOCAL CON REMOTO
#
#	Trae cambios de la rama a un buffer local
#	git fetch
#
#	Trae cambios de 'rama' a local
#	git pull origin rama
#
#-------RAMAS
#
#	Crear rama nueva:
#	git branch rama_nueva
#
#	Moverse a otra rama:
#	git checkout otra_rama
#
#	Unificar ramas:
#	pull request -> Herramienta de GitHub
#	merge request -> Herramienta de GitHub
#
#=============================================
#		INSTALACION
#=============================================
#
#	Extraer tar.gz		
#	tar xvzf archivo.tar.gz
#
#	Extraer tar.bz2		
#	tar xvjf archivo.tar.bz2
#
#	Archivo ejecute	
#	chmod +x nombre_archivo
#
