# Atividade 14 - Índices e Dados Educacionais
<h4>
    106. Comando SQL para criação da estrutura da tabela.
</h4>

>CREATE TABLE aluno (<br> municipio VARCHAR(100),<br> qt_matricula INT)

<H4>107. Comando SQL para criação do índice.</H2>

> CREATE INDEX index_nome <br> ON tabela (coluna1,coluna2)

<h4>108. Comando SQL para trazer a quantidade de alunos.</h4>

>SELECT COUNT(*)<br> FROM aluno


<h4>109. Nome da Cidade e da UF pesquisada.</h4>

> [!CAUTION]
> Esse exercicio varia de acordo com seu nome

 <h4>110. Quantidade de linhas da cidade pesquisada?
</h4>

>SELECT COUNT(municipio)<br> FROM alunos

<H4>111. Quantidade de alunos matriculados da cidade pesquisada?</H4>

>SELECT SUM(qt_matricula)<br> FROM aluno <br>WHERE municipio = 'Cajamar' (resposta.109)
<br>

# Atividade 15 - Índices e controle de acesso
<h4>114. O que é um índice no SQL Server?</h4>

> Índices são estruturas que agilizam as consultas aos dados <br> Índices são associados a tabelas e podem ser formados por uma ou mais colunas da tablea


<h4>115. Quantos tipos de índices o SQL Server suporta?</h4>

> O SQL suporta somente 6 tipos de indices

<h4>116. Qual é a diferença entre um índice clusterizado e um índice não 
clusterizado?</h4>

>um índice clusterizado é um índice que define a ordem física dos dados na tabela <br>índice não clusterizado é um índice que não define a ordem física dos dados na tabela

<h4>117. Quais são as desvantagens de ter muitos índices em uma tabela no 
SQL Server?</h4>

> pois tornamos os INSERT,
UPDATE e DELETE mais lentos, pois podem
ter que alterar índices.

<h4>118. O que é o controle de acesso em um banco de dados SQL Server?
</h4>

>O controle de acesso em um banco de dados SQL Server refere-se à capacidade de gerenciar quem pode acessar o banco de dados e quais ações eles podem executar.

<h4>119. Como você concede permissões a um usuário ou função no SQL 
Server?</h4>

>GRANT "permissões" <br>ON "tabela" <br>TO "usuario";




































