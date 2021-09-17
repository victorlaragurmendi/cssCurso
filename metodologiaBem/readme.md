
esta metodologia indica separar los selectores con 
dos guiones bajos juntos __ para especificar al contenido 
que hacemos referencia

en general:
.elementopadre__elementohijo:first-child{
    color:red
}
cambiamos al promero de los hijos a color rojo

.elementopadre__elementohijo--active{
    color:red
}
para referenciar a alguno de los hijos usamos el active
```
el html:
 <div class="nombre-form"><input type="text" class="nombre-form__input">
        <input type="text" class="nombre-form__input">
        <input type="text" class="nombre-form__input">
        <input type="text" class="nombre-form__input--active">
        <input type="text" class="nombre-form__input">
</div>

el css
  .nombre-form__input:first-child{
      background-color: red;
  }
  .nombre-form__input--active{
      background-color: yellow;
  }
```  