# 🧪 Projeto de Análise de Dados — Pacientes com Diabetes

Este projeto realiza uma **análise exploratória de dados** sobre pacientes com diabetes, utilizando **Python 3**, **pandas**, e consulta a dados armazenados em **arquivos CSV e um banco de dados SQLite**. O foco está na consolidação de habilidades em leitura de dados, filtragem, agrupamento e estatísticas básicas.

---

## 🎯 Objetivo

Aplicar conhecimentos de **análise de dados e manipulação de datasets** reais para extrair informações úteis sobre pacientes, com foco em indicadores de diabetes. O projeto utiliza diferentes fontes de dados (`CSV`, `SQLite`) e oferece uma introdução prática à exploração de dados em Python.

---

## 🖥️ Funcionalidades

- Leitura de dados de pacientes e registros de diabetes a partir de arquivos `.csv` e `.db`
- Análises com `pandas` e `sqlite3`, incluindo:
  - Contagem de pacientes por faixa etária
  - Médias de glicose, pressão e IMC
  - Identificação de casos com diabetes e sem
  - Agrupamentos e filtragens por sexo, idade e diagnóstico
- Geração de estatísticas descritivas sobre o conjunto de dados
- Integração entre dados em `CSV` e registros armazenados em banco de dados

---

## 🧱 Tecnologias Usadas

- Python 3  
- `pandas` para leitura e manipulação de dados  
- `sqlite3` para acesso ao banco de dados  
- `os`, `csv`, `statistics` e outras bibliotecas nativas para processamento

---

## 📂 Estrutura do Projeto

    ├── Projeto.py  Script principal com lógica e análise
    ├── database/
        └── diabetes.db  Banco de dados SQLite com dados de pacientes
    ├── dataset/
        └── diabetes.csv  Conjunto de dados principal com atributos médicos
        └── pacientes.csv  Lista com dados demográficos dos pacientes


---

## 🚀 Como Executar

  1. Clone o repositório:

    git clone https://github.com/ekthra/AnaliseBasica.git


  2. Acesse a pasta do projeto:

    cd ProjetoAnalise

  3.Instale as dependências (caso necessário):

    pip install pandas
     Observação: As bibliotecas sqlite3, os, csv, statistics e math já fazem parte da biblioteca padrão do Python, então não precisam ser instaladas separadamente.

  4. Apague os arquivos pacientes.csv e diabetes.db antes de rodar o script


    del dataset/pacientes.csv database/diabetes.db        # Windows (cmd)
    rm dataset/pacientes.csv database/diabetes.db         # Linux/Mac (bash)

    Estes arquivos serão gerados pelo código em Python.
   
  5. Execute o script principal
    
    python Projeto.py
O script irá:

    Gerar novamente os arquivos pacientes.csv e diabetes.db

    Carregar os dados e realizar análises estatísticas

    Exibir os resultados diretamente no terminal
