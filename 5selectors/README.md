# Seletores

Os seletores servem para conectar um elemento HTML com o CSS, possibilitando que o computador os encontre e aplique as definições de estilo.

## Tipos 

* Global selector: `*`, Este seletor abrange **TODOS** os elementos html do documento.
* Element/ Type selecot: `h1, h2, p, div, a...`- Refere aos próprios elementos HTML.
* ID selector: `#home-page` - seleciona o elemento que possui o id.
* Class selector: `.card, .margin` - seleciona todos os elementos que possuem a classe informada.
* Atribute, Pseud-class, Pseud-elemnt.

### Exemplos

**HTML**
```html
    <div class="container">
        <h1 id="title">Título</h1>
        <h2>Subtítulo</h2>
    </div>
```

**CSS**
```css
* {
    margin: 0;
}

.container {
    width: 300px;
    background: #22f604;
    color: #555;
    padding: 10px;
}

#title {
    color: #333;
}

```

Acima foi utilizado como exemplo os seletores globais, id e class.