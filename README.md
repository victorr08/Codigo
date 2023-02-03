# Primer dia usando Git y Git-Hub
Lista de comandos de Git
* Para poder ver la version de Git usamos:
```bash
git --version
git -v
```
* Para configurar nombre y correo (solo la primera vez en mi maquina)
```bash
git config --global user.name "Víctor Barazorda"
git config --global user.email "victorbarazorda@gmail.com"
```
* Para ver la configuracion de Git
```bash
git config --list
```
* Para inicializar el repositorio
```bash
git init
```
* Para ver estado de nuestros cambios
```bash
git status
```
* Para preparar nuestros archivos para la zona de stage (prepararlos para commit)
```bash
git add . 
git add nombre del archivo. extension
```
* Crear el registro de los cambios realizados
```bash
git commit -m "comentario corto pero especifico"
```
* Para crear una linea de tiempo de lo que hemos realizado
```bash
git log
```
* Para poder ver el detalle de un commit en specifico
```bash
git show
```

