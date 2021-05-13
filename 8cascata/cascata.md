# Cascata (C do css, cascading)

É uma escolha que o browser faz para aplicar os estilos caso haja muitas regras.

* Os estilos são lidos de cima para baixo;

Para que o browser faça essa escolha, ele leva em consideração 3 critérios:

* Origem do estilo;
* Especificidade;
* Importância.

## Origem do estilo

inline > tag style > link:css

* O estilo inline é o mais forte, as outras definições de estilo serão ignoradas perante a ele.
* A tag style é a segunda mais forte, quando não há estilos inline, a tag style prevalecerá. E se houver duas tags style, a última  prevalecerá sobre a primeira.
* o link:css não é o mais forte mas é o mais recomendado, as definições são lidas de cima para baixo (como todas) onde a última regra será a mais forte. Se houver vários links, o último será o mais forte.

## Especificidade

Para que não haja confusão na hora de aplicar os estilos, o navegador realiza um cálculo que verifica qual é a força da especificidade de uma regra. Logo a mais forte será aplicada.

* 0pt - Seletor universal (*), combinators e pseudo classes de negação (:not).
* 1pt - Seletor de elemento e pseudo elementos.
* 10pt - Classes e atributos.
* 100pt - ID.
* 1000pt - inline style.