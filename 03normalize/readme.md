sirve para tener la pagina sin las preconfiguraciones del navegador 
que siempre vienen por defecto para palicar nosotros nuestros estilos y se apliquen
tal cual en todos los navegadores

como usarlo 
lo usamos via npm

npm install normalize.css


o descargamos el archivo normalize.css ctrl+S importamos con link y establecemos algunos parametros segun convenga

```
<head>
    <link rel="stylesheet" href="./normalize.css">
</head>
```

algunas configuraciones para el normalize
para que gestione bien las cajas ;v

```

*{
    box-sizing:border-box;
}
```

para que tome completo las imagenes en moviles 
```
img{
    border-style:none;
    max-width:100%;
}
```
