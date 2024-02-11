# Comandos git

### Configura tus credenciales

```
git config --global user.name "Edwin Ortiz"
```

```
git config --global user.email  "edarcode@gmail.com"
```

### Ver cambios que se hayan hecho

```
git status
```

### Agrega todos los cambias a **staged**

```
git add .
```

puede agregar el cambio especifico de un archivo remplazando **< . >** por la ruta del mismo

### Quita cambios de staged

```
git restore --staged
```

### Ver historial de commits

```
git log
```

una versión mas limpia del historial

```
git log --oneline
```

### Navegar entre commits

```
git checkout idCommit
```

### Diferencias entre último commit y los cambios recién hechos

```
git diff
```

también es posible ver diferencias entre 2 commits

```
git diff idCommit idCommit
```

### Borrar todos cambios recién hechos

```
git restore .
```

también puede borrar los cambias de 1 archivo especifico remplazando **< . >** por la ruta del mismo
