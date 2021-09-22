tenemos 4 formas de posicionar 

STATIC <br/>
RELATIVE  <br/>
ABSOLUTE  <br/>
FIXED    <br/>
STICKY   <br/>


position <br/>
el elemento posicionado con alguna de las 4 formas adquiere nuevas propiedades
top <br/>
bot <br/>
right <br/>
left <br/>

STATIC es el  valor por defecto <br/>

RELATIVE se mueve el elemento top bottom left right desde su posicion original (respecto de si mismo)
<br/>

ABSOLUTE indica desplazamiento top bottom right left desde el borde del contenedor del elemento (respecto de sus ancestro mas cercano o contenedor)

solo si el elemento padre esta posicionado( relative ) sino sera el viewport la referencia
<br/>
truco para poner al centro un elmento absolute

```
.caja5{
    background: green;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    margin: auto;
}
```

FIXED  elemento fijo se usa para publicidad o nabvar que se yo..
<br/>

STICKY elemento queda fijo hasta donde le llega el scroll y puede estar un poca mas arriba de la cabecera de la pagina dependiendo cuando le indiquemos top

ejemplo sticky

```
.caja-sticky{
    background-color: yellow;
    position: sticky;
    top: 10px;
}
```
<br/>

