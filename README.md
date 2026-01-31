# 📊 Consumo de Streaming no Brasil – Análise Regional (2024)

## 📌 Objetivo
Este projeto analisa o consumo de streaming nas regiões brasileiras, com foco em compreender
por que a **Região Norte apresenta menor consumo via televisão**, mesmo possuindo ampla
presença de aparelhos e acesso à internet.

A análise relaciona infraestrutura digital, dispositivos disponíveis e comportamento de consumo,
buscando explicar **como e onde o streaming ocorre em cada região**.

---

## 📂 Fonte dos dados
- **IBGE – PNAD TIC 2024**
- Indicadores regionais consolidados:
  - Uso de streaming
  - Acesso à internet domiciliar
  - Presença de televisores
  - Posse de telefone celular

---

## 🧠 Metodologia (resumo)
- Limpeza e padronização dos dados
- Conversão do formato wide → long
- Criação de indicador sintético de **TV conectada estimada**
- Análises comparativas entre infraestrutura e consumo

---

## 📈 Resultados

### 🔹 1. Estimativa de TVs conectadas à internet
Este gráfico representa o **potencial máximo** de domicílios aptos a consumir streaming via TV,
calculado como a interseção entre presença de televisores e acesso à internet.

<img width="613" height="360" alt="Estimativa_de TVs_Conectadas_internet" src="https://github.com/user-attachments/assets/99383c85-7b44-46cc-bb03-090d8c980910" />

**Destaque:** a Região Norte apresenta o menor potencial de TVs conectadas.

---

### 🔹 2. TV conectada × uso de streaming
A relação entre infraestrutura domiciliar e consumo efetivo de streaming.

<img width="613" height="360" alt="Tvs_Conectadas_x_uso_de_streaming" src="https://github.com/user-attachments/assets/cba5007b-067f-4b8f-b552-0227fabac0c5" />


**Destaque:** regiões com maior TV conectada apresentam maior uso de streaming.

---

### 🔹 3. Gráfico-resumo: infraestrutura × consumo
Visão consolidada dos principais indicadores do projeto.

<img width="3000" height="1800" alt="grafico_resumo_streaming_regioes" src="https://github.com/user-attachments/assets/045bff50-7086-4982-bdff-297764d35ca7" />


**Leitura central:**  
Mesmo com menor potencial de consumo via TV, o uso de streaming no Norte se mantém por meio
de dispositivos móveis.

---

## 📊 Análises complementares
Os gráficos abaixo reforçam a adaptação do consumo digital às limitações de infraestrutura
domiciliar na Região Norte.

### 🔸 Internet móvel × uso de streaming
![Internet móvel x streaming](outputs/figures/Internet_movel_x_uso_de_streaming.png)

### 🔸 Uso de celular × uso de streaming
![Celular x streaming](outputs/figures/Uso_de_celular_x_uso_de_streaming.png)

---

## ✅ Conclusões
- O menor consumo de streaming via TV no Norte **não é causado pela ausência de televisores**
- A limitação está na **infraestrutura de conectividade domiciliar**
- O consumo digital se adapta por meio do uso intensivo de celular e internet móvel
- O comportamento observado reflete desigualdades estruturais de acesso

---

## 🛠️ Tecnologias Utilizadas
- R
- tidyverse
- ggplot2
- janitor
- stringr
- scales
- RMarkdown

---

## 📌 Observações
- Análise exploratória com dados agregados por região
- Indicadores sintéticos representam estimativas
- Resultados devem ser interpretados com cautela estatística

---

## 👤 Autor
Projeto desenvolvido para fins de **portfólio em Análise de Dados**.
