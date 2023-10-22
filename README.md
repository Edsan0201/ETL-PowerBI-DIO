# ETL-PowerBI-DIO

Entrega do desafio "Processando e Transformando Dados com Power BI" da DIO, onde foram seguidas as seguintes etapas:

1- Criação de uma instância na Azure para MySQL, além de crição de Banco de dados com base disponível no github e integração do Power BI com MySQL no Azure.
2- Transformação dos dados conforme segue:

- Alterado o tipo de dado da coluna "salary" da tabela "Employee" para decimal fixo;
- Alterado o tipo de dado da coluna "dnumber" da tabela "Department" para número inteiro;
- Alterado o tipo de dado da coluna "dnumber" da tabela "Dept_locations" para número inteiro;
- Alterado o tipo de dado da coluna "hours" da tabela "Works_on" para número decimal;
- Coluna "Mgr_ssn" tabela "Department" alterada para "Super_ssn" 

3- Número de horas dos projetos foi demonstrado no relatório;
4- Separação de colunas complexas- Separado endereço do "Employee" em "number", "state", "city" e "FU";
5- Mesclagem de "Employee" e "Departament" em "Employee".
6- Exclusão de colunas desnecessárias;
7- Junção dos colaboradores e respectivos nomes dos gerentes, realizada mesclando as tabelas no Power BI, na tabela "funcionarioxgerente";
8- Mesclagem das colunas de Nome e Sobrenome dos colaboradores na tabela "funcionarioxgerente";
9- Mesclagem de "Location" e "Department", criada a coluna "locationxdepartment" em "dept_locations"; 

OBS: Neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir, pois as tabelas são complementares e relacionadas, onde faz sentido adicionar colunas de uma na outra. 

10- Demonstrado no relatório quantos funcionários existem por gerente; 

