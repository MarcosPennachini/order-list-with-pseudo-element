# Order list with pseude element. ONLY CSS

A simple order list with modified order numbers with css.

## Code example

```html
<div class="counters">
  <h3 class="section">Este es un ejemplo</h3>
</div>
```

```css
.counters {
  counter-reset: counters;
}

.section {
  position: relative;
}

.section::before {
  counter-increment: counters;
  content: counter(counters);
}
```

## Link

- Live Demo: [demo]()

## Author

[Marcos Pennachini](https://www.linkedin.com/in/marcos-pennachini-b39898123/)
