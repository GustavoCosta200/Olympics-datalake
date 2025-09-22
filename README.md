# 🏅 Olympics Data Lake

Este repositório organiza e disponibiliza um **Data Lake analítico** sobre os Jogos Olímpicos, abrangendo desde 1896 até Paris 2024.  
O objetivo é estruturar os dados em diferentes camadas para facilitar análises históricas, comparativas e de evolução das modalidades e países.

---

## 📂 Estrutura do Repositório

- **`raw/`** → arquivos originais (CSV).  
- **`bronze/`** → dados convertidos para **Parquet** e padronizados.  
- **`silver/`** → tabelas intermediárias (transformações e limpezas).  
- **`gold/`** → análises finais e datasets prontos para exploração (CSV e Parquet).  

---

## 📊 Principais Análises (Camada Gold)

- **Medalhas por ano (overall)** → evolução histórica do número total de medalhas.  
- **Medalhas por ano e país** → ranking por delegação em cada edição dos Jogos.  
- **Crescimento das modalidades** → identificação de esportes/disciplines que mais expandiram em participação ao longo do tempo.  

Esses resultados estão disponíveis em formatos **CSV** e **Parquet** dentro da pasta `gold/`.

---

## 📑 Fontes de Dados

- [Base dos Dados – Jogos Olímpicos (1896–2022)](https://basedosdados.org/dataset/62f8cb83-ac37-48be-874b-b94dd92d3e2b)  
- [Kaggle – Paris 2024 Olympic Summer Games](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games/data)  

---

## 🚀 Possibilidades de Uso

- Estudos acadêmicos sobre desempenho esportivo.  
- Análises comparativas entre países e modalidades.  
- Integração com ferramentas de ciência de dados.  

---

## 👥 Autoria

- [Luis Gustavo](https://github.com/GustavoCosta200)  
- [Kaique Olegar](https://github.com/kaiqu3santoss)  
