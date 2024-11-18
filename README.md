# Insta Data Science: Análise de Engajamento no Instagram

## Resumo

Para estabelecer e manter proximidade com o seu público, nada é mais eficaz do que o engajamento no Instagram. O engajamento avalia como sua audiência interage com suas publicações e perfil, sendo uma métrica que leva em consideração curtidas, comentários, compartilhamentos, visualizações, aumento no número de seguidores, posts salvos, entre outros.

O *Top Instagram Accounts Dataset* é uma coleção de 200 linhas de dados que oferece insights valiosos sobre as contas mais populares do Instagram em diversas categorias. O conjunto de dados inclui várias colunas que fornecem informações abrangentes sobre o desempenho de cada conta, taxa de engajamento e tamanho do público.

Este projeto visa criar uma aplicação para analisar as variáveis relacionadas a interação das contas do Instagram, tendo como variável alvo, a taxa de engajamento, ou "60_day_eng_rate". Essa métrica calcula a taxa de engajamento de uma conta dividindo o número total de curtidas e comentários recebidos pelo número total de seguidores, expresso em porcentagem. 

O conjunto de dados [*Top Instagram Influencers Data (Cleaned)*](https://www.kaggle.com/datasets/surajjha101/top-instagram-influencers-data-cleaned/data) foi utilizados na construção deste projeto.

## Como Executar

### *Máquina Local*
Para configurar o ambiente e executar o projeto em sua máquina local, siga as instruções abaixo:

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
4. Execute o projeto:
Após a configuração, siga as instruções contidas no notebook ou nos scripts disponíveis para realizar as análises.

### *Google Colab*
Para executar o projeto diretamente no Google Colab, siga as etapas abaixo:

1. Abertura do notebook: 
No Google Colab, abra o arquivo top_insta_influencers_data.ipynb, localizado na raiz do repositório.

2. Carregamento do conjunto de dados:
Faça o upload do arquivo top_insta_influencers_data.csv para o ambiente do Colab ou ajuste o caminho de leitura conforme necessário. O arquivo está localizado na pasta data na raiz do repositório.

3. Execução das células:
Execute as células do notebook em ordem sequencial para realizar as análises e obter os resultados.

## Estrutura dos Arquivos
  O repositório é organizado da seguinte forma:
   ```bash
    /data
     top_instagram_accounts.csv                    # Dados utilizados no projeto
   .gitignore                                      # Arquivos e diretórios ignorados pelo Git
   LICENSE                                         # Licença do projeto
   README.md                                       # Documentação do projeto
   Relatório Técnico - Regressão Linear.docx.pdf   # Relatório técnico detalhado
   requirements.txt                                # Dependências do projeto (para ambientes locais)
   Insta_Data_Science.ipynb                        # Notebook principal desenvolvido no Google Colab

  ```

## Tecnologias Utilizadas
  Este projeto foi desenvolvido utilizando:

  - Python - Linguagem de programação principal
  - Pandas - Manipulação e análise de dados
  - Matplotlib e Seaborn - Visualização de dados
  - Sklearn - Sklearn (Scikit-learn) - Implementação de algoritmos de aprendizado de máquina, como modelos de regressão e avaliação de métricas.
  - Google Colab - Ambiente para execução do código de forma colaborativa, com acesso à nuvem.

## Autores e Colaboradores

[Elai Emylle Matos de Lima](https://www.linkedin.com/in/elaimatos/)
  - Coleta e preparação de dados
  - Análise inicial
  - Documentação e estruturação do projeto

[Luana Oliveira da Silva](https://github.com/luanaoliveira)
  - Coleta e preparação de dados
  - Desenvolvimento de modelos de engajamento
  - Documentação e estruturação do projeto
