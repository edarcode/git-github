# Comandos git

- Configura tus credenciales

```
git config --global user.name "Edwin Ortiz"
```

```
git config --global user.email  "edarcode@gmail.com"
```

- Permite ver cambios que se hayan hecho

```
git status
```

- Agrega todos los cambias a **staged**

```
git add .
```

puede agregar el cambio especifico de un archivo remplazando **.** por la ruta del mismo

- Quita cambios de staged

```
git restore --staged
```

- Ver historias de commits

```
git log
```

una versión mas limpia sería

```
git log --oneline
```
