# imersao-dados-python

# Dashboard de Salários na Área de Dados

Este é um dashboard interativo construído com Streamlit, Pandas e Plotly para analisar salários na área de dados. Ele permite explorar e filtrar dados salariais por ano, senioridade, tipo de contrato e tamanho da empresa.

## Funcionalidades

-   **Filtros:** Utilize a barra lateral para filtrar os dados por:
    -   Ano
    -   Senioridade
    -   Tipo de Contratação
    -   Tamanho da Empresa
-   **Métricas Principais:** Visualize métricas importantes como:
    -   Salário médio
    -   Salário máximo
    -   Total de registros
    -   Cargo mais frequente
-   **Gráficos:** Explore os dados através de gráficos interativos:
    -   Top 10 cargos por salário médio
    -   Distribuição de salários anuais
    -   Proporção dos tipos de trabalho (remoto, híbrido, presencial)
    -   Salário médio de Cientista de Dados por país
-   **Tabela de Dados Detalhados:** Visualize todos os dados filtrados em uma tabela interativa.

## Como usar

1.  **Instale as dependências:**

    ```bash
    pip install -r requirements.txt
    ```
2.  **Execute o aplicativo:**

    ```bash
    streamlit run app.py
    ```
3.  **Acesse o dashboard:**
    Abra o link exibido no terminal no seu navegador.

## Dependências

-   streamlit==1.44.1
-   pandas==2.2.3
-   plotly==5.24.1

## Fonte de Dados

Os dados são carregados do seguinte repositório:

https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv

## Autor
[Marilia](https://github.com/seu-usuario)

