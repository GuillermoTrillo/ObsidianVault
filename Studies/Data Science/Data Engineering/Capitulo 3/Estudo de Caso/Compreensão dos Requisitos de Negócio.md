Coisas a fazer:

- Compreender o problema:
	A empresa tem máquinas que fazem diversos processos, e essas máquinas tem dados tanto do seu estado atual quanto dos processos que ela faz.
- Compreender o que deve ser entregue:
	Extrair dados das máquinas, separar esses dados entre dados relacionados ao estoque e dados relacionados ao estado da máquina.
- Pesquisamos a(s) fonte(s) de dados:
	As máquinas são a fonte retornando tudo em TXT.
- identificamos a infraestrutura atual e o que será necessário:
	A infraestrutura atual está tanto em servidores locais quanto na AWS. Poderiamos fazer os processos principais pelos servidores locais e entregar o resultado aos servidores da AWS, para facilitar seu acesso.
- Desenhamos um esboço da solução:


										\/-> processamento do produto -> \
 Maquina -> Divisao entre produto/estado da maquina                                            Servidores AWS
										 \\ -> processamento do estado       -> /
*(minha ideia)*

Isso é em BATCH, e não streaming.