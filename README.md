# Sales Funnel Analysis & A/A/B Test - Food App

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Sobre o projeto

Analise de comportamento de usuarios e teste A/A/B para o app de uma startup de produtos alimenticios. O projeto investiga o funil de vendas para entender a progressao dos usuarios ate a compra e avalia o impacto estatistico de uma mudanca de fonte no aplicativo. Projeto desenvolvido no Bootcamp de Analise de Dados da TripleTen Brasil.

## Perguntas de negocio

- Como os usuarios progridem pelo funil de vendas ate a compra?
- - Em qual etapa do funil ocorre a maior perda de usuarios?
  - - Qual proporcao de usuarios completa o funil inteiro?
    - - A mudanca de fonte no app causa impacto estatisticamente significativo na conversao?
      - - Os grupos de controle (246 e 247) sao equivalentes, validando o experimento?
       
        - ## Estrutura do projeto
       
        - **Passo 1 e 2 - Carregamento e preparacao dos dados**
        - - Importacao de bibliotecas e carregamento do CSV
          - - Renomeacao de colunas para snake_case
            - - Tratamento de valores ausentes e tipos de dados
              - - Criacao de colunas de data/hora formatada
               
                - **Passo 3 - Exploracao dos dados**
                - - Contagem de eventos e usuarios unicos
                  - - Histograma de eventos por data para identificar ponto de corte
                    - - Filtragem de dados incompletos
                      - - Verificacao dos 3 grupos experimentais
                       
                        - **Passo 4 - Analise do funil de eventos**
                        - - Frequencia de cada evento
                          - - Usuarios unicos por etapa do funil
                            - - Taxas de conversao entre etapas
                              - - Identificacao da maior perda no funil
                               
                                - **Passo 5 - Analise do teste A/A/B**
                                - - Comparacao grupos de controle 246 vs 247 (validacao A/A)
                                  - - Z-test de proporcoes para cada evento
                                    - - Comparacao grupo de teste 248 vs grupos de controle
                                      - - Conclusao sobre impacto da mudanca de fonte
                                       
                                        - ## Dataset utilizado
                                       
                                        - | Arquivo | Descricao |
                                        - |---------|----------|
                                        - | `logs_exp_us.csv` | Logs de eventos de usuarios com grupo experimental (246, 247 = controle, 248 = teste) |
                                       
                                        - ## Stack utilizada
                                       
                                        - - Python 3
                                          - - Pandas - manipulacao e analise de dados
                                            - - Matplotlib / Seaborn - visualizacao de dados
                                              - - SciPy - testes de proporcoes (z-test)
                                                - - Jupyter Notebook
                                                 
                                                  - ## Como executar
                                                 
                                                  - ```bash
                                                    git clone https://github.com/carinelit/analise-funil-teste-aab
                                                    cd analise-funil-teste-aab
                                                    jupyter notebook
                                                    ```

                                                    ## Portfolio

                                                    [linkedin.com/in/carinelitwinczuk](https://www.linkedin.com/in/carinelitwinczuk)# Sales Funnel Analysis & A/A/B Test - Food App

                                                    ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
                                                    ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
                                                    ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
                                                    ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
                                                    ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

                                                    ## Sobre o projeto

                                                    Analise de comportamento de usuarios e teste A/A/B para o app de uma startup de produtos alimenticios. Investiga o funil de vendas e avalia o impacto estatistico de uma mudanca de fonte no aplicativo. Projeto desenvolvido no Bootcamp de Analise de Dados da TripleTen Brasil.

                                                    ## Perguntas de negocio

                                                    - Como os usuarios progridem pelo funil de vendas ate a compra?
                                                    - - Em qual etapa do funil ocorre a maior perda de usuarios?
                                                      - - Qual proporcao de usuarios completa o funil inteiro?
                                                        - - A mudanca de fonte no app causa impacto estatisticamente significativo?
                                                          - - Os grupos de controle 246 e 247 sao equivalentes, validando o experimento?
                                                           
                                                            - ## Estrutura do projeto
                                                           
                                                            - **Preparacao dos dados:** carregamento, snake_case, tipos, colunas de data
                                                           
                                                            - **Exploracao:** eventos por usuario, histograma temporal, ponto de corte, grupos experimentais
                                                           
                                                            - **Funil de eventos:** frequencia por etapa, usuarios unicos, taxas de conversao, maior perda
                                                           
                                                            - **Teste A/A/B:** z-test de proporcoes, validacao A/A, comparacao grupo 248 vs controles, conclusao
                                                           
                                                            - ## Dataset utilizado
                                                           
                                                            - | Arquivo | Descricao |
                                                            - |---------|----------|
                                                            - | `logs_exp_us.csv` | Logs de eventos com grupo experimental (246, 247 = controle, 248 = teste) |
                                                           
                                                            - ## Stack utilizada
                                                           
                                                            - - Python 3
                                                              - - Pandas - manipulacao e analise de dados
                                                                - - Matplotlib / Seaborn - visualizacao de dados
                                                                  - - SciPy - testes de proporcoes (z-test)
                                                                    - - Jupyter Notebook
                                                                     
                                                                      - ## Como executar
                                                                     
                                                                      - ```bash
                                                                        git clone https://github.com/carinelit/analise-funil-teste-aab
                                                                        cd analise-funil-teste-aab
                                                                        jupyter notebook
                                                                        ```

                                                                        ## Portfolio

                                                                        [linkedin.com/in/carinelitwinczuk](https://www.linkedin.com/in/carinelitwinczuk)
