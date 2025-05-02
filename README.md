# analise-dados-vacinacao-vestibular
EBAC_Mod04_Tarefa_aula_03_a_05_(base) (1)

# Análise de Dados de Vacinação e Vestibular

Este repositório contém notebooks Jupyter e arquivos de dados relacionados a duas análises distintas:

1.  **Análise de Dados de Vacinação (BS2 e Vacinação II):** Exploração e manipulação de dados de vacinação para responder a perguntas específicas sobre a aplicação de vacinas, especialmente em relação a menores de 18 anos e os estabelecimentos de saúde envolvidos.

2.  **Análise de Dados de Vestibular (Vestibular II):** Processamento de dados de um vestibular para identificar alunos desqualificados com base em critérios de nota zero em matérias específicas e para determinar os alunos aprovados para a segunda fase.

## Conteúdo do Repositório

* `dados_vestibular.csv` (ou similar): Arquivo contendo os dados dos candidatos ao vestibular (usado em "Vestibular II").
* `dados_vacinacao.csv` (ou similar): Arquivo contendo os dados de vacinação (usado em "BS2" e "Vacinação II").
* `Mod04_Tarefa_aula_03_a_05_(base) (1).ipynb` (ou similar): Notebook Jupyter contendo a análise dos dados de vacinação e as respostas para as questões "BS2" e "Vacinação II".
* `Analise_Vestibular_II.ipynb` (ou similar): Notebook Jupyter contendo a análise dos dados do vestibular e as respostas para a questão "Vestibular II".
* `README.md`: Este arquivo, fornecendo uma visão geral do repositório.

## Como Utilizar

1.  **Clonar o Repositório:**
    ```bash
    git clone <URL_DO_REPOSITORIO>
    cd <NOME_DO_REPOSITORIO>
    ```

2.  **Pré-requisitos:**
    Certifique-se de ter o Python instalado em seu sistema, juntamente com as seguintes bibliotecas:
    * `pandas`
    * `numpy` (geralmente instalado com pandas)

    Você pode instalar as bibliotecas usando o pip:
    ```bash
    pip install pandas
    ```

3.  **Executar os Notebooks:**
    Para executar os notebooks Jupyter, você precisará ter o Jupyter Notebook ou JupyterLab instalado. Se não tiver, você pode instalá-lo com:
    ```bash
    pip install notebook
    # ou
    pip install jupyterlab
    ```

    Navegue até o diretório do repositório no seu terminal e execute:
    ```bash
    jupyter notebook
    # ou
    jupyter lab
    ```

    Isso abrirá o Jupyter em seu navegador, onde você poderá abrir e executar os notebooks (`.ipynb` files).

4.  **Explorar os Dados:**
    Os arquivos de dados (`.csv`) podem ser abertos com qualquer editor de texto ou planilha para inspeção. Os notebooks carregam e processam esses dados para realizar as análises.

## Visão Geral das Análises

### Análise de Dados de Vacinação

O notebook de análise de vacinação (`Mod04_Tarefa_aula_03_a_05_(base) (1).ipynb`) explora um conjunto de dados de vacinação para responder a perguntas como:

* Quantos pacientes com menos de 18 anos foram vacinados?
* Quantos estabelecimentos aplicaram vacina no Acre?
* Quais estabelecimentos aplicaram vacinas a menores de 18 anos e qual a quantidade?
* Análise das categorias de vacinas aplicadas a menores de 18 anos.

### Análise de Dados de Vestibular

O notebook de análise do vestibular (`Analise_Vestibular_II.ipynb`) utiliza dados de um vestibular para:

* Identificar e listar os alunos desqualificados por zerarem em matemática, física ou química.
* Determinar a quantidade de alunos desqualificados.
* Calcular a média das notas em história e geografia dos alunos desqualificados.
* Criar um DataFrame com os alunos aprovados para a segunda fase (aqueles que não foram desqualificados).

## Contribuição

Contribuições para este repositório são bem-vindas. Se você encontrar erros, tiver sugestões de melhorias ou quiser adicionar novas análises, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.


