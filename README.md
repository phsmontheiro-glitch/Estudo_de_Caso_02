# Estudo de Caso 02 — Análise da Escolaridade no Brasil

## Sobre o projeto

Este projeto foi desenvolvido para a disciplina de **Métodos Quantitativos para Tomada de Decisão**, com o objetivo de analisar dados relacionados à escolaridade da população brasileira.

A análise utiliza técnicas de tratamento de dados, estatística descritiva e visualização de dados para identificar padrões de escolaridade e diferenças entre regiões, estados, gêneros e municípios.

---

## Objetivos

- Analisar a distribuição da escolaridade no Brasil;
- Comparar os níveis de escolaridade entre as regiões brasileiras;
- Comparar os indicadores de escolaridade entre homens e mulheres;
- Analisar a distribuição do ensino superior completo entre os estados;
- Avaliar diferenças de escolaridade dentro dos municípios da Bahia;
- Utilizar medidas de estatística descritiva para interpretar os dados;
- Identificar desigualdades educacionais presentes nos dados analisados.

---

## Metodologia

O estudo foi realizado utilizando **Python** e bibliotecas de análise e visualização de dados.

Inicialmente, os dados foram carregados a partir de uma planilha Excel e passaram por uma etapa de limpeza e organização. As colunas foram padronizadas para facilitar a manipulação dos dados durante a análise.

Em seguida, foram realizadas análises envolvendo:

- Brasil;
- Regiões brasileiras;
- Estados;
- Região Nordeste;
- Municípios da Bahia;
- Comparação entre homens e mulheres;
- Ensino superior completo;
- Baixa escolaridade e risco educacional.

Também foram calculadas medidas de **média, mediana, desvio padrão, mínimo, máximo e amplitude**.

---

## Visualizações desenvolvidas

O estudo apresenta diferentes visualizações para facilitar a interpretação dos dados.

### 1. Escolaridade no Brasil por gênero

Comparação entre os níveis de escolaridade da população total, homens e mulheres.

A análise indica maior concentração nos níveis intermediários de escolaridade e maior percentual de ensino superior completo entre as mulheres.

### 2. Comparação entre regiões

Análise da distribuição dos níveis de escolaridade nas regiões Norte, Nordeste, Sudeste, Sul e Centro-Oeste.

Os dados analisados apresentam diferenças regionais importantes, especialmente entre os indicadores de baixa escolaridade e ensino superior completo.

### 3. Homens e mulheres nas regiões

Comparação dos percentuais de ensino superior completo entre homens e mulheres nas diferentes regiões.

Os resultados apresentados mostram maior percentual de ensino superior completo entre as mulheres na maior parte das regiões analisadas.

### 4. Estatística descritiva

Para os estados brasileiros, foram calculadas as seguintes medidas para o indicador de ensino superior completo:

- **Média:** 10,08
- **Mediana:** 9,32
- **Desvio padrão:** 4,49
- **Mínimo:** 1,73
- **Máximo:** 45,20
- **Amplitude:** 43,47

Os resultados demonstram uma variação significativa entre os estados analisados.

### 5. Ranking dos estados

Foi elaborado um ranking dos estados de acordo com o percentual de população com ensino superior completo, permitindo comparar os diferentes resultados entre as unidades federativas.

### 6. Análise do Nordeste

Foi realizada uma análise específica dos estados da região Nordeste, observando o indicador de ensino superior completo e as diferenças existentes entre os estados.

### 7. Municípios da Bahia

Também foi realizada uma análise dos municípios da Bahia, incluindo estatística descritiva e distribuição dos dados.

Resultados encontrados:

- **Média:** 7,82
- **Mediana:** 7,82
- **Desvio padrão:** 4,18
- **Mínimo:** 4,86
- **Máximo:** 10,77
- **Amplitude:** 5,91

Os resultados indicam diferenças internas entre os municípios analisados.

### 8. Histograma

Foi utilizado um histograma para observar a distribuição dos níveis de ensino superior completo entre os municípios analisados da Bahia.

### 9. Radar das regiões

O gráfico radar foi utilizado para comparar visualmente o perfil educacional das diferentes regiões brasileiras.

### 10. Perfil e risco educacional por região

Também foram desenvolvidas visualizações para comparar o perfil educacional das regiões e analisar indicadores relacionados à baixa escolaridade.

---

## Tecnologias utilizadas

- **Python**
- **Pandas**
- **NumPy**
- **Plotly**
- **Matplotlib**
- **Google Colab**
- **Microsoft Excel**

---

## Como executar

O projeto foi desenvolvido no **Google Colab** utilizando Python.

### Passo a passo

1. Acesse o arquivo [`Estudo_de_Caso_02.ipynb`](./Estudo_de_Caso_02.ipynb);
2. Clique em **Open in Colab** ou abra o notebook diretamente no Google Colab;
3. Certifique-se de que a planilha [`caso 2.xlsx`](./caso%202.xlsx) esteja disponível no mesmo ambiente;
4. Execute as células do notebook na sequência.

### Bibliotecas utilizadas

As principais bibliotecas utilizadas no projeto são:

```python
import pandas as pd
import numpy as np
import plotly.graph_objects as go
import plotly.express as px
import matplotlib.pyplot as plt
````

---

## Estrutura do repositório

```text
Estudo-de-Caso-02/
│
├── Estudo_de_Caso_02.ipynb
├── caso 2.xlsx
├── README.md
└── LICENSE
```

---

## Integrantes

**Pedro Henrique Silva Monteiro** —
[@phsmontheiro-glitch](https://github.com/phsmontheiro-glitch)

**Robson Otávio Queiroz Castro** —
[@robsonotavioqueirozcastroo343-pixel](https://github.com/robsonotavioqueirozcastroo343-pixel)

**Igor Jesus da Silva Tolentino** —
[@igorjesusdasilvatoletntino](https://github.com/igorjesusdasilvatoletntino)

---

## Disciplina

**Métodos Quantitativos para Tomada de Decisão**

**Centro Universitário UDF**

---

## Observação

Este repositório contém materiais desenvolvidos para fins acadêmicos, incluindo o notebook utilizado para tratamento, análise e visualização dos dados.

