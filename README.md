# Codigo 13

##  Comando para GIT
```
git init
```Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git
- :eye: crear una :file_folder: carpeta oculta llamada 


```
git  status
```
- poder listar  y ver si los archivos  estan listos para subir
- ojo en caso los archivos no esten listos se veran de color rojo y cuando lo esten sera color verde

```
git add .
git add nombre_de_archivo
```
- se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash

```
git commit -m "comentario"
```
- crea un punto en la linea de tiempo: time: de nuestros cambios y a estos se le es posible  adjuntar un comentario 
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación
```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github
```
git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la nube, en este caso github
```
git branch
```
- sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente
```
git checkout -b nombre_del_branch
```
- sirve para poder crear branch nuevo y poder trabajar con el
```
git checkout nombre_del_branch
```
- sirve para poder moverme entre ramas
