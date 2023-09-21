# Processando e Transformando Dados com Power BI

O objetivo desse desafio foi obter dados por meio da conexão do Power BI com banco de dados externo e realizar transformações nos dados por meio do Power Query.

## Aprendizados

- Criar e configurar banco de dados no Google Cloud;
- Conectar o banco de dados do Google Cloud com o MySQL Workbench;
- Conectar o MySQL Workbench com o Power BI;
- Limpeza de dados e mesclagem de tabelas com Power Query;

## Resolução do desafio

Primeiramente, optei por utilizar o Google Cloud ao invés do Azure, que foi a plataforma sugerida no bootcamp. Isso foi um desafio a mais, pois não pude contar unicamente com os tutorias do curso. Após criar uma instância, criei o banco de dados por meio cloud shell. Em seguida, conectei o MySQL Workbench com o Google Cloud e executei os scripts para criar as tabelas e adicionar os valores. Em seguida, conectei o Power BI ao banco de dados.<br />

![tabelas do banco de dados criado no google cloud](https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/print-google-cloud.png)
*Tabelas no Google Cloud.*<br />

![tabelas do banco de dados no mysql workbench](https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/print-mysql.png)
*Tabelas no MySQL Workbench.*<br />

![conexão do banco da dados ao power bi](https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/print-power%20bi.png)
*Conexão do banco de dados ao Power BI.*<br /><br />

O próximo passo foi analisar os dados e aplicar modificações por meio do Power Query. Precisei alterar os tipos, mesclar e separar algumas colunas, como as que indicavam nome e sobrenome, endereço e salário. Também mesclei algumas tabelas para exibir dados relacionados entre si.

<img src="https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/mesclagem-employee-departament.png" width=480> &nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/mesclagem-employee-manager.png" width=480> <br />

<img src="https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/agrupar_employees_per_manager.png" width=480>&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/mesclagem-departament-location.png" width=480> <br /><br />

Por fim, elaborei o relatório.

<img src="https://github.com/anacarlaaf/santander-bootcamp-2023-dio/blob/main/desafio-final-power-bi/img/relatorio.png">




