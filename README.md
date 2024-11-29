# Human Activity Recognition with Smartphones

## Resumo

Os smartphones se tornaram ferramentas essenciais em nossa vida diária, não apenas para comunicação, mas também para fornecer assistência inteligente em diversas atividades. Eles combinam portabilidade, capacidade de computação e interconectividade, permitindo a execução de ferramentas e aplicativos de terceiros. Esses dispositivos vêm com recursos avançados, como câmeras, GPS, navegadores da web, e sensores embutidos, como acelerômetros e giroscópios, que aprimoram os aplicativos com base no movimento e contexto do usuário.

O banco de dados *Human Activity Recognition* foi criado a partir das gravações de 30 participantes realizando atividades diárias (ADL) enquanto carregavam um smartphone preso à cintura com sensores inerciais incorporados. O objetivo desse banco de dados é classificar essas atividades em uma das seis categorias diferentes.

Este projeto visa explorar os dados e aplicar o K-means para identificar padrões ou agrupamentos de atividades. O conjunto de dados [*Top Instagram Influencers Data (Cleaned)*](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones) foi utilizados na construção deste projeto.

## Como Executar

### *Máquina Local*
Para configurar o ambiente e executar o projeto em sua máquina local, siga as instruções abaixo:

1. **Clone o repositório:**
   ```bash
   git clone git@github.com:luanaoliveira/HAR-smartphones.git
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
No Google Colab, abra o arquivo cuhk_face_sketch_database_cufs.ipynb, localizado na raiz do repositório.

2. Carregamento do conjunto de dados:
Faça o upload do arquivo top_insta_influencers_data.csv para o ambiente do Colab ou ajuste o caminho de leitura conforme necessário. O arquivo está localizado na pasta data na raiz do repositório.

3. Execução das células:
Execute as células do notebook em ordem sequencial para realizar as análises e obter os resultados.

## Tecnologias Utilizadas
  Este projeto foi desenvolvido utilizando:

   - Python - Linguagem de programação principal
   - NumPy - Biblioteca para manipulação de arrays e operações matemáticas de alto desempenho
   - Matplotlib - Visualização de dados
   - TensorFlow - Framework para construção e treinamento de modelos de aprendizado de máquina
   - Google Colab - Ambiente para execução do código de forma colaborativa, com acesso à nuvem

## Autores e Colaboradores

- [Elai Emylle Matos de Lima](https://www.linkedin.com/in/elaimatos/)
- [Luana Oliveira da Silva](https://github.com/luanaoliveira)

