usaremos las medidas realtivas para los textos

medidas por defecto
1em ->>16px


si definimos el tamaño del contenedor esta sea la nueva unidad del em
```
  .contact-form{
      font-size: 20px;
  }
  .contact-form__h2{
    font-size: 1em;
  }
```
la nueva unidad del em es 20px

sirve para todas las unidades que se puedan medir es decir se heredan a los hijos
```
  .contact-form{
      font-size: 20px;
      padding:10px;
  }
  .contact-form__h2{
    font-size: 1em;
    padding:1em;
  }
```

medidas relativas viewport height viewport width

ocupamos toda la pantalla sin margenes
fondo negro
50% de ancho de dispositivo
50% de alto de dispositivo


```
  *{
      padding:0px;
      margin:0px;
  }
  .contact-form{
    background-color:#000;
    width:50vw;
    height:50vh;
    
  }
```
```
font-family fuente que ocupara la letra, si no encuentra la primera toma la segundaen este caso consolas
line-height crece el espacio que ocupara la letra
font-weight grosor de la letra

  .contact-form__h2{
    font-size: 1em;
    font-family: sans-serif,consolas;
    line-height: 2;
  }
  ```