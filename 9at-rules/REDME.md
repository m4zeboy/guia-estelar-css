# @ At Rules

* Essas são regras especiais que estão relacionadas ao comportamento do CSS.

**Anatomia**

Uma at rule começa com o arroba `@`, seguido por um identificador que leva o nome da regra e termina no primeiro ponto e vírgula `;`.

Existem várias at rules:

* `@charset`, Define os caracteres suportados pela folha de estilos;

```css 
    @charset "UTF-8";
    /* Precisa das aspas para funcionar; indica que será usado a codificação unicode utf-8 */
```

* `@import`, Importa uma folha de estilos externa;

```css 
    @import url("https://local/styles.css"); 
    /* Função url que especifíca que é uma url */
```

* `@media`, Para responsividade. Caso o dispositivo cumpra a definição de mídia, será aplicado o conjunto de regras dentro dessa at rule.;

```css 
    @media(min-width: 800px) {
        /* Regras aqui - Nessa regra se aninham outras definições css */
        h1 {
            font-size: 95%
        }
    };
```

* `@font-face`, descreve o aspecto de fontes externas que precisam ser baixadas.;

```css 
    @font-face {
        font-family: "SF Pro Display";
        src: url("/fonts/SF-Pro-Display.woff") format("woff")
    } 
    /* Precisa das aspas para funcionar; indica que será usado a codificação unicode utf-8 */
```

## Grupos condicionais de regras

Cada regra at possui uma sintaxe diferente, no entanto algumas delas apresentam um comportamento em comum e são agrupadas no grupo condicional de regras at. Que apresentam regras aninhadas e indicam uma condição (escolher um caminho diferente) para ser aplicada.

* `@media`;
* `@document`;
* `@supports`;