los pseudolementos  no forman parte del dom
sirven para el diseño especifico de una parte 
especifica de los elementos seleccionados <br/>

Los pseudo-elementos se añaden a los selectores, pero en cambio, no describen un estado especial sino que, permiten añadir estilos a una parte concreta del documento. <br/>

sintaxis:
```
selector::pseudo-element {
  property: value;
}
```

first-line <br/>
```
p::first-line {
  color: blue;
  text-transform: uppercase;
}
```
first-letter <br/>
```
p::first-letter{
    font-size: 50px;
    font-family: 'Franklin Gothic Medium';
}
```