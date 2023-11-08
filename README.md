# Snippets CSS p/ você copiar e colar


Quadrado:
``` html
<div class="meu_elemento"></div>

<style>
  /* CSS */
  .meu_elemento{
    width: 50px;
    aspect-ratio: 1;
    background: blue;
  }
</style>
```

Círculo:
``` html
<div class="meu_elemento"></div>

<style>
  /* CSS */
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: gold;
    border-radius: 50%;
  }
</style>
```

Semicírculo:
<div width="50%">

  ``` html
  <div class="meu_elemento"></div>

  <style>
    /* CSS */
    .meu_elemento{
      width: 50px;
      height: 50px;
      background: red;
      border-radius: 0 0 50% 50% / 0 0 100% 100%;
    }
  </style>
  ```

</div>

<div width="50%">
    <div class="meu_elemento"></div>

  <style>
    /* CSS */
    .meu_elemento{
      width: 50px;
      height: 50px;
      background: red;
      border-radius: 0 0 50% 50% / 0 0 100% 100%;
    }
  </style>
</div>