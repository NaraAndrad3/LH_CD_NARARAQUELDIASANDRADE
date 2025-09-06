## Hollywood Film Success Analysis - PProductions

Este repositório contém um projeto completo de ciência de dados realizado para a PProductions, um estúdio de Hollywood. O objetivo da análise é utilizar um banco de dados de filmes para identificar os principais fatores de sucesso (como aclamação da crítica e faturamento) e fornecer uma recomendação estratégica para a produção de seu próximo filme.


## Conteúdo do Repositório
O repositório está organizado para facilitar a compreensão e a reprodução da análise:

- README.md: Este arquivo, que fornece uma visão geral do projeto.

- requirements.txt: Um arquivo que lista todas as bibliotecas Python necessárias e suas versões.

- analise_cinematografica.ipynb: O notebook principal que documenta todas as etapas do projeto, incluindo:

  -- Análise Exploratória de Dados (EDA) e limpeza.

  -- Análise estatística e visualizações.

  -- Respostas para as perguntas de negócio do estúdio.

  --  Implementação do modelo de machine learning para previsão de notas.

- modelo_imdb_rating.pkl: O modelo de regressão Random Forest treinado, salvo no formato .pkl.

## Como instalar e executar o projeto:

- Primeiro, clone este repositório com o comando:
- 
`git clone https://github.com/NaraAndrad3/LH_CD_NARARAQUELDIASANDRADE.git`

- Crie um ambiente virtual:
- 
  `python -m venv venv`

-Acesse o ambiente virtual criado:

`source venv/bin/activate`

- Instale as dependências listas no arquivo requiremets.txt
  `pip install -r requirements.txt`

- Execute o jupyter notebook:

`jupyter notebook`

## Principais Descobertas e Análises
As análises realizadas revelaram diversos insights valiosos para o estúdio:

- Duração e Qualidade: Filmes mais longos tendem a ter notas IMDB mais altas.

- Popularidade e Qualidade: Existe uma forte correlação positiva entre o número de votos de um filme e sua nota. Filmes que geram grande engajamento tendem a ser bem avaliados.

- Fatores de Faturamento: A nota IMDB tem uma correlação positiva, porém fraca, com o faturamento. Outros fatores como gênero e o talento principal (atores e diretores) são mais determinantes para o sucesso financeiro.

- Análise de Talento: A análise mostrou que atores como Tom Hanks são apostas seguras, pois seus filmes consistentemente entregam alta nota e alto faturamento.


## Previsão Final
Um modelo de regressão Random Forest foi desenvolvido para prever a nota IMDB de um filme com base em suas características. O modelo alcançou um erro médio (RMSE) de 0.21 pontos, demonstrando boa performace e alta precisão.

Com base neste modelo, a nota prevista para o filme "The Shawshank Redemption" é de 9.28.

## Conclusão
Este projeto demonstra como a análise de dados e a modelagem preditiva podem ser aplicadas para informar decisões estratégicas de negócio, transformando dados brutos em uma vantagem competitiva para o estúdio PProductions.

