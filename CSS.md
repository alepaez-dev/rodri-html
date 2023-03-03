# CSS

Formas de implementar CSS a nuestro HTML
1. Inline CSS -> Justo donde se está haciendo el elemento de HTML (muy redundante)
2. Internal sheet -> Dentro del documento de HTML -> index.html (se ve feo uakala, solo sirve pa un documento de html, no hay separacion)
3. External sheet -> Un archivo aparte que mandas a llamar


```css
button {
  color: red;
  border:1px solid orange;
  background-color:blue;
  width: 6.25rem;
  height: 50px;
}
```


### Unidades
En CSS cuando hablamos de unidades hablamos de
- Pixeles
- Rems -> tamaño elemento raiz
- Ems -> tamaño elemento padre
- vw -> ancho ventana gráfica
- vh -> altura ventana gráfica


### Selectores
La forma de apuntar a un elemento y aplicarle CSS

###### Selectores básicos
1. Elemento
2. Clases
3. Ids

Prioridad: Id > Class > Elemento