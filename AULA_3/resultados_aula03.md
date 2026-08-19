==================================================
ALGORITMO GENÉTICO PASSO A PASSO
==================================================

População inicial: [[0, 1, 0, 1, 1], [0, 0, 1, 1, 0], [0, 1, 0, 0, 1], [0, 1, 0, 0, 1], [1, 1, 0, 1, 1], [0, 0, 1, 0, 0]]

==================== GERAÇÃO 0 ====================

Avaliação dos indivíduos:
  [0, 1, 0, 1, 1] → x=11 → f(x)=121
  [0, 0, 1, 1, 0] → x= 6 → f(x)= 36
  [0, 1, 0, 0, 1] → x= 9 → f(x)= 81
  [0, 1, 0, 0, 1] → x= 9 → f(x)= 81
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [0, 0, 1, 0, 0] → x= 4 → f(x)= 16

 Melhor: x = 27 → f(x) = 729

==================== GERAÇÃO 1 ====================

Avaliação dos indivíduos:
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 0, 0, 1, 0] → x=18 → f(x)=324
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [0, 1, 0, 0, 1] → x= 9 → f(x)= 81
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729

 Melhor: x = 27 → f(x) = 729

==================== GERAÇÃO 2 ====================

Avaliação dos indivíduos:
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 0, 0, 1, 1] → x=19 → f(x)=361

 Melhor: x = 27 → f(x) = 729

==================== GERAÇÃO 3 ====================

Avaliação dos indivíduos:
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 0, 1] → x=25 → f(x)=625
  [1, 0, 0, 1, 0] → x=18 → f(x)=324
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729

 Melhor: x = 27 → f(x) = 729

==================== GERAÇÃO 4 ====================

Avaliação dos indivíduos:
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [0, 1, 0, 1, 0] → x=10 → f(x)=100
  [1, 0, 1, 0, 1] → x=21 → f(x)=441
  [1, 1, 1, 1, 0] → x=30 → f(x)=900
  [1, 0, 0, 0, 1] → x=17 → f(x)=289
  [1, 1, 0, 1, 1] → x=27 → f(x)=729

 Melhor: x = 30 → f(x) = 900

==================== GERAÇÃO 5 ====================

Avaliação dos indivíduos:
  [1, 1, 1, 1, 0] → x=30 → f(x)=900
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 1, 1, 1] → x=31 → f(x)=961
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 1, 1, 0] → x=30 → f(x)=900
  [1, 1, 0, 1, 1] → x=27 → f(x)=729

 Melhor: x = 31 → f(x) = 961

==================== GERAÇÃO 6 ====================

Avaliação dos indivíduos:
  [1, 1, 1, 1, 1] → x=31 → f(x)=961
  [1, 1, 1, 1, 1] → x=31 → f(x)=961
  [1, 1, 0, 1, 0] → x=26 → f(x)=676
  [1, 1, 0, 1, 0] → x=26 → f(x)=676
  [1, 1, 1, 1, 1] → x=31 → f(x)=961
  [1, 1, 0, 1, 0] → x=26 → f(x)=676

 Melhor: x = 31 → f(x) = 961

==================== GERAÇÃO 7 ====================

Avaliação dos indivíduos:
  [1, 1, 1, 1, 1] → x=31 → f(x)=961
  [1, 1, 1, 1, 0] → x=30 → f(x)=900
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 1, 0, 1, 1] → x=27 → f(x)=729
  [1, 0, 0, 1, 0] → x=18 → f(x)=324
  [0, 1, 0, 1, 0] → x=10 → f(x)=100

 Melhor: x = 31 → f(x) = 961

==================================================
RESULTADO FINAL
==================================================

Melhor indivíduo: [1, 1, 1, 1, 1]
x = 31
f(x) = 961

Ótimo global: x = 31, f(x) = 961
Erro: 0





-----

Professor, tendo em vista a sua explicacao sobre a margem de populacao, tanto quanto quanto o numero de POP como este:
POP_SIZE = 6
BITS = 5
GERACOES = 8
TAXA_MUTACAO = 0.1

se tem como entendido que, de geracao em geracao, dependendo das variveis colocadas, a solucao otima ou heuristca podem ser encontradas mais rapidamente.
e como eu perguntei durante a aula, a quantidade de taxa de mutacao tem que ser baixa e a 


RESULTADOS LAB2:

==================================================
ONEMAX - AG com 10 indivíduos, 100 gerações
==================================================
Geração   0: Melhor = 13/20, Média = 9.70
Geração  10: Melhor = 18/20, Média = 16.10
Geração  20: Melhor = 19/20, Média = 16.80
Geração  30: Melhor = 16/20, Média = 14.60
Geração  40: Melhor = 18/20, Média = 14.40
Geração  50: Melhor = 16/20, Média = 14.90
Geração  60: Melhor = 18/20, Média = 15.00
Geração  70: Melhor = 18/20, Média = 15.80
Geração  80: Melhor = 16/20, Média = 14.30
Geração  90: Melhor = 17/20, Média = 14.40

 MELHOR FITNESS: 17/20
   Ótimo = 20 (todos os bits são 1)

