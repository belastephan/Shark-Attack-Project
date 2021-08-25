# projeto shark attack


A pergunta inicial do projeto tem como objetivo descobrir em que pais tem o maior numero de ataques de tubarão.

Para responder a esta pergunta foi necessário:

1) Importar a biblioteca pandas.
2) Ler o arquivo attacks.csv que tinha como enconding latin.
3) Realizar a limpeza da coluna contry atraves dos seguintes passos:

1. Remoção do ponto de interrogação das celulas desta coluna.
2. Remoção dos espaços vazios antes do inicio das palavras.
3. Colocando os dados da coluna Country em ordem crescente.
4. Consolidação das células com valores próximos (Exemplo: Ceylo e Ceylon - Sri Lanka).
5. Ao longo de todo esse processo de limpeza da base foi utilizado a string replace e conforme houve a recorrrencia de utilização da mesma utilizado biblioteca dentro de biblioteca dentros da estrutura do argumento do replace, o que otimizou a limpeza.


4) Reliazar a contagem da quantidade de opções ocorrências de ataques por país atraves da value.counts.

Chegou-se a conclusao de que o pais que mais sofre com ataques de tubarão é o USA com 2.229 registros de ocorrências.

Após esta resposta, forma levantados outros questionamentos que tem como objetivo entender o motivo pelo qual este pais é o pais recorde em ataques de tubarão.
