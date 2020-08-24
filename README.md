Plantilla SASS para proyectos a medida, usando `Split media` como estrategia `Responsive Design`.

## HTML

``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, shrink-to-fit=no">
<link href="css/mobile.css" rel="stylesheet" media="all and (max-width: 600px)">
<link href="css/desktop.css" rel="stylesheet" media="all and (min-width: 600px)">
```

## Instalar

1. Clonar repositorio (No descargar) dentro de tu proyecto.

Renombra a `SASS`.

``` shell
mv estructura-sass sass
```

2. Entrar en el proyecto (`estructura-sass` o `sass`).

3. Descargar vendors.

``` shell
git submodule update --init --recursive
```

4. Comprobar que compila.

``` shell
sass mobile.sass
```

5. Borra directorios de `Git`.

``` shell
rm -rf .git main/vendors/symbiosis-css/.git main/vendors/normalize.css/.git
```

6. Disfruta.
