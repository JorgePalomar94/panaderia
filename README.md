# panaderia

## Comandos comunes

1) git status (muestra todos los archivos que hayan tenido algún cambio)
2) git add . (guarda todos los archivos que tengan cambios)
3) git commit -m "comentario" (confirmación de cambios más un comentario que describe lo ralizado)
4) git push origin rama (origin es el prefijo de la url del remoto (repositorio) más el nombre de la rama)

### Crear una rama nueva
Existen varias formas de crear ramas

- git branch nombre-rama (preferentemente usar cualquiera de los otros 2)
- git checkout -b nombre-rama
- git switch -c nombre-rama

### Moberse entre ramas

- git switch nombre-rama
- git checkout nombre-rama

### Unir cambios en 2 ramas
Para unir cambios de 2 ramas, tenés que estar en la rama que queres actualizar y correr el siguiente comando

- git merge nombre-rama