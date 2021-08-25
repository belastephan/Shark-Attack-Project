# projeto shark attack


A pergunta inicial do projeto tem como objetivo descobrir em que pais tem o maior numero de ataques de tubar�o.

Para responder a esta pergunta foi necess�rio:

1) Importar a biblioteca pandas.
2) Ler o arquivo attacks.csv que tinha como enconding latin.
3) Realizar a limpeza da coluna contry atraves dos seguintes passos:

1. Remo��o do ponto de interroga��o das celulas desta coluna.
2. Remo��o dos espa�os vazios antes do inicio das palavras.
3. Colocando os dados da coluna Country em ordem crescente.
4. Consolida��o das c�lulas com valores pr�ximos (Exemplo: Ceylo e Ceylon - Sri Lanka).
5. Ao longo de todo esse processo de limpeza da base foi utilizado a string replace e conforme houve a recorrrencia de utiliza��o da mesma utilizado biblioteca dentro de biblioteca dentros da estrutura do argumento do replace, o que otimizou a limpeza.


4) Reliazar a contagem da quantidade de op��es ocorr�ncias de ataques por pa�s atraves da value.counts.

Chegou-se a conclusao de que o pais que mais sofre com ataques de tubar�o � o USA com 2.229 registros de ocorr�ncias.

Ap�s esta resposta, forma levantados outros questionamentos que tem como objetivo entender o motivo pelo qual este pais � o pais recorde em ataques de tubar�o.
