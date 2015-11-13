# flexable

Lets you setup simple layouts with [flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes) using 3 classes :


- `fa-box` or `fa-box-h` : make an element a horizontal flex container

- `fa-box-v` : make an element a vertical flex container

- `fa-stretch` : make an element occupy maximum space inside a container


## Example

```html

<div class="fa-box-v">

  <div class="fa-stretch fa-box-h">

    <div class="fa-stretch">empty</div>

    <div>side 1</div>
    <div>side 2</div>

  </div>

  <div>bottom</div>

</div>

```

Will give something like :

    ---------------------------------------
    | empty             | side 1 | side 2 |
    |                   |        |        |
    |                   |        |        |
    |                   |        |        |
    |                   |        |        |
    |                   |        |        |
    |                   |        |        |
    ---------------------------------------
    | bottom                              |
    ---------------------------------------

## Licence

The MIT License (MIT) - Copyright (c) 2015 Alexandre Bintz  
See [LICENCE](LICENCE) file for full text.
