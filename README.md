## Comandos GIT

- Configurar el usuario de git

```shell
git config --global user.name "Su Nombre"
git congih --global user.email "Email"
```

- "git status" nos permite saber el estado actual de nuestro proyecto
```shell
git status
```

- "git init" nos permite crear un nuevo repositorio de git, solo se debe ejecutar la primara vez

```shell
git init
```

- Para preparar los archivos a guardar "git add"

```shell
git add <filename>
git add -A
git add .
git add *
```

- Guardar los cambios en el repositorio

```shell
git commit -m "Mensaje o descripcion de lo que se esta guardando"
```

- Restaurar el archivo a su estado original

```shell
git restore <filename>
```

- Para crear una nueva rama (branch)

```shell
git branch <branchname> (crea solo la rama)
git checkout -b <branchname> (crea y activa la rama)
```
- Activar una rama (branch)

```shell
git checkout <branchname>
```

- Eliminiar una rama (branch)

```shell
git branch -D <branchname>
```

- Añadir un repositorio remoto (remote)

```shell
git remote add <name> <url>
```

- Remover un repositorio remoto (remote)

```shell
git remote rm <name>
```

- Modificar un repositorio remote (remote)

```shell
git remote set-url <name> <url>
```