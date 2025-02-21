# Score de Risco - Praso

Este projeto implementa um modelo de machine learning para prever a inadimplência de clientes com base em seus dados financeiros e cadastrais.

##  Descrição

A solução desenvolvida visa calcular um **Score de Risco** utilizando dados anonimizados fornecidos pela Praso. O modelo utiliza técnicas de aprendizado de máquina para prever a probabilidade de um cliente se tornar inadimplente.

##  Tecnologias Utilizadas

- Python
- Jupyter Notebook
- Pandas, NumPy, Scikit-Learn
- XGBoost, LightGBM
- Git & GitHub

markdown

# Como Rodar o Projeto Localmente e no Google Colab

## Rodando o Projeto Localmente

Recebendo o repositório no GitHub:

```bash
git init
git remote add origin https://github.com/JoaoTeles87/Score_Risco_Praso.git
git push -u origin main
```

**Crie um ambiente virtual**:
   ```bash
   python -m venv env
   ```

Ative o ambiente virtual:

No Windows:

```bash

env\Scripts\activate
```
No Linux ou macOS:

```bash
source env/bin/activate
```
Instale as bibliotecas necessárias:


```bash
pip install jupyterlab ipykernel pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm
```
Registre o ambiente virtual como um kernel no Jupyter:


```bash
python -m ipykernel install --user --name=env --display-name "Python (env)"
```

Inicie o Jupyter:

Para o Jupyter Notebook:

```bash
jupyter notebook
```

Para o Jupyter Lab:

```bash
jupyter lab
```
Selecione o kernel "Python (env)" ao criar um novo notebook no Jupyter.

Rodando o Projeto no Google Colab:

Monte o Google Drive:

```python

from google.colab import drive
drive.mount('/content/drive')
```
Clone o repositório:
```bash
!git clone <URL_DO_REPOSITORIO>
```
Após fazer alterações no Colab, envie as atualizações de volta para o GitHub:

```bash
!git add .
!git commit -m "Atualização do modelo de score"
!git push origin main
```

## ⚖️ Licença

Este projeto é licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
