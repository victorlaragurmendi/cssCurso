OVERFLOW
esta propiedad nos ayudad con el desbordamiento del  contenido en una caja dandole
propiedades de scroll 

por defecto la propiedad es <br/>
VISIBLE <br/>

para que adquiera el scroll en el tamaño que le damos a la caja usamos
AUTO <br/>
```
div{    
   width: 300px;
   height: 200px;
   margin: 20px auto;
   background: red;

   overflow: auto;
}
```

aunque no sea necesario escrollear esta propiedad pone la barrita de todos modos <br/>

SCROLL <br/>

```
div{    
   overflow: scroll;
}
```