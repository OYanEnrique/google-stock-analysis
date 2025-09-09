[Read in english](README.en.md) 

# A Saga das Ações do Google (GOOG): Uma Jornada de Dados de 2005 a 2023

![Dashboard de Análise de Ações do Google](./assets/google.png)

## ❯ O Início da Jornada: Desvendando a História por Trás dos Números

No palco volátil do mercado de ações, um protagonista se destaca: a ação do Google (GOOG). Por quase duas décadas, sua trajetória foi uma saga de picos, vales e reviravoltas impressionantes. Mas como decifrar a história contida em milhões de pontos de dados brutos?

Este projeto embarca em uma expedição *end-to-end* para fazer exatamente isso: transformar o caos dos números em uma narrativa visual coesa. O objetivo não é apenas analisar, mas revelar os segredos, as tendências e os riscos que moldaram a performance histórica de um gigante da tecnologia.

## 📈 O Conflito: A Trama Escondida nos Dados

Dados de ações, em sua forma bruta, são como um livro escrito em um idioma antigo — cheios de potencial, mas ininteligíveis para a maioria. O verdadeiro conflito não é a falta de informação, mas a ausência de uma história clara.

A missão era forjar um caminho desde a coleta dos dados até a criação de um oráculo visual: um dashboard que não apenas mostrasse gráficos, mas que contasse a saga do Google, permitindo a qualquer um entender o passado para tomar decisões mais informadas sobre o futuro.

### A Forja dos Dados: Onde a Mágica Acontece

Toda grande jornada exige preparação. A nossa começou no ambiente do Jupyter Notebook, onde as ferramentas dos exploradores de dados (**Python**, **Pandas**, **Matplotlib** e **Seaborn**) foram empunhadas para dar forma aos dados.

#### • Etapa 1: A Purificação (ETL) e o Primeiro Obstáculo

O primeiro passo foi purificar o minério bruto — o arquivo `GOOG.csv`. As datas foram convertidas para o formato `datetime`, os tipos de dados foram ajustados e o terreno foi preparado.

No caminho, um desafio surgiu. O **Looker Studio**, nosso destino final, falava um dialeto de datas diferente (`YYYYMMDD`). Foi preciso atuar como um tradutor, convertendo nosso formato de data para garantir uma comunicação perfeita entre o código e a plataforma de BI. Um pequeno passo técnico, mas um obstáculo crucial que foi superado para garantir a integridade da nossa história.

#### • Etapa 2: Encantando os Dados (Engenharia de Features)

Com os dados limpos, era hora de infundir-lhes poder. Novas métricas foram calculadas para nos dar uma visão além do alcance, transformando dados simples em insights poderosos:

* **Médias Móveis Simples (SMA 50 & 200):** Duas lentes mágicas para observar tendências de curto e longo prazo, revelando potenciais sinais de compra e venda.
* **Retorno Diário:** O pulso do mercado, medindo a vitória ou a derrota de cada dia em termos percentuais.
* **Volatilidade (50 dias):** Um medidor de tempestades, quantificando o risco e a incerteza da jornada.

## 💡 O Clímax: O Oráculo do Looker Studio

A jornada culmina aqui. Onde antes havia apenas linhas de código e tabelas, agora existe um portal interativo e dinâmico. O dashboard no **Looker Studio** é o nosso mapa do tesouro revelado, onde cada gráfico se une para contar a história completa.

**🔗 Explore a Saga Você Mesmo: [Acesse o Dashboard Interativo](https://lookerstudio.google.com/reporting/8f839b22-f0f4-4a22-88e2-38b560468476)**

O painel revela:
* **Os Grandes Feitos:** KPIs de Preço Máximo, Mínimo e Volume Médio.
* **A Linha do Tempo da Saga:** A evolução do preço de fechamento ao longo do tempo.
* **As Correntes do Mercado:** A dança das Médias Móveis de 50 e 200 dias, indicando as marés de tendência.
* **O Clamor da Batalha:** O volume de ações negociadas, mostrando os dias de maior interesse e atividade.
* **O Risco da Aventura:** A volatilidade histórica, mapeando os períodos de calmaria e turbulência.

## 🎓 As Lições da Saga: Principais Aprendizados

Esta expedição nos deixou três grandes aprendizados:

1.  **A Torre de Babel dos Dados:** Aprendi que cada ferramenta tem seu próprio "idioma". A necessidade de converter as datas para `YYYYMMDD` mostrou que a preparação de dados para BI é um ato de tradução, garantindo que a história não se perca entre diferentes sistemas.

2.  **A Alquimia do Código:** O maior desafio não foi apenas calcular as Médias Móveis, mas traduzir seus cruzamentos (como o famoso "Golden Cross") em um insight visual claro no dashboard. Foi como transformar o chumbo do código no ouro da análise de negócio.

3.  **A Arte do Contador de Histórias:** Estruturei o dashboard para contar uma narrativa, posicionando os gráficos de preço, volume e volatilidade de forma a revelar suas correlações. Isso solidificou minha habilidade de transformar dados brutos em uma história visual coesa e de fácil compreensão.

---

## 🛠️ O Arsenal do Aventureiro: Ferramentas e Tecnologias

* **Linguagem de Programação:** Python 3
* **Bibliotecas de Análise:** Pandas, Matplotlib, Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook
* **Ferramenta de BI e Visualização:** Google Looker Studio
* **Fonte dos Dados:** [Kaggle Dataset](https://www.kaggle.com/datasets/henryshan/google-stock-price) | Formato CSV

---

## 📂 O Mapa do Tesouro: Estrutura do Repositório

```
├── GOOGLE_limpo.xlsx                # O mapa final: dataset limpo e pronto para o BI
├── google_stock_prices.ipynb       # O diário de bordo: notebook com toda a jornada de análise
├── README.md                       # O pergaminho que narra a saga (este arquivo)
└── assets/
    └── google.png                  # O retrato da nossa descoberta: imagem do dashboard
```

---

## 🚀 Recrie a Jornada: Como Executar o Projeto

Para replicar esta análise e desvendar os dados por conta própria, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/OYanEnrique/google-stock-analysis.git
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd google-stock-analysis
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
4.  **Abra o diário de bordo:**
    ```bash
    jupyter notebook google_stock_prices.ipynb
    ```

---

## 👨‍💻 O Arquiteto da Análise

* **Yan Enrique**
* **LinkedIn:** [https://www.linkedin.com/in/yanenrique/](https://www.linkedin.com/in/yanenrique/)
* **GitHub:** [https://github.com/OYanEnrique](https://github.com/OYanEnrique)
* **Landing page:** [https://yanenrique.carrd.co](https://yanenrique.carrd.co)


---
