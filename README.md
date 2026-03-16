# 📊 Projeto 04 — Operação Nota Inflada

## 👥 Equipe

* **José Alves Ferreira Neto**
* **Filipe Pioner**
* **João Pedro Sobral**

---

# 🕵️ Operação Nota Inflada

## 📌 Descrição

Este projeto consiste em uma **investigação de dados educacionais** com o objetivo de identificar possíveis indícios de **inflação ou manipulação de notas internas em escolas**.

A hipótese investigada é que algumas instituições podem apresentar **notas internas significativamente maiores que os resultados obtidos em avaliações externas padronizadas**, o que pode indicar inconsistências no processo de avaliação interna.

A análise utiliza diferentes bases de dados educacionais para comparar resultados, identificar padrões e investigar possíveis discrepâncias.

---

## 🎯 Objetivos da Análise

A análise procura responder às seguintes perguntas investigativas:

1. **Existe discrepância entre notas internas e notas externas (SAEB)?**
   Comparar a média das avaliações internas com as notas do SAEB por escola para identificar diferenças relevantes.

2. **A distribuição das notas internas parece artificial?**
   Avaliar variância e desvio-padrão das notas entre escolas para identificar distribuições suspeitamente homogêneas.

3. **Há mudanças abruptas de desempenho ao longo do tempo?**
   Analisar a evolução temporal das notas internas e verificar se há saltos incompatíveis com as avaliações externas.

4. **Escolas com discrepâncias atingem metas e recebem bonificações?**
   Cruzar os dados de desempenho com o dataset de metas educacionais.

5. **O perfil socioeconômico explica o desempenho?**
   Avaliar se fatores socioeconômicos justificam os resultados obtidos.

6. **Quais evidências visuais indicam possíveis irregularidades?**
   Construir gráficos comparando escolas suspeitas com o restante da rede.

---

## 🔎 Etapas da Análise

O notebook segue as seguintes etapas:

1. Carregamento dos datasets
2. Exploração inicial dos dados
3. Tratamento e limpeza
4. Agrupamentos e agregações
5. Análise comparativa entre avaliações internas e externas
6. Análise temporal das notas
7. Cruzamento com dados socioeconômicos
8. Construção de visualizações para identificação de padrões suspeitos

---

## 🔎 Principais Descobertas

Durante a análise exploratória dos dados, foram observados alguns padrões relevantes:

* Existência de **diferenças significativas entre notas internas e avaliações externas (SAEB)** em determinadas escolas.
* Algumas instituições apresentam **distribuição de notas muito homogênea**, o que pode indicar padrões atípicos de avaliação.
* Foram identificados **casos de crescimento abrupto nas médias internas**, sem correspondência proporcional nas avaliações externas.
* A análise também sugere que **fatores socioeconômicos influenciam o desempenho**, mas não explicam completamente algumas discrepâncias observadas.

Esses resultados indicam **padrões que merecem investigação mais aprofundada**.

---

## ▶️ Como Executar o Projeto

Para executar a análise:

### 1️⃣ Instalar dependências

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 2️⃣ Executar o Jupyter Notebook

No terminal:

```bash
jupyter notebook
```

Depois abra o notebook localizado em:

```
notebooks/
```

Execute as células **na ordem em que aparecem no notebook** para reproduzir toda a análise.

---

## 🎥 Link do Vídeo



```
https://drive.google.com/drive/folders/1X1qaY0DobKW50cXHU4tpwcM92FW4AW52?usp=drive_link

---

## 📂 Estrutura do Repositório

```
projeto_04/
│
├── README.md          # Descrição geral do projeto
├── data/              # Datasets utilizados na análise
├── notebooks/         # Notebook principal da investigação
├── scripts/           # Scripts auxiliares (se houver)
└── docs/              # Documentação adicional ou apresentação
```

---

## 🛠 Tecnologias Utilizadas

* **Python**
* **Jupyter Notebook**
* **Pandas** — manipulação de dados
* **NumPy** — operações numéricas
* **Matplotlib** — visualização de dados
* **Seaborn** — visualizações estatísticas
* **Análise Exploratória de Dados (EDA)**

---

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como parte de uma atividade acadêmica de **pós-graduação** (MBA em Ciência de Dados - Universidade de Fortaleza / Unifor), envolvendo técnicas de **análise exploratória de dados e investigação baseada em dados educacionais**.