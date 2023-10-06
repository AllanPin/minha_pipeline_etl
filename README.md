# minha_pipeline_etl
## Projeto inspirado pelo Venilton da DIO em sua aula sobre o pipe do Santander DevWeek.

Como eu já tinha estourado o meu limite de tokens da OpenAI de outros carnavais, resolvi trazer uma proposta diferente, porém mantendo a essência: um **pipeline ETL**.

A proposta é simples:

- extraímos os dados da API Keras;
- transformamos os dados, salvando-os como uma database SQL;
- carregamos os dados, sempre que precisarmos, em um DataFrame do pandas.

Com isso, nós conseguimos rapidamente ter os nossos dados prontos para serem utilizados pelo nosso hipotético modelo de deep learning.

Peço desculpas por ter me desviado da proposta inicial do projeto, que tinha como pano de fundo um serviço bancário. Mas, realmente ficaria inviável pagar por mais tokens da OpenAI para tornar fazer o projeto inicial.
