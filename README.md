# Análise de Ocorrências Aéreas no Brasil (CENIPA)

## Sobre o Projeto

Este projeto consiste em uma análise exploratória de dados sobre ocorrências aeronáuticas no Brasil, utilizando informações públicas disponibilizadas pelo CENIPA (Centro de Investigação e Prevenção de Acidentes Aeronáuticos).

O estudo foi inspirado no projeto original disponível em:  
https://github.com/paulozip/acidentes-aereos  
Porém, toda a análise, seleção de perguntas e visualizações foram desenvolvidas de forma autoral com foco em diferentes aspectos dos dados.

---

## Dataset Utilizado

- **ocorrencia.csv** – Informações gerais sobre cada ocorrência (data, localização, classificação, status da investigação, etc.).
- **aeronave.csv** – Detalhes sobre as aeronaves envolvidas (fabricante, modelo, tipo de motor, ano de fabricação, número de fatalidades, etc.).

Fonte dos dados: Dados Abertos do CENIPA.

---

## Perguntas Respondidas

O projeto buscou responder as seguintes questões:

1. Como evoluiu o número de ocorrências aéreas no Brasil ao longo dos anos?
2. Quais estados (UFs) concentram o maior número de ocorrências?
3. Durante qual fase do voo os acidentes com fatalidades são mais frequentes?
4. A idade da aeronave influencia na gravidade do dano?
5. Quanto tempo, em média, leva uma investigação até a publicação do relatório final?

Além disso, foi incluída uma análise bônus mostrando a distribuição de ocorrências por estado (UF).

---

## Ferramentas Utilizadas

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (Google Colab)

---

## Estrutura do Repositório

- `datasets/` → Arquivos CSV com os dados originais.
- `acidentes_aereos.ipynb` → Notebook com toda a análise.
- `README.md` → Este arquivo.

---

## Observações Finais

Este projeto tem fins exclusivamente educacionais e acadêmicos. Os dados utilizados são públicos e foram obtidos diretamente do CENIPA.

