# Proba-repo

## Practica 1: creacion e conexion de repositorios git

### Comandos empregados

```bash
git init
```

>Sirve para inicializar un repo local 

```bash
git commit -m ""
```
>Sirve para comentar una actualizacion de ficheros

```bash
git log --oneline --graph --decorate --all
```
>Sirve para recibir una lista de todos los commit

```bash
git remote add origin https://github.com/mnotac/Proba-repo.git
```
>vincula el repositorio de github online con el local

```bash
git push -u origin main
```
>sincroniza los archivos del repositorio onlin con los del local


```bash
git branch -M main  
```
>cambia la rama a main

```bash
git status
```
>sirve para ver el estado del repositorio local

```bash
git push -u origin main
```
>sirve para sincronizar los archivos desde la rama main

## Practica 2: Ejercicios de git

### Comandos utilizados

```bash
> git config --global user.name "Your-Full-Name"
> git config --global user.email "your-email-address"
> git config --global color.ui auto
> git config --list
```
>git config sirve para configurar nuestro git user.name para nuestro usuario user.mail para nuestro email color.ui auto paraactivar el coloreado de la salida y --list para ver la configuracion
```bash
git status
git add
```
>git status sirve para para mirar el estado del repositorio local y git add añade los contenidos del archivo al index

```bash
git diff
```
>muestra los cambios que se hicieron en un archivo

```bash 
git commit --amend -m
```
>sirve para modificar el ultimo commit realizado 

```bash
git log
```
>Muestra las diferencias entre la última versión y dos versiones anteriores.

```bash
git annotate indice.txt
```
>muestra quien hizo los cambios en un fichero
```bash
git checkout --<file>
```
>Deshace los cambios realizados en el fichero  para volver a la versión anterior.
```bash
git reset <file>
```
>Quita los cambios de la zona de intercambio temporal, pero los mantiene en el directorio de trabajo.
```bash
git clean -f
```
>Deshace los cambios realizados para volver a la versión del repositorio.
```bash
git reset --hard <file>
```
>Quita los cambios de la zona de intercambio temporal, del archivo y del directorio de trabajo.
