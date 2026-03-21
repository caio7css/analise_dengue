# Análise de Padrões Espaciais e Temporais da Dengue em Campina Grande

Este repositório contém o desenvolvimento técnico referente ao plano de trabalho de Iniciação Científica (PIBIC/UEPB) focado na identificação de zonas de risco de dengue através de técnicas de **Aprendizado de Máquina Não Supervisionado**.

## 📌 Visão Geral do Projeto
[cite_start]O projeto visa transcender os métodos tradicionais de vigilância epidemiológica, utilizando algoritmos de clusterização para extrair padrões ocultos e identificar agrupamentos naturais nos dados de Campina Grande/PB. A análise integra variáveis epidemiológicas (incidência, sazonalidade), fatores ambientais (precipitação, temperatura) e indicadores sociodemográficos.

## 🛠️ Tecnologias e Algoritmos
[cite_start]A implementação foca na avaliação e comparação dos seguintes modelos:
* **K-Means:** Para particionamento dos dados em grupos homogêneos.
* **DBSCAN:** Para identificação de clusters baseados em densidade e detecção de outliers.
* **Agrupamento Hierárquico:** Para investigação de estruturas de dados em diferentes níveis.

## 📊 Métricas de Validação
[cite_start]Para garantir a precisão científica, os modelos são avaliados por meio de:
* **Silhouette Score:** Medição de coesão e separação.
* **Davies-Bouldin Index:** Avaliação da similaridade entre clusters.
* **Análise Qualitativa:** Confronto dos clusters gerados com a realidade dos dados epidemiológicos locais.

## 📂 Estrutura do Repositório
* [cite_start]`/data`: Bases de dados epidemiológicos, ambientais e georreferenciáveis[cite: 146].
* [cite_start]`/notebooks`: Experimentos de implementação, tratamento de dados faltantes e normalização[cite: 146].
* `/src`: Scripts principais de aplicação dos algoritmos (K-Means, DBSCAN, etc).
* [cite_start]`/results`: Mapas de calor e visualizações geográficas das áreas de risco[cite: 146].

## 📅 Cronograma de Atividades (Resumo)
| Atividade | Descrição | Período (2025-2026) |
| :--- | :--- | :--- |
| **Atividade 4** | Coleta de dados epidemiológicos e ambientais | Nov - Jan |
| **Atividade 5** | Tratamento, normalização e georreferenciamento | Dez - Fev |
| **Atividade 6** | Implementação dos algoritmos de clusterização | Jan - Mar |
| **Atividade 7** | Validação métrica e refinamento dos modelos | Mar - Mai |

---
**Aluno:** Caio César Silva dos Santos 
**Orientador:** Dunfrey Pires Aragão 
**Instituição:** Universidade Estadual da Paraíba (UEPB) 
