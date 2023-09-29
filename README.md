# processando-dados-powerbi

# Desafio da DIO - Processando e Transformando Dados no Power BI

Este projeto desafiador oferecido pela DIO (Digital Innovation One) aborda o aprendizado fundamental do processo de extração e transformação de dados utilizando o Power BI em conjunto com um Banco de Dados SQL. Além disso, exploramos o uso da plataforma Azure para acessar um banco de dados MySQL. 

## Relatório

Aqui estão as etapas-chave realizadas durante este projeto:

1. **Modificação dos Valores Monetários para Double Preciso (Coluna Salary):** Foi necessário converter os valores monetários presentes na coluna "Salary" para o tipo de dado "double preciso".

2. **Separação de Colunas Complexas (Address):** Na tabela "employee", as informações complexas de endereço foram divididas utilizando um delimitador, resultando em novas colunas para CEP, cidade, estado e unidade federativa.

3. **Mescla das Tabelas Employee e Department:** Uma nova tabela foi criada, combinando as informações de colaboradores e seus respectivos departamentos. Foram eliminadas as colunas desnecessárias para simplificar a visualização.

4. **Junção de Colaboradores e Gerentes:** Utilizando a tabela "employee", organizamos os nomes dos colaboradores e seus respectivos gerentes. As colunas contendo nomes foram mescladas para uma visualização mais organizada.

5. **Mescla das Tabelas Department e Dept_Locations:** Para uma melhor visualização, mesclamos as informações dos departamentos e suas respectivas localizações a partir da tabela "dept_locations".

6. **Agrupamento de Dados para Visualização de Quantidade de Colaboradores por Gerente:** Foi realizada uma operação de agrupamento de dados para visualizar quantos colaboradores estão sob a supervisão de cada gerente.

## Por que Usar Mesclar em Vez de Atribuir?

Mesclar resulta em combinar as tabelas com base em colunas comuns, criando uma nova tabela com as colunas das tabelas originais, agregando as informações desejadas sem repetições. Por outro lado, atribuir apenas empilha as tabelas desejadas uma sobre a outra, o que não seria o ideal para este projeto, uma vez que queremos combinar e relacionar os dados de maneira eficaz.

