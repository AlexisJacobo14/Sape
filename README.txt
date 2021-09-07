PWD: PATH actual
ls: ver archivos de la carpeta actual
CD <PATH>: moverte entre directorios
	ruta absoluta: escribiendo todo el path
	ruta relativa: escribiendo a partir de mi path actual
		. = direccion actual
		.. = direccion padreclear´
clear = limpantalla / ctrl l
mkdir <nombre> = create directory
git clone <link> = para clonar repositorio

git status = para ver el estado de cambios

PARA SUBIR UN ARCHIVO

git add . #agrega los cambios del archivo actual
git commit -m "<mensaje describiendo los cambios"
	#si te pide nombre y email:
		git config --global user.name "<tu nombre de usuario>"
		git config --global user.email "<tu email>"
git push -u origin


