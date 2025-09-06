Configuração e execução
Para rodar a análise, siga estes passos para configurar o ambiente e executar o notebook.

# 1. Configuração do Ambiente Virtual
É altamente recomendado usar um ambiente virtual para isolar as dependências do projeto.


# Crie o ambiente virtual
```bash
python -m venv venv
```
# Ative o ambiente virtual

# No macOS/Linux:
```bash
source venv/bin/activate
```
# No Windows:
```bash
venv\Scripts\activate
```

# 2. Instalação das Dependências
Com o ambiente virtual ativado, instale todas as bibliotecas necessárias listadas no requirements.txt.

```bash
pip install -r requirements.txt
```
3. Execução do Notebook
Após a instalação, inicie o Jupyter Notebook na pasta do projeto e abra o arquivo .ipynb.

```bash
jupyter notebook
```
O notebook irá abrir no seu navegador. Siga as células de código para executar a análise passo a passo.