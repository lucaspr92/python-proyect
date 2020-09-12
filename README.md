# Python Project

---

## Git

Estos son algunos comandos básicos para usar Git. En `docs` compartí un cheatsheet
con más comandos que nos serán de utilidad.

```bash
# Clonar
$ git clone https://github.com/mrti259/python-proyect.git

# Crear una rama
$ git checkout -b [mi-rama]

# Agregar a stage
$ git add [archivo-1 archivo-2 ...|| .]

# Realizar commit de stage
$ git commit [-m mi-comentario]

# Publicar mis modificaciones
$ git push origin [mi-rama]

# Actualizar mi repositorio -> puede tirar problemas por
# incompatibilidades entre versiones y haya que hacer un merge
$ git fetch
```

En `.gitignore` pueden agregar los directorios y archivos que no
quieran que Git haga seguimiento.
