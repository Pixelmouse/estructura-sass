Plantilla universal para proyectos a medida, usando `Split media` como estrategia `Responsive Design`.

## HTML

``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, shrink-to-fit=no">
<link href="css/mobile.css" rel="stylesheet" media="all and (max-width: 600px)">
<link href="css/desktop.css" rel="stylesheet" media="all and (min-width: 600px)">
```

## Cargar vendors

``` shell
git submodule update --init --recursive
```

