los elementos en bloque se ajustan al ancho de su contenedor


los siguientes elementos son en "bloque" son los mas usados
```
<h1>, <h2>, <h3>, <p>, <ul>, <li>, <div>, <header>, <nav>, <section>, <article>, <footer>, <form>, <table>
```

los elementos el linea pueden juntarse aa lado siempre que sean chicos 
a los elementos en linea no se les puede dar height ni width 


Los siguientes elementos son "en línea":

```
 <a>, <b>, <span>, <strong>, <img>, <input>, <code>
```

cambiar comportamiento por defecto
```
h2{
    display:inline;
}
```


modelo de cajas 

elementos principales

content   contenido del centro de la caja
padding   entre el contenido y el borde
border    fuera del padding  
margin    fuera del border

sus modificadores en orden son

line-height
padding
border
margin

ejemplos de uso de margin y padding

padding a todos los lados
```
h2{
    padding:100px  
}
```
margin arriba abajo 20px derecha e izquierda 50px
```
h2{
    margin:20px 50px;
}
```
margin 10px arriba 20px derecha 50px abajo 20px izquerda en sentido horario si lo vemos
```
h2{
    margin:10px 20px 50px 20px;
}
```