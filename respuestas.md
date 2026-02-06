### Pregunta 1: Selector CSS

Mi elección por la recomendación de que es simple y justo no planeo usar más imágenes en este formulario es **B) Selector directo a todas las imágenes en main:**

```css
main img {
}
```

### Pregunta 2: Display

Apliqué `display: block` para probar visualmente pero no hubo diferencia, lo dejaré por cualquier cosa para otros navegadores, ¿qué opinas?

### Pregunta 3: Max-width (Responsive)

Usaré `max-width: 100%` por lo que dices de que no se estira, pensando en responsive.

### Pregunta 4: Height

Por tu recomendación, mantendré `height: auto`

### Pregunta 5: Centrado horizontal

Sí, la centré y, además, agregué un `margin-top: 0.5rem;` porque estaba pegada al header.

### Pregunta 6: Margin-bottom

No lo necesito, ya está separada del h2 por los ` margin-top: var(--space-xl);
  margin-bottom: var(--space-lg);` que aplicamos

### Pregunta 7: ¿Algo más?

No lo necesita.

Me adelanté jeje y ya puse el código para ir revisando visualmente cómo queda. La puse solo para probar imágenes, pero yo creo la quitaré porque realmente en nuestros diseños de empresa no usamos imágenes y menos en formularios.

````css
main img {
display: block;
max-width: 100%;
height: auto;
margin: 0 auto;
margin-top: 0.5rem;
}```
````
