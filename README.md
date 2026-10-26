# DataPET-Relatorio2-2026
# Análise do Impacto do El Niño no Rio Grande do Norte

Este repositório contém um Jupyter Notebook projetado para analisar como o fenômeno climático El Niño afeta os índices de chuvas e as temperaturas no estado do Rio Grande do Norte (RN). O estudo busca responder questões como a correlação entre a intensidade do El Niño e as precipitações, além do possível deslocamento do período chuvoso.

## Pré-requisitos

* **Python 3.x** instalado na sua máquina.

## Como configurar o Ambiente Virtual (venv) e rodar o Notebook

Siga os passos abaixo no terminal do seu sistema operacional para criar um ambiente isolado e executar o projeto de forma limpa.

### 1. Criar o ambiente virtual

Navegue pelo terminal até a pasta onde o seu arquivo `.ipynb` está salvo e execute:

```bash
python -m venv venv

```

### 2. Ativar o ambiente virtual

A ativação varia conforme o seu sistema operacional:

* **Windows (Prompt de Comando ou PowerShell):**
```bash
venv\Scripts\activate

```


* **Linux ou macOS:**
```bash
source venv/bin/activate

```



*(Dica: Ao ativar, você verá o prefixo `(venv)` no seu terminal).*

### 3. Instalar o Jupyter

Com o ambiente ativado, instale a interface do Jupyter para conseguir abrir e interpretar o arquivo `.ipynb`:

```bash
pip install jupyter

```

### 4. Abrir o Notebook

Inicie o servidor local do Jupyter rodando:

```bash
jupyter notebook

```

Uma aba será aberta automaticamente no seu navegador. Navegue pela interface, clique no arquivo `.ipynb` do projeto e ele será carregado.

### 5. Execução e Dependências Automáticas

Não é necessário instalar as bibliotecas de análise de dados manualmente via terminal. A primeira célula de código do próprio notebook já contém um script estruturado que verifica e instala automaticamente todas as dependências necessárias, como `pandas`, `numpy`, `requests`, `matplotlib`, `seaborn`, `scipy`, `statsmodels` e APIs meteorológicas.

Basta rodar as células do notebook sequencialmente (usando `Shift + Enter`) para que o ambiente configure as bibliotecas e carregue as bases de dados históricas da NOAA.
