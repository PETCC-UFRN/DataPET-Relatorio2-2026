# DataPET-Relatorio2-2026
# Análise do Impacto do El Niño no Rio Grande do Norte

Este repositório contém um Jupyter Notebook projetado para analisar como o fenômeno climático El Niño afeta os índices de chuvas e as temperaturas no estado do Rio Grande do Norte (RN). O estudo busca responder questões como a correlação entre a intensidade do El Niño e as precipitações, além do possível deslocamento do período chuvoso.

## Pré-requisitos

* **Python 3.x** instalado na sua máquina.

## Como configurar o Ambiente Virtual e rodar o Notebook

Como o ambiente virtual do projeto já está configurado você apenas precisa instalar o gerenciador de pacotes e sincronizar os pacotes faltantes seguindo os seguintes passos.
### 1. Instalar o UV

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```


### 3. Sincronizar os pacotes
Para instalar pacotes faltantes, no diretório do projeto execute:

```bash
uv sync
```


### 4. Abrir o Notebook

Inicie o servidor local do Jupyter rodando:

```bash
source .venv/bin/activate  
jupyter notebook
```

Uma aba será aberta automaticamente no seu navegador. Navegue pela interface, clique no arquivo `.ipynb` do projeto e ele será carregado.

Ou utilize uma extensão no seu IDE para visualização de notebooks jupyter.
## Adição de dependências
Para adicionar bibliotecas python ao ambiente virtual, navegue até o diretório do projeto e execute:

```bash
uv add <nome-do-pacote>
```

O pacote será instalado e adicionado na lista de dependências automaticamente.