# Actividades
## 1. Inicialización de un repositorio en GIT
**Objetivo**: Aprender a crear un repositorio local (minuto 22:17)
**Instrucciones**
1. Abrir la terminal 
2. navegar a la carpeta del proyecto
```bash
cd mi_proyecto
```
2. inicializar el repositorio GIT con el comando:
```bash
git init
```
4. verificar el estado con:
```bash
git status -s
```

## 2. Realizar el primer commit
**Objetivo**: Realizar el primer commit local
**Instrucciones**
1. Crear un archivo index.html y/o README.md
2. Agregar contenido a los archivos
3. Utilizar 
```bash
git add . 
``` 
para añadir el archivo al área de preparación.
4. Realizar un commit con el comando 
```bash
git commit -m "Mi primer commit" -a 
```
5. Verificar el estado con el comando:
```bash
git log
``` 
Para asegurse de que el commit se realizó correctamente

## 3. Creación y conexión con el repositorio GITHUB
**Objetivo**: Crear un repositorio remoto en GitHub y vincular con el repositorio local
**Instrucciones**
1. Crear una cuenta en GITHUB [GITHUB](https://github.com)
2. Crar un nuevo repositorio en GitHub (sin inicializar el README ni archivos)
3. en la terminal añade el repositorio remoto
```bash
git remote add origin https://github.com/WaldoMS/m1-git-github-3.git
```
4. Verificar que se añadio correctamente
```bash
git remote -v
```
5. Sube el primer commit a GITHUB con
```bash
git push origin master
```
6. Entrar a GitHub y actualizar el repositorio para verificar la existencia
## 4. Crear y trabajar con ramas
**Objetivo**: Aprender a crear y trabajar con ramas
**Instrucciones**
1. Crear una nueva rama llamada `ramaDesarrollo`
```bash
git branch ramaDesarrollo
```
2. Cambiar a rama `ramaDesarrollo`
```bash
git checkout ramaDesarrollo
```
3. Realizar cambios en los archivo de desarrollo
4. Añade y realiza un commit de los cambios
```bash
git add .
git commit -m 'Cambios en la ramaDesarrollo' -a
git 
```
