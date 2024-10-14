<div align="justify"> 
# Ejercicio 2

## Paso 1: Crear repositorio
Primero, debemos crear un repositorio en GitHub, he accedido a mi cuenta y lo he nombrado <b>"ejercicio2-branch"</b>

## Paso 2: Clonar repositorio
Luego, clonamos el repositorio en nuestro equipo local, he utilizado la terminal y he puesto estos comandos:

```bash
git clone  https://github.com/franciscorodalf/ejercicio2-branch.git
```

## Paso 3: Creamos una rama nueva
Creamos una rama nueva para realizar los cambios, he utilizado el comando:

```bash
git checkout -b ejercicio2-branch
```
## Paso 4: Crear archivo
Abrimos el archivo en Visual Code y creamos dos archivos, un <b>Markdown</b> y un archivo java llamado <b>Ejercicio1.java</b>.

En el archivo java ponemos un codigo cualquiera:

```java
     public class Ejercicio1 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }    
```
## Paso 5: Agregar comentario
Una vez creados los archivos, agregamos un comentario en el <i>.git</i>:
```bash
git commit -m "Se incluye el Ejercicio1.java"
```

## Paso 6: Subir los cambios
ejecutamos el comando:
```bash
git push origin ejercicio2-branch
```
## Paso 7: Fusionar rama main
Finalmente, fusionamos la rama <b>ejercicio2-branch</b> con la rama <b>main</b>:
```bash
git checkout main
git merge ejercicio1-branch
```

## Paso 8: Push
Finalmente, subimos los cambios a GitHub:
```bash
git push
```

Si todo ha salido bien, a la hora de hace el comando <i>push</i>
```bash
Enumerando objetos: 4, listo.
Contando objetos: 100% (4/4), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (4/4), listo.
Escribiendo objetos: 100% (4/4), 1.05 KiB | 1.05 MiB/s, listo.
Total 4 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/franciscorodalf/ejercicio2-branch
 * [new branch]      main -> main
```
</div>