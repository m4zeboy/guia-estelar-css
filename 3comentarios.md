# Comentários em CSS

* É uma marcação no seu código que não irá afetar o código.
* É muito útil para:
    * Explicar algum bloco de código;
    * Dividir o código em seções;
    * Lembrar de alguma funcionalidade;
    * Dicas de leitura para você e para eventuais outras pessoas que lerem o teu código.

**Importante** Nunca esqueça de fechar um comentário.

## Exemplo de comentário em CSS

Comentários começam com ```/*``` e terminam com ```*/```.

```css
    /* Isso é um comentário. Não será lido como código pelo navegador.*/

    /* Reset */
    * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }

    /* Titles */
    h1,h2,h3 {
        color: #02e52b;
    }

```
Comentários também servem para desabilitar blocos de códigos.