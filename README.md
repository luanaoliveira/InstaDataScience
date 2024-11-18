# Insta Data Science: Análise de Engajamento no Instagram

## Resumo

Para estabelecer e manter proximidade com o seu público, nada é mais eficaz do que o engajamento no Instagram. O engajamento avalia como sua audiência interage com suas publicações e perfil, sendo uma métrica que leva em consideração curtidas, comentários, compartilhamentos, visualizações, aumento no número de seguidores, posts salvos, entre outros.

O *Top Instagram Accounts Dataset* é uma coleção de 200 linhas de dados que oferece insights valiosos sobre as contas mais populares do Instagram em diversas categorias. O conjunto de dados inclui várias colunas que fornecem informações abrangentes sobre o desempenho de cada conta, taxa de engajamento e tamanho do público.

Este projeto visa criar uma aplicação para analisar as variáveis relacionadas a interação das contas do Instagram, tendo como variável alvo, a taxa de engajamento, ou "60_day_eng_rate". Essa métrica calcula a taxa de engajamento de uma conta dividindo o número total de curtidas e comentários recebidos pelo número total de seguidores, expresso em porcentagem. 

O conjunto de dados [*Top Instagram Influencers Data (Cleaned)*](https://www.kaggle.com/datasets/surajjha101/top-instagram-influencers-data-cleaned/data) foi utilizados na construção deste projeto.

## Instalação
Para configurar o ambiente e executar o projeto, siga as instruções abaixo:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/luanaoliveira/insta-data-science.git
   cd insta-data-science
   ```
2. **Crie e ative um ambiente virtual (opcional):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```
3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

## Como Executar
  1. No Google Colab, abra o arquivo Insta_Data_Science.ipynb localizado na raiz do repositório.
  2. Faça o upload do conjunto de dados top_instagram_accounts.csv no ambiente do Colab ou ajuste o caminho para leitura, conforme necessário.
  3. Execute as células do notebook sequencialmente para realizar as análises e gerar os resultados.

## Estrutura dos Arquivos
  O repositório é organizado da seguinte forma:
   ```bash
    top_instagram_accounts.csv      # Dados utilizados no projeto
    Insta_Data_Science.ipynb        # Notebook principal desenvolvido no Google Colab
    README.md                       # Documentação do projeto
    requirements.txt                # Dependências do projeto (para ambientes locais)

  ```

## Tecnologias Utilizadas
  Este projeto foi desenvolvido utilizando:

  - Python - Linguagem de programação principal
  - Pandas - Manipulação e análise de dados
  - Matplotlib e Seaborn - Visualização de dados
  - Google Colab - Ambiente para execução do código

## Autores e Colaboradores

[Elai Emylle Matos de Lima](https://www.linkedin.com/in/elaimatos/)
  - Coleta e preparação de dados
  - Análise inicial
  - Documentação e estruturação do projeto

[Luana Oliveira da Silva](https://github.com/luanaoliveira)
  - Coleta e preparação de dados
  - Desenvolvimento de modelos de engajamento
  - Documentação e estruturação do projeto
