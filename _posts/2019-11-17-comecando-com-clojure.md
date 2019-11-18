---
layout: post
title: Começando com Clojure
tags: [funcional, clojure]
---
<h2>O início</h2>

<p>
Clojure possui uma sintaxe muito simples, porém que pode confundir muito <s>(me confundiu muito)</s> quem está começando no mundo de linguagens que são baseadas em Lisp. 
</p>


<p><code>(operador operando1 operando2... operando)</code></p>

<p>
Não entendeu? Então vamos para um exemplo. Suponhamos que você deseja realizar uma soma entre 5 números. </p>

<p>O que em Javascript poderíamos fazer assim:</p>
<code>let resultado = 3 + 7 + 8;</code>

<p>Em Clojure fazemos assim: </p>
<p><code >(+ 3 7 8)</code></p>

<p>
No código acima o operador "+" soma os parâmetros 3, 7 e 8.
</p>

<p>Um outro exemplo utilizando o famoso Hello World, onde a <i>string</i> "Hello World" é passada como parâmetro para a função println: </p>

<p><code>(println "Hello World")</code></p>
<br/>
<h2>Nomeando valores</h2>

<p>Usa-se a instrução <b>def</b> para vincular o nome do símbolo a um valor. Exemplos: </p>

<p><code>(def texto "Iniciando com Clojure")</code></p>
<p><code>(def contas-pagas 100)</code></p>

<p>Imprimindo os valores definidos: </p>
<p><code>(println texto)</code></p>
<p><code>(println "Quantidade de contas pagas:"  contas-pagas)</code></p>

<br/>
<h2>Estruturas de dados</h2>

<p>Em Clojure todas as estruturas de dados são imutáveis, ou seja, seus valores não podem ser alterados. 

<h3>Números básicos</h3>

<p>Em Clojure podemos definir três tipos básicos de números, sendo eles Integer, Float ou fracionados. Exemplo: 

<p><code>(def numero-inteiro 10)</code><p>
<p><code>(def numero-ponto-flutuante 3.5)</code><p>
<p><code>(def numero-fracionado 10/3)</code><p>

<h3>Strings</h3>

<p>Strings representam textos, assim como em outras linguagens de programação.</p>

(def hobbit "Bilbo")