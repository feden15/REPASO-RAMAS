# Clase 6 - Bootcamp

## Repaso GIT

# Creo el repositorio GIT

```sh
git init
```

# Listo el estado de lops archivos

```sh
git status
```

# Haciendo un commit

1. Agrego al área de staging los archivos que necesito que formen parte del commit

```sh
git add <nombre-archivo>
git add <nombre-archivo> <nombre-archivo> <nombre-archivo>
git add . # Agrega todos los archivos del Working directory (WD)
```

2. Hago el commit

```sh
git commit -m "Mensaje descriptivo"
```

# Cambiar el editor por nano

```sh
git config --global core.editor nano
git config --global core.editor "code ---wait"
```

# Ver listado de commits que hice en el repo

```sh
git log # Versión larga
git log --oneline # Versión corta
```

# Agregar un remoto a mi repositorio local

```sh
git remote add origin <URL-al-repo-remoto>
git remote add origin https://github.com/feden15/REPASO-RAMAS.git
```

# Para ver si se agregó el repo remoto

```sh
git remote -v
```

# Subo al remoto el repositorio local

```sh
git push -u origin main # La primrera vez
git push
```