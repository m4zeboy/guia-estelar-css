# Anatomia 

Nesta aula aprendemos a forma correta de como se declarar um estilo css.
A anatomia de uma marcação de estilo é composta por:

* Selector - Seletor.
* Declaration - Declaração;
* Properties - Propriedade;
* Property values - Valor da propriedade.

```css
    div {
        padding: 10px;
        background: gray;
        text-align: center;
    }
    /* 
        div - é o seletor
        abrimos os parenteses para iniciar uma declaração
        as propriedades são escritas com seus nomes e seguidas de :
        os valores vem com um pequeno espaço, e os valores em si seguidos de ;
     */
```


Aqui estamos pedindo para que o computador procure no documento html algum elemento **div** e aplique as configurações feitas dentros dos `{ }`.

* Aplicar 10px de preenchimento dentro dessa caixa;
* Alterar o fundo da caixa para a cor cinza;
* Alinhar os textos ao centro.