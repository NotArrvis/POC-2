# POC ARRAYS 

Este projeto é uma Prova de Conceito (POC) desenvolvida em HTML e JavaScript, que demonstra como funcionam diferentes métodos aplicados em arrays. O código explora os seguintes métodos:

    sort(): Ordena os elementos de um array.
    map(): Aplica uma função a cada elemento do array e retorna um novo array.
    reduce(): Reduz o array a um único valor, aplicando uma função de acumulação.
    filter(): Filtra os elementos do array com base em uma condição específica.
    Operador spread: Combina ou expande arrays.

Funcionalidade

A página contém botões que, ao serem clicados, executam diferentes operações em dois arrays: um de números e outro de palavras. Para cada operação, o resultado é exibido na tela.
Estrutura HTML e CSS

    HTML:
        A estrutura HTML é composta por várias seções (div) que representam cada operação (Sort, Map, Reduce, Filter, Spread).
        Cada uma dessas seções possui um botão que aciona a função JavaScript correspondente.
        Os resultados das operações são exibidos em blocos de texto <pre>, que preservam a formatação.

    CSS:
        O estilo da página define a aparência de cada componente (títulos, botões, etc.).
        O botão muda de cor quando o usuário passa o mouse sobre ele.
        O código usa uma paleta de cores suaves e um layout simples, centrado no conteúdo.

Operações Demonstradas

    Sort (Ordenação):
        Clicando no botão Sort, os arrays de números e de palavras são ordenados.
        Os números são classificados em ordem crescente, e as palavras em ordem alfabética.

    Map (Mapeamento):
        O botão Map aplica uma função que eleva ao quadrado cada número do array de números.
        O resultado é exibido com os números elevados ao quadrado.

    Reduce (Redução):
        O botão Reduce soma todos os números do array, utilizando o método reduce().
        O resultado é a soma total dos números.

    Filter (Filtragem):
        O botão Filter filtra os números pares do array original.
        Somente os números pares são exibidos.

    Spread (Espalhamento):
        O botão Spread combina os dois arrays (de números e de palavras) em um único array, utilizando o operador spread.
        O array combinado é exibido na tela.

Funções JavaScript

Cada botão na interface está vinculado a uma função JavaScript que realiza as operações desejadas. As funções são:

    demonstrarSort(): Ordena os arrays.
    demonstraMap(): Aplica o map() para elevar os números ao quadrado.
    demonstrarReduce(): Usa reduce() para calcular a soma dos números.
    demonstrarFilter(): Filtra números pares com filter().
    demonstrarSpread(): Combina os arrays usando o operador spread.

Como Usar

    Abra o arquivo index.html no navegador.
    Explore as operações clicando nos botões correspondentes.
    O resultado de cada operação será exibido abaixo de cada botão.

Requisitos

    Um navegador moderno que suporte JavaScript ES6.

Conclusão

Este projeto simples ilustra de maneira prática alguns dos métodos mais úteis para manipulação de arrays no JavaScript, servindo como um guia para quem deseja entender melhor o funcionamento dessas operações básicas.
