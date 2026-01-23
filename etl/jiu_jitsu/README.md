# Coach Digital para Atletas de Jiu-Jitsu

## Visão Geral

Este projeto propõe o desenvolvimento de um **coach digital para atletas de Jiu-Jitsu**, baseado na análise de dados de combates e das características individuais dos atletas. O sistema utiliza técnicas de ciência de dados para apoiar a avaliação de desempenho competitivo, com foco na identificação de padrões técnicos e táticos associados a falhas, ineficiências ou vantagens durante as lutas.

O projeto possui caráter **exploratório e analítico**, com o objetivo de **auxiliar treinadores e atletas na tomada de decisão**, sem substituir a avaliação humana, a experiência técnica ou o contexto específico de cada combate.

---

## Objetivos

### Objetivo principal
- Identificar **pontos de melhoria no desempenho competitivo** dos atletas a partir da análise de métricas de combate, estilo de jogo, resultados e padrões técnicos.

### Objetivo secundário
- Descrever **vantagens competitivas individuais**, destacando técnicas, posições e comportamentos associados a maiores taxas de sucesso em campeonatos.

---

## Abordagem Metodológica

O projeto integra conceitos de:
- Ciência de dados
- Análise de desempenho esportivo
- Processamento de dados estruturados
- Uso de APIs e notebooks interativos

As análises são realizadas **exclusivamente com base nos dados disponíveis**, evitando inferências subjetivas ou extrapolações não sustentadas.

---

## Arquitetura do Pipeline (ETL)

O fluxo de dados segue o modelo ETL (Extract, Transform, Load):

### Extração (Extract)
- Extração de dados via **API do Google Drive**, simulando dados oriundos de uma planilha do **Google Sheets**.

### Transformação (Transform)
- Processamento, padronização e enriquecimento dos dados utilizando a **API do Gemini 2.5**.
- Geração de resumos técnicos e análises orientadas ao desempenho competitivo dos atletas.

### Carga (Load)
- Organização e manipulação dos dados utilizando **Pandas**.
- Envio dos dados transformados para o **Google Drive** por meio de API.
- Dados em formato CSV.

---

---

## Notebooks e Dados

- 📓 **Notebook no Google Colab**  
  https://colab.research.google.com/drive/18-p7cLJwrxH3CyUcoIt3InHHRlsxNPi0?usp=sharing

- 📊 **Base de dados em CSV**  
  https://drive.google.com/uc?export=download&id=1lphf-veG30G3QcKY6ojJQFgCMuFbidX-

- 📦 O notebook também está disponível neste repositório para execução local.

---

## Considerações Éticas e Limitações

Este projeto:
- Não prevê resultados de lutas
- Não substitui treinadores ou avaliações técnicas humanas
- Não utiliza dados sensíveis reais de atletas

O sistema atua exclusivamente como **ferramenta de apoio analítico**, fornecendo evidências e padrões que podem auxiliar decisões estratégicas.

---

## Autor

Projeto desenvolvido no contexto de estudos em **ciência de dados e análise de desempenho esportivo**, aplicado ao Jiu-Jitsu competitivo.

