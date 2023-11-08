# Workshop de desenhos CSS

## Links úteis

- [Guia de Flexbox (pt-BR)](https://www.alura.com.br/artigos/css-guia-do-flexbox)
- [Artigo: Entendendo como funciona o Box Model e o Box Sizing](https://www.alura.com.br/artigos/entendendo-como-funciona-box-model-e-o-box-sizing)
---
- [Codepen](https://codepen.io/)
- [Extensão do Visual Studio Code: Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (Para habilitar o auto-reload em uma aba do navegador)
- [Extensão do Visual Studio Code: Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) (Para deixar os espaços de indetação coloridos, mas é totalmente opcional)

---

# Snippets CSS p/ você copiar e colar

Reset CSS:
``` css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```
Quadrado:
``` html
<div class="meu_elemento"></div>

<style>
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
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: gold;
    border-radius: 50%;
  }
</style>
```

Semicírculo:
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: red;
    border-radius: 0 0 50% 50% / 0 0 100% 100%;
  }
</style>
```

Losango:
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: purple;
    transform: rotate(45deg);
  }
</style>
```

Gota:
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: purple;
    border-radius: 0 50% 50%;
    transform: rotate(45deg);
  }
</style>
```

Fundo gradiente (linear):
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: linear-gradient(blue, violet);
  }
</style>
```

Fundo gradiente (circular):
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 50px;
    height: 50px;
    background: radial-gradient(blue, violet);
  }
</style>
```

Retângulo com borda simples:
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 90px;
    height: 50px;
    background: violet;
    border: 3px solid black;
  }
</style>
```

Elipse com borda pontilhada:
``` html
<div class="meu_elemento"></div>

<style>
  .meu_elemento{
    width: 90px;
    height: 50px;
    background: violet;
    border-radius: 50%;
    border: 3px dotted black;
  }
</style>
```