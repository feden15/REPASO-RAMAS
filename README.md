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