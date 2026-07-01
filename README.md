# EDA de Produtos Agrícolas

Análise exploratória de dados de variaçção de preços de produtos agrícolas entre 1990 e 2020.

## Visão geral

Este projeto contém um estudo de exploração de dados (EDA) sobre a evolução dos preços de matérias-primas agrícolas ao longo de 20 anos. Os notebooks incluem ingestão de dados, limpeza, visualizações e análise de padrões de correlação.

## Estrutura do projeto

- `data/raw/` — dados brutos usados na análise
- `notebooks/` — notebooks Jupyter com a análise
- `requirements.txt` — dependências Python necessárias
- `venv/` — ambiente virtual local (não versionado)

## Como usar

1. Criar e ativar um ambiente virtual:

   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   ```

2. Instalar dependências:

   ```powershell
   pip install -r requirements.txt
   ```

3. Abrir o notebook de análise em `notebooks/`:

   - `notebooks/01_eda_produtos_agricolas.ipynb`
   - `notebooks/02_agricultural_products_eda.ipynb`

4. Executar células no Jupyter Notebook ou JupyterLab.

## Dependências principais

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## Observações

- Os notebooks contêm a análise principal e não foram alterados.
- O arquivo de dados está localizado em [`data/raw/agricultural_product_prices_1990_2020.csv`](https://www.kaggle.com/datasets/kianwee/agricultural-raw-material-prices-19902020).
