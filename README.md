# 🇵🇹 PT-Linguistic-Bias-Detector

### Auditoria Automatizada de Variedades Linguísticas e Viés de IA em Notícias PT-PT

O **PT-Linguistic-Bias-Detector** é uma ferramenta de investigação desenhada para analisar o enviesamento linguístico em meios de comunicação digitais. O foco principal é a distinção rigorosa entre o **Português Europeu (PT-PT)** e outras variedades (como o PT-BR), identificando desvios léxico-sintáticos comuns em textos gerados artificialmente por Modelos de Linguagem (LLMs).



## 🛠️ Tecnologias e Metodologia Avançada

Este projeto evoluiu de uma simples contagem de palavras para um pipeline completo de **Ciência de Dados aplicada às Humanidades**:

* **Processamento de Linguagem Natural (NLP):** Utilização da biblioteca **spaCy** (modelo `pt_core_news_sm`) para análise morfossintática profunda, incluindo **lematização** e identificação de traços gramaticais.
* **Deteção de "Decalques Sintáticos":** Identificação automática de **gerundismo**, um marcador estatístico frequente em LLMs não calibrados para a norma europeia.
* **Automação de Dados (Web Scraping):** Implementação de um motor de recolha automática via `newspaper3k` para a construção de *corpora* jornalísticos em tempo real.
* **Métricas de Densidade Normalizadas:** Cálculo de viés por cada 100 palavras, garantindo rigor estatístico na comparação de textos de diferentes extensões.

## 📊 Visualização e Reporting

O sistema gera automaticamente:
1.  **Dashboard Comparativo:** Gráficos de alta resolução que contrastam o viés lexical (vocabulário) com o viés sintático (gramática) de múltiplas fontes.
2.  **Relatório Técnico em PDF:** Exportação de um relatório formal com os resultados da auditoria, facilitando a partilha de *insights* de investigação.

## 📈 Relevância para Investigação

Este projeto demonstra competências críticas para a **auditoria de modelos de linguagem** e curadoria de dados em contexto nacional. É uma prova de conceito capaz de avaliar o rigor cultural de conteúdos gerados por IA, sendo uma ferramenta essencial para o combate à descaracterização linguística digital.

---

### 🚀 Como utilizar no Google Colab

1.  Carrega o ficheiro `PT_Linguistic_Bias_Detector.ipynb`.
2.  Garante que tens o ficheiro `dicionario_bias.csv` no diretório principal ou utiliza a célula de criação automática.
3.  Executa as células por ordem para gerar o dashboard e o PDF.
