# 🦟 Identificação de Zonas de Proliferação de Dengue com Machine Learning

Projeto de Iniciação Científica (PIVIC/UEPB) voltado à análise espaço-temporal da dengue em Campina Grande/PB utilizando técnicas de **aprendizado de máquina**, com foco em **clusterização de dados epidemiológicos** e integração futura com processamento de imagens de satélite.

---

## 📌 Sobre o Projeto

A dengue é um dos principais desafios de saúde pública no Brasil. Este projeto propõe o uso de técnicas de **Machine Learning não supervisionado** para identificar padrões ocultos na distribuição dos casos da doença.

A partir da análise de dados epidemiológicos, ambientais e sociodemográficos, buscamos:

* Identificar **áreas de maior risco**
* Detectar **padrões espaço-temporais**
* Auxiliar na **tomada de decisão em saúde pública**

---

## 🎯 Objetivos

### Objetivo Geral

Aplicar algoritmos de clusterização para analisar a distribuição dos casos de dengue em Campina Grande/PB.

### Objetivos Específicos

* Aplicar algoritmos como:

  * K-Means
  * DBSCAN
  * Clusterização Hierárquica
* Avaliar desempenho com métricas:

  * Silhouette Score
  * Davies-Bouldin Index
* Gerar visualizações:

  * Mapas de calor
  * Distribuição geográfica dos clusters
* Identificar padrões relevantes para apoio a políticas públicas

---

## 🧠 Tecnologias e Métodos

* **Linguagem:** Python

* **Bibliotecas (previstas):**

  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib / Seaborn
  * GeoPandas / Folium (visualização geográfica)

* **Técnicas utilizadas:**

  * Aprendizado de Máquina Não Supervisionado
  * Clusterização de Dados
  * Análise Espacial

---

## 📊 Dados Utilizados

O projeto integra diferentes fontes de dados:

* Dados epidemiológicos (casos de dengue)
* Dados ambientais (temperatura, chuva, etc.)
* Dados sociodemográficos
* (Futuro) Imagens de satélite

---

## ⚙️ Estrutura do Projeto (sugestão)

```
📁 projeto-dengue-ml
│
├── data/               # Dados brutos e tratados
├── notebooks/         # Análises exploratórias
├── src/               # Implementação dos algoritmos
├── results/           # Resultados, gráficos e mapas
├── docs/              # Relatórios e documentação
└── README.md
```

---

## 📈 Resultados Esperados

* Identificação de **clusters de risco**
* Geração de **mapas de calor**
* Análise comparativa entre algoritmos
* Suporte à:

  * Vigilância epidemiológica
  * Planejamento de ações públicas
  * Combate ao Aedes aegypti

---

## 🚧 Status do Projeto

🔄 Em desenvolvimento
📌 Etapa atual: Estruturação do repositório e início da implementação dos modelos de clusterização

---

## 👨‍💻 Autor

**Caio César Silva dos Santos**
Graduando em Ciência da Computação - UEPB
Projeto de Iniciação Científica (PIVIC)

---

## 👨‍🏫 Orientação

**Prof. Dr. Dunfrey Pires Aragão**

---

## 📄 Licença

Este projeto é de caráter acadêmico. A definir.

---

## 🤝 Contribuição

Contribuições são bem-vindas para fins acadêmicos e de pesquisa.
Sinta-se à vontade para abrir issues ou pull requests.

---

## 📌 Observação

Este repositório faz parte de um projeto maior que também inclui:

* Processamento de imagens de satélite (CNNs)
* Desenvolvimento de plataforma web para visualização dos dados

---

