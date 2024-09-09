# Desafio Processo Seletivo CITi

<p align="center">
  <img src="https://github.com/waltercrastobr/P.S-Citi/blob/main/img_citi.png" alt="imagem">
</p>

## Introdução
### Contexto do Projeto
A TechSales Inc., uma empresa de tecnologia, está enfrentando dificuldades para atingir suas metas de vendas, mesmo com uma equipe dedicada e um sistema de CRM para gerenciar interações com clientes, atividades de vendas e oportunidades de negócio. O objetivo da empresa é identificar padrões e tendências para melhorar o desempenho de vendas e orientar estratégias mais eficazes. Aqui está a [proposta](https://github.com/waltercrastobr/P.S-Citi/blob/main/Desafio_Geral_-_PTA_IDFin_2024.1.pdf) de projeto detalhada.

### Problema de Negócio
A TechSales Inc. precisa entender os fatores que influenciam o sucesso nas vendas e identificar oportunidades de melhoria. A empresa busca respostas para questões como:

- Quais são os principais fatores que determinam o sucesso ou fracasso de uma oportunidade?
- Quais produtos têm maior impacto nas vendas e como otimizar o portfólio?
- Como o desempenho das equipes de vendas varia, e o que podemos aprender com as equipes de melhor desempenho?
- Quais características dos clientes estão mais associadas ao fechamento de negócios?

### Objetivos do Projeto
- Realizar uma Análise Exploratória de Dados (EDA) para identificar padrões e tendências.
- Fornecer insights sobre como melhorar a performance das vendas.
- Propor ações para otimização do portfólio de produtos e segmentação dos clientes.

### Benefícios Esperados
- Insights valiosos sobre o comportamento das vendas e o desempenho das equipes.
- Sugestões estratégicas para melhorar a taxa de conversão e maximizar o valor das vendas.
- Identificação dos principais produtos e clientes que geram maior impacto para o negócio.

## Metodologia
### Análise Exploratória de Dados (EDA)
Para realizar a Análise Exploratória de Dados, utilizamos várias bases fornecidas pela TechSales Inc.:

- [Accounts](https://github.com/waltercrastobr/P.S-Citi/blob/main/accounts.csv): Informações sobre as empresas clientes.
- [Products](https://github.com/waltercrastobr/P.S-Citi/blob/main/products.csv): Dados dos produtos vendidos.
- [Sales Pipeline](https://github.com/waltercrastobr/P.S-Citi/blob/main/sales_pipeline.csv): Pipeline de vendas com detalhes das oportunidades.
- [Sales Team](https://github.com/waltercrastobr/P.S-Citi/blob/main/sales_teams.csv): Desempenho e composição das equipes de vendas.
- [Dicionário de Dados](https://github.com/waltercrastobr/P.S-Citi/blob/main/data_dictionary.csv): Descrição das variáveis presentes nas bases.
  
Os dados foram pré-processados para eliminar duplicatas, lidar com dados nulos e normalizar as variáveis necessárias. Após essa etapa, foi gerada uma [base tratada](https://github.com/waltercrastobr/P.S-Citi/blob/main/base_final_eda.csv) para análise. Em seguida, foi realizada a criação de gráficos e tabelas comparativas para facilitar a visualização dos padrões entre os produtos mais vendidos e as oportunidades bem-sucedidas.

### Notebooks Desenvolvidos
- [ETL](https://github.com/waltercrastobr/P.S-Citi/blob/main/ETL_Desafio_PTA.ipynb): Extração, transformação e carregamento dos dados.
- [EDA](https://github.com/waltercrastobr/P.S-Citi/blob/main/EDA_Desafio_PTA.ipynb): Análise Exploratória de Dados para geração de insights.

## Resultados
Foram gerados insights importantes, incluindo:

- Identificação de fatores-chave para o sucesso das vendas, como o envolvimento dos gerentes regionais e o impacto de determinados produtos no desempenho de vendas.
- Análise do portfólio de produtos que mais contribuem para o sucesso da empresa.
- Sugestões para a segmentação de clientes baseada nas características que mais influenciam o fechamento de negócios.
  
## Conclusão
Este [relatório](https://github.com/waltercrastobr/P.S-Citi/blob/main/Apresentac%CC%A7a%CC%83o%20Case%20TechSales.pdf) contém os resultados da análise exploratória, que foram validados para fornecer recomendações práticas à TechSales Inc.. Espera-se que, com base nestes insights, a empresa possa ajustar suas estratégias de vendas para melhorar a taxa de conversão e o desempenho geral das equipes.

