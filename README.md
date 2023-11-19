# Estudo Prova - P2
nesse documento contem o gabarito dos teste e a resolução da atividade 15. 

## Gabarito Teste

<h3>
  114.Em uma situação hipotética, ao ser designada para atender aos requisitos 
de negócio de um usuário, uma Analista de Sistemas do TRE-SP escreveu 
expressões e comandos para serem executados em um Banco de Dados Relacional 
que visavam<br>(1) criar uma tabela que contivesse dados de processos 
partidários <br>(2) controlar a segurança e o acesso a ela<br>(3) manipular dados
nela. <br> Desta forma ela, se valeu, correta e respectivamente, por exemplo, de 
alguns elementos de expressões tais como:
</h3>
<P>
  (A) INSERT, REVOKE e SELECT.<br> 
(B) CREATE, REVOKE e INSERT.<br> 
(C) CREATE, GRANT e ALTER.<br> 
(D) DROP, ALTER e UPDATE.<br> 
(E) INSERT, INDEX e CREATE.<br>
</P>
<strong>
  Gabarito: B
</strong>

<h3>
  115. A linguagem SQL possui comandos de DDL e DML. As construções da linguagem 
utilizadas para especificar concessão e revogação de privilégios são, 
respectivamente.
</h3>
<P>
  (A) SET e DENY.
(B) GRANT e REVOKE. 
(C) INSERT e REMOVE. 
(D) INSERT e UPDATE. 
(E) ATTACH e DETACH.
</P>
<strong>
  Gabarito: B
</strong>
<h3>
  116. Após constatar que todos os dados em uma tabela estavam incorretos, foi
solicitado ao Técnico em Informática para limpar os registros desta tabela 
mantendo sua estrutura, para que os dados corretos fossem posteriormente 
inseridos. Para realizar este trabalho o Técnico terá que utilizar a 
instrução SQL 
</h3>
<P>
  (A) DROP TABLE table_name.
(B) REDO * FROM table_name. 
(C) DELETE TABLE table_name. 
(D) ERASE * FROM table_name.
(E) TRUNCATE TABLE table_name.
</P>
<strong>
  Gabarito: E
</strong>

<h3>
  117.No que concerne à linguagem SQL, julgue o item seguinte.
Ao se criar uma view, não é necessário que os nomes dos atributos da view 
sejam os mesmos dos atributos da tabela.
</h3>
<P>
  (C) Certo
(E) Errado
</P>
<strong>
  Gabarito: C
</strong>

<h3>
  118.Para que um usuário possa executar o comando select em uma view, não é 
necessário que ele tenha esse privilégio diretamente na view, mas apenas na 
tabela a que a view faz referência.
</h3>
<P>
  (C) Certo
(E) Errado
</P>
<strong>
  Gabarito: E
</strong>

<h3>
  119.Qual conceito é uma coleção de comandos em SQL para otimização de Banco 
de dados e que encapsula tarefas repetitivas, aceita parâmetros de entrada 
e retorna um valor de status (para indicar aceitação ou falha na execução)?
</h3>
<P>
  (A) Campos.
(B) Índices.
(C) Registros.
(D) Triggers.
(E) Stored Procedures.
</P>
<strong>
  Gabarito: E
</strong>

<h3>
  120. Sobre as estruturas de banco de dados, analise as afirmativas abaixo:
I. Trigger define uma estrutura, que dispara mediante alguma ação, como 
inserção, exclusão e atualização de dados.
II. Uma trigger não precisa estar associada a uma tabela.
III. Stored Procedure corresponde a um conjunto de comandos em SQL, que podem 
ser executados de uma só vez, a partir de sua chamada.
IV. Stored Procedure não aceita parâmetros de entrada.
Estão CORRETAS
</h3>
<P>
  
(A) I e II. 
(B) I e III. 
(C) I e IV 
(D) II e IV. 
(E) II e III.
</P>
<strong>
  Gabarito: B
</strong>









121. Um dos mecanismos de segurança em um sistema de banco de dados é o 
subsistema de autorização, que permite a usuários que têm privilégios 
específicos concederem de forma seletiva e dinâmica esses privilégios a 
outros usuários e, subsequentemente, revogarem esses privilégios, se 
desejarem. Os comandos SQL que permitem a um usuário conceder privilégios a 
outros usuários e revogar privilégios concedidos a outros usuários são, 
respectivamente:
(A) INSERT PRIVILEGES e DELETE PRIVILEGES. 
(B) CREATE ROLE e DROP ROLE.
(C) CONCEDE e EXCLUDE. 
(D) GRANT e REVOKE.
(E) ALLOW e DISALLOW.
Gabarito: D
122.Com relação aos bancos de dados, os índices são uma das técnicas mais 
utilizadas na otimização de desempenho de consultas SQL.
A respeito dos índices, assinale V para a afirmativa verdadeira e F para a 
falsa.
(...) Os índices provavelmente serão utilizados quando uma coluna indexada 
aparecer nos critérios de busca de uma cláusula WHERE ou HAVING.
(...) Os índices provavelmente serão utilizados quando uma coluna indexada 
aparecer em uma cláusula GROUP BY e ORDER BY.
(...) Os índices provavelmente serão utilizados quando a seletividade dos 
dados de uma coluna indexada for baixa.
As afirmativas são, respectivamente, 
(A) F, V e F.
(B) V, V e F.
(C) V, F e F.
(D) V, F e V. 
(E) F, F e V.
Gabarito: B.
123. A respeito de sistemas gerenciadores de banco de dados (SGBD), julgue 
os próximos itens.
O comando GRANT é utilizado para conceder privilégios em um objeto do SGBD, 
ao passo que o comando REVOKE serve para cancelar um privilégio já concedido.
(C) Certo
(E) Errado
Gabarito: C
124. A linguagem de manipulação de dados (DML – data definition language) é 
usada para, entre outras finalidades, criar e alterar estruturas de tabelas 
em um SGBD.
(C) Certo
(E) Errado
Gabarito: E
125. Na linguagem SQL, o comando create table é usado para criar uma tabela 
no banco de dados; enquanto o relacionamento entre duas tabelas pode ser 
criado pela declaração
(A) null.
(B) primary key.
(C) constraint.
(D) auto_increment. 
(E) not null.
Gabarito: C
126. Em SQL, para alterar a estrutura de uma tabela do banco de dados e 
incluir nela uma nova foreign key, é correto utilizar o comando
(A) convert.
(B) group by. 
(C) alter table. 
(D) update.
(E) insert.
Gabarito: C
127. O administrador de um banco de dados deseja remover do usuário RH5678 
o privilégio de excluir linhas da tabela RH05_FUNCIONARIO.
Qual comando SQL executará o que esse administrador deseja?
(A) REVOKE DELETE ON RH05_FUNCIONARIO FROM RH5678
(B) PURGE DELETE FROM RH5678 ON RH05_FUNCIONARIO
(C) DROP DELETE ON RH05_FUNCIONARIO FROM USER RH5678
(D) DROP FUNCTION DELETE ON RH05_FUNCIONARIO FROM RH5678 
(E) DELETE FUNCTION DELETE FROM RH5678 ON RH05_FUNCIONARIO
Gabarito: A
<h3>
  
</h3>
<P>
  
</P>
<strong>
  
</strong>
