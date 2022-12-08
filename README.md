# Primeros pasos Git

## Inicializar git
```
git init
```

## Establecer una conexion a mi escritorio remoto
```
git remote add origin https://github.com/Jlevanos/CODIGO-G19.git
```

## Definir la rama principla(default)
```
git branch -M main
```

## Añadir los cambios a mi repositorio local
```
git add --all
```
## Hacer commit
```
git commit -M "mi primer commit"
```
## subir los cambio al repositorio remoto
```
git push origin main
```
## crear una nueva rama
```
git branch semana01
```
## cambiar de rama a `semana01`
```
git switch semana01
```
## luego de añadir archivos a la rama semana01 subimo los cambios
```
git add --all
git commit -m "cambio de la rama semana01"
git push origin semana01
```

## Para clonar una repositorio
```
git clone https://github.com/Jlevanos/CODIGO-G19.git
```

## Para descargar cambios a nivel repositorio

```
git fetch
```
## Para descargar cambios `dentro de una rama`

```
git pull origin semana02
```
