# Primer día con Git y Github

Lista de comandos de git
* Para poder ver la versión de git
ejecutamos en nuestra terminal:

```bash
git --version
git -v
```
*Para configurar el correo y nombre (sólo la primera vez en mi máquina)

```bash
git config --global user.email "cristhina.cerron.c@uni.pe"
git config --global user.name "Mi nombre"
```

*Para ver la configuración de git

```bash
git config --list
```
*Para inicializar nuestro repositorio en git:
```bash
git init
``` 
*Para ver el estado de nuestros cambios
```bash
git status
```
*Para preparar nuestros archivos para la zona de stage (prepararlos para commit)
```bash
git add
git add nombreDelArchivo.extensión
```
*Crear el registro de los cambio realizados
```bash
git commit -m "comentario corto y preciso"
```
*Para ver una linea de tiempo de los commits que 
hemos realizado:
```bash
git log
```
* Para poder ver el detalle de un commit especifico usamos:
```bash
git show id-de-commit
```

