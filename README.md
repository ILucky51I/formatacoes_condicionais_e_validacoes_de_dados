# Análise de Impostos — Case de Dados

## Sobre o projeto

Este projeto apresenta uma análise exploratória de um conjunto de dados relacionado à **renda anual, categoria profissional e percentual de imposto**.

O objetivo é trabalhar com os dados fornecidos no case, realizando etapas de **tratamento, padronização, análise e interpretação das informações**, utilizando conceitos fundamentais da área de Dados.

O dataset contém informações de diferentes profissionais classificados nas categorias:

- CLT
- Autônomo
- Empresário

A partir dessas informações, é possível explorar a relação entre **renda anual, categoria profissional e percentual de imposto**.

---

## Objetivo

Realizar o tratamento e a análise dos dados disponibilizados no case, buscando identificar padrões e informações relevantes sobre a distribuição da renda anual e dos percentuais de imposto entre diferentes categorias profissionais.

---

## Dataset

O arquivo utilizado no projeto é:

`dataset_impostos_case_situation_one.xlsx`

O arquivo possui duas abas principais:

### 1. Dataset de impostos

Contém as informações utilizadas na análise:

| Coluna | Descrição |
|---|---|
| ID | Identificador do registro |
| Renda Anual | Renda anual do profissional |
| Categoria Profissional | Categoria do profissional |
| Percentual de Imposto | Percentual de imposto associado ao registro |

### 2. DeXPara Categoria Profissional

Tabela auxiliar utilizada para padronização das categorias profissionais.

Exemplo:

| De | Para |
|---|---|
| CLT | CLT |
| AutÃ´nomo | Autônomo |
| EmpresÃ¡rio | Empresário |

Essa etapa permite corrigir possíveis problemas de codificação e padronizar os valores antes da análise.

---

## Estrutura dos dados

O dataset apresenta registros de profissionais distribuídos entre três categorias principais:

- **CLT**
- **Autônomo**
- **Empresário**

Entre as variáveis disponíveis estão valores de renda anual que variam de aproximadamente **R$ 20 mil a R$ 148 mil**, além de diferentes percentuais de imposto.

---

## Etapas do projeto

O projeto pode ser organizado nas seguintes etapas:

### 1. Importação dos dados

Leitura do arquivo Excel contendo o dataset e a tabela auxiliar de categorias.

### 2. Tratamento dos dados

Nesta etapa são realizadas atividades como:

- Identificação de valores inconsistentes;
- Remoção de linhas que não fazem parte do dataset;
- Padronização dos nomes das categorias;
- Tratamento de problemas de codificação de caracteres;
- Verificação de valores ausentes;
- Validação dos tipos de dados.

### 3. Transformação

Utilização da tabela **DeXPara** para garantir que as categorias profissionais estejam padronizadas.

### 4. Análise exploratória

Análise das principais características dos dados, incluindo:

- Distribuição da renda anual;
- Distribuição por categoria profissional;
- Percentual de imposto;
- Relação entre renda e percentual de imposto;
- Comparação entre categorias profissionais.

### 5. Visualização

Os dados podem ser apresentados por meio de gráficos como:

- Distribuição da renda anual;
- Renda média por categoria;
- Percentual médio de imposto por categoria;
- Relação entre renda anual e percentual de imposto;
- Quantidade de registros por categoria.

---

## Principais tecnologias

As ferramentas utilizadas ou recomendadas para o desenvolvimento do projeto incluem:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Excel**

---

## Estrutura do projeto

```text
analise-impostos/
│
├── data/
│   └── dataset_impostos_case_situation_one.xlsx
│
├── notebooks/
│   └── analise_impostos.ipynb
│
├── src/
│   └── tratamento_dados.py
│
├── README.md
└── requirements.txt
