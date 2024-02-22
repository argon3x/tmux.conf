# Archivo de configuración tmux

## Descripción

Esté es un archivo de configuración para darle un estilo a `tmux` \

el `prefix` que usa por defecto este archivo de configuración es `Alt+F` pero puede ser remplazado \
por `Ctrl+c` solo comentando o eliminando las lineas `4`,`7` y `8`, en caso de querer hacer uso
de otro prefix pero utilizando `Alt` puedes cambiar la letra `f` de `M-f` que esta en la linea `7` \
por la que requieras, en caso de querer usar `Ctrl` pero con otra letra puedes cambiar `M-f` por \
`C-'letra'`, esto solo afectara al prefix no a las funciones que se pueda hacer con el.

### Instalación

* clonar el repositorio

```bash
$ https://github.com/argon3x/tmux.conf.git 
```

* puedes copiar o mover el archivo `tmux.conf` a tu home

```bash
$ cp $PWD/tmux.conf/tmux.conf ~/.tmux.conf

$ mv $PWD/tmux.conf/tmux.conf ~/.tmux.conf
```

* o puedes hacer un enlace simbólico

```bash
$ ln -svf $PWD/tmux.conf/tmux.conf ~/.tmux.conf
```

### Screenshot

![Screenshot](screenshot.png)
