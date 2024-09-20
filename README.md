# FDV_1.1

## _**1. Crea una carpeta que incluya 2 imágenes y 3 ficheros de texto. La utilizaremos para crear un repositorio Git que se conecte a GitHub. Puedes utilizar comandos o una herramienta visual. Las imágenes deben tener seguimiento LFS. Añade una imagen adicional y un fichero adicional y actualiza el repositorio GitHub con la nueva versión del proyecto.**_

Primero, creamos el repositorio desde la propia página de Github.

![1  Crear repositorio Github](https://github.com/user-attachments/assets/04037216-e417-4b32-915a-68f1591d26bc)

A continuación, y empleando Github Desktop, clonamos el repositorio recién creado a nuestro equipo.

![2  Clonación repo](https://github.com/user-attachments/assets/f1cad929-4ffe-47de-a262-1c28b5b008a5)

Una vez se ha clonado el repositorio, creamos las dos imágenes y los tres ficheros de texto solicitados y hacemos _commit _y _push_ para subirlos al repositorio.

![3  Creación de archivos](https://github.com/user-attachments/assets/ace17053-e087-4d0c-a9f7-47bea845c698)

Tras haber subido los archivos, instalamos Git LFS y realizamos un seguimiento de todos los archivos con la extensión `.jpg` medianto comandos.

```
git lfs install
```

```
git lfs track ".*jpg"
```

![4  Git LFS](https://github.com/user-attachments/assets/7a9cb87a-63aa-4b72-9831-181b9e94a669)

Ahora añadimos los archivos adicionales.

![5  Creación de archivos adicionales](https://github.com/user-attachments/assets/2948c4cf-66d2-4558-8769-fa58221759a2)


## **_2. Crea un repositorio Git LFS para el proyecto Unity de la tarea 1.2. Configura el fichero .gitattribute adecuado. Una segunda versión del fichero debe incluir una textura y un segundo script que muestre el mensaje en consola "Script tarea 1.2". Obtener capturas de pantalla del proceso para realizar la entrega de la práctica._**

Se crea un nuevo repositorio para la tarea 1.2, esta vez empleando Github Desktop.

![6  Creación de un nuevo repositorio para la tarea 1 2](https://github.com/user-attachments/assets/c68bb5ff-6c56-4b47-8ec1-70e44057ccdb)

Nuevamente, instalamos Git LFS y esta vez añadimos una textura y un scrip en específico.

```
git lfs install
```

```
git lfs track "Texture1_LFS.tif"
```

```
git lfs track "Script_LFS.cs"
```

![7  Git LFS 1 2](https://github.com/user-attachments/assets/4f55392b-b7da-43df-a014-c5141ddb5753)

Captura de pantlla con el log "Script tarea 1.2" en la consola:
![8  Script Tarea 1 2](https://github.com/user-attachments/assets/cc98306f-c7b3-4ffd-a1e2-9c396850cd90)

