# Desafio Gupy

1) Observe o trecho de código abaixo:

```

int INDICE = 13, SOMA = 0, K = 0;

enquanto K < INDICE faça

{

K = K + 1;

SOMA = SOMA + K;

}

imprimir(SOMA);


```
Ao final do processamento, qual será o valor da variável SOMA?

[Resposta da questão 1](https://github.com/Ceds0508/testegupy/blob/main/Ceds/SomaSimples/SomaSimples.java) =  91 


2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.
[Resposta da Questão 2](https://github.com/Ceds0508/testegupy/blob/main/Ceds/Fibonacci/Fibonacci.java)

3) Descubra a lógica e complete o próximo elemento:


a) 1, 3, 5, 7, <strong><code>9</code></strong>

b) 2, 4, 8, 16, 32, 64,  <strong><code>128</code></strong>

c) 0, 1, 4, 9, 16, 25, 36, <strong><code>49</code></strong>

d) 4, 16, 36, 64, <strong><code>100</code></strong>

e) 1, 1, 2, 3, 5, 8,<strong><code>13</code></strong>

f) 2,10, 12, 16, 17, 18, 19, <strong><code>20</code></strong>


4) Você está em uma sala com três interruptores, cada um conectado a uma lâmpada em uma sala diferente. Você não pode ver as lâmpadas da sala em que está, mas pode ligar e desligar os interruptores quantas vezes quiser. Seu objetivo é descobrir qual interruptor controla qual lâmpada.

Como você faria para descobrir, usando apenas duas idas até uma das salas das lâmpadas, qual interruptor controla cada lâmpada?

```
Aqui está uma solução para o problema:

1. Primeira visita:
   - Ligue o primeiro interruptor e o deixe ligado por alguns minutos.
   - Depois, desligue-o e ligue o segundo interruptor.
   - Deixe o segundo interruptor ligado e visite a primeira sala.

   Agora, temos três situações possíveis:

   a) Se a lâmpada estiver acesa, então o primeiro interruptor controla essa lâmpada.
   
   b) Se a lâmpada estiver desligada e fria, então o segundo interruptor controla essa lâmpada.
   
   c) Se a lâmpada estiver desligada, mas ainda estiver quente, então o terceiro interruptor controla essa lâmpada.

2. Segunda visita:
   - Ligue o interruptor que você identificou na primeira etapa (ou seja, o interruptor que você acredita controlar a primeira lâmpada).
   - Deixe-o ligado e visite a segunda sala.

   Agora, observe a lâmpada na segunda sala:

   - Se estiver acesa, o interruptor que você ligou na segunda visita controla essa lâmpada.
   - Se estiver desligada e fria, o interruptor que você não tocou em nenhuma das visitas controla essa lâmpada.

Dessa forma, com apenas duas idas até uma das salas das lâmpadas, você pode determinar qual interruptor controla cada uma das lâmpadas.


Sim, usei chat gpt para responder essa
```

5) Escreva um programa que inverta os caracteres de um string.


IMPORTANTE:

a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;

b) Evite usar funções prontas, como, por exemplo, reverse;

[Resposta questão 5](https://github.com/Ceds0508/testegupy/blob/main/Ceds/InverteString/InverteString.java)

