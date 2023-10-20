# Processamento e Transformação de Dados

Este Desafio foi elaborado um processamento de dados utilizando a ferramanta Power BI em conjunto com Banco de dados MySQl.
O processo envolve a criação de Banco de Dados com base no conjunto disponivel no GitHub e a integração com PowerBI com o MySQL e o tratamentod desses dados.


## Diretrizes para transformação dos dados

1. Verifique os cabeçalhos e tipos de dados
2. Modifique os valores monetários para o tipo double preciso
3. Verifique a existência dos nulos e analise a remoção
4. O employyes com nulos em Super_ssn podem ser gerentes. Verifique se há algum colaborador sem gerente
5. Verifique se há algum departamento sem gerente
6. Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
7. Verifique o número de horas dos projetos
8. Separar colunas complexas
9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção.
10. Neste processo elimine as colunas desnecessárias.
11. Realize a junção dos colaboradores e respectivos nomes dos gerentes. Isso pode ser feito com consulta SQL ou pela mescla da tabela com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nome dos colaboradores.
13. Mescle os nome dos departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
14. Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.
15. Agrupe os dados a fim de saber quantos colaboradores existem por gerente.
16. Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela


## Pergunta e Respostas
1. Por que Utilizar mesclar consultas e não combinar consultas nos casos supracitados?
- Mesclar consultas serve para o momento em que desejamos apenas unir as colunas entre tabelas, ou seja, trabalhando de formar colunar e combinar consulta está em unificar apenas as linhas entre as tabelas.


## Tecnologias Utilizandas no Projeto.

- Power BI: Ferramente de analise e visualização de dados por meio desta para fazer a transformação e limpeza dos dados necessários.
- MySQL: Sistema de gerenciamento de banco de dados, usado para interface com linguagem SQL



 #FogueteNãoTemRé 🚀
