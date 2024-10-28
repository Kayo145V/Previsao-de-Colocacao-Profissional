# Previsão de Colocação Profissional

Este projeto realiza uma análise preditiva sobre a empregabilidade de estudantes, utilizando um dataset que contém informações acadêmicas e profissionais. O objetivo é prever se um estudante será colocado no mercado de trabalho ("Placed" ou "Not Placed") com base em diversos fatores.


## Conteúdo do Repositório


- `Análise de Dados Campus.ipynb`: Notebook Jupyter contendo todo o código do projeto, incluindo análise exploratória dos dados, tratamento de dados ausentes, implementação dos modelos preditivos e visualizações.


- `Placement_Data_Full_Class.csv`: Dataset utilizado.


## Pré-requisitos


Antes de executar o projeto, certifique-se de que você possui os seguintes requisitos instalados:


- Python 3.x

- Bibliotecas:

  - pandas

  - numpy

  - seaborn

  - matplotlib

  - scikit-learn


Você pode instalar as bibliotecas necessárias usando o seguinte comando:

    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn

## Estrutura do Projeto

Placement_Data_Full_Class.csv: O arquivo CSV contendo os dados sobre os estudantes. O caminho padrão para o arquivo deve ser ajustado no código, conforme sua estrutura de diretórios. O código para carregar o dataset é o seguinte:

df_original = pd.read_csv("C:/Users/SeuUsuario/Downloads/Placement_Data_Full_Class.csv", sep=",")

Substitua "C:/Users/SeuUsuario/Downloads/" pelo caminho correto onde o arquivo está localizado em seu sistema.

----------------------------------------------------------------------------------------------------------------------------

### Em caso de dúvidas entre em contato com: Kayo145v@gmail.com
