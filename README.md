# Projeto Cloudboost

## Resumo do projeto
É um projeto feito com o curso do Codeboost para construir uma Landing Page, aprendendo
como o pre-compilador Sass funciona no momento da programação.

## Aprendizados

* `all: unset` podendo ser usado para remover todo o css anterior a esse comando e adicionar novos estilos;
* Podemos usar o `@mixin` como somente um objeto sem passagem por parâmetro na parte do `@include`;
* No Sass é possivel usar comandos comuns na maioria das linguagens de programação, como `@if`, `@else`,
`@for`, `@each` e `@while`;
* Também é possivel fazer declaração de funções;
* Operações booleanas, matemáticas e de string são mais fáceis de executar do que no CSS normal;
* Para fazer uma especie de array key-value, pode usar uma váriavel padrão do Sass e fazer uma lista, por exemplo:
```Sass
$breakpoints: (
    'laptop': 1200px,
    'tablet': 991px,
    'mobile': 560px
);
```
* Também é possivel fazer uma busca dentro desse array como se fosse um indexOf ou array.map().

## Problemas idenficados do curso

* Não aborda a variedade de funções que o Sass apresenta por ter uma similaridade 
com outras linguagens de programação em sua sintaxe, como o for, foreach, função com passagem
por parâmetro com valor default, com uma lista e entre outros.