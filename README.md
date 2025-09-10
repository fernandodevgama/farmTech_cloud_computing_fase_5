# Análise de Rendimento de Safra Agrícola (farmTech_cloud_computing_fase_5)

## Introdução

Este projeto realiza uma análise detalhada do rendimento de safras agrícolas, utilizando um conjunto de dados para prever a produtividade e identificar tendências. A análise completa, incluindo o código-fonte, as visualizações e as conclusões, está documentada no notebook Jupyter.

## Equipe
- [Gabriel Schuler Barros] (RM: [rm564934])
- [Gabriella Serni Ponzetta] (RM: [rm566296])
- [João Pedro Abreu] (RM: [RM563261])
- [Fernando Ricardo] (RM: [rm566501])
- [João Francisco Maciel Albano] (RM: 565985)

## Entrega 1: Análise Preditiva de Safras

## Vídeo de Demonstração

Para uma visão geral do projeto e da análise, assista ao nosso vídeo de demonstração no YouTube:

[Link para o vídeo de demonstração](https://youtu.be/mUG2QHdiThI)

## Como Utilizar
Acesse: [https://colab.research.google.com/drive/15gt8C-CqMlii8T7JmoXVEsrWzPXL5eOJ?usp=sharing#scrollTo=k2zCNcncbLHA](https://colab.research.google.com/drive/15gt8C-CqMlii8T7JmoXVEsrWzPXL5eOJ?usp=sharing#scrollTo=k2zCNcncbLHA)

Ou:

Para explorar a análise em detalhes, siga os passos abaixo:

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/seu-usuario/farmtech_cloud_computing_fase_5.git
    ```

2.  **Acesse o notebook Jupyter:**

      - O arquivo principal da análise é o `FernandoRicardo_rm566501_pbl_fase5.ipynb`.
      - Abra este arquivo em um ambiente Jupyter para ver o código, as análises e as conclusões.

## Tecnologias Utilizadas

  - Python
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Jupyter Notebook


## Entrega 2: Análise de Custos na Nuvem AWS

### Vídeo de Demonstração

Assista ao vídeo da Entrega 2 para uma demonstração da comparação de custos e recursos usando a Calculadora AWS:

[Link para o vídeo de demonstração da Entrega 2](https://youtu.be/oxlzB0FDWaE)

### 1. Estimativa de Custos: São Paulo vs. Virgínia do Norte

Utilizando a Calculadora de Preços da AWS, realizamos uma estimativa de custos para uma instância Linux (`t3.micro`) com 2 CPUs, 1 GiB de memória e 50 GB de armazenamento, operando em modo *On-Demand* (100% de utilização).

A tabela abaixo compara os custos mensais entre as duas regiões:

| Região | Custo Mensal (USD) |
| :--- | :--- |
| US East (N. Virginia) | $12,59 |
| South America (Sao Paulo) | $21,76 |

A análise mostra que a região da **Virgínia do Norte (EUA)** oferece a solução com o menor custo mensal.

### 2. Escolha da Região: Custo vs. Desempenho e Conformidade

Embora a Virgínia do Norte seja mais barata, para o nosso projeto, a escolha mais adequada é a região de **São Paulo (BR)**. Esta decisão é baseada em dois fatores críticos:

* **Baixa Latência:** A proximidade física com os sensores no Brasil é essencial para garantir o **acesso rápido aos dados**, minimizando atrasos e otimizando o desempenho da API e do modelo de Machine Learning.
* **Soberania de Dados:** Manter os dados em território nacional é fundamental para cumprir com as **restrições legais**, como a LGPD, que regulamenta o armazenamento e a transferência de informações para o exterior.

A escolha por São Paulo, portanto, prioriza o desempenho e a segurança jurídica da aplicação em detrimento do menor custo.

---

## Licença

Este projeto está sob a licença [Creative Commons CC0 1.0 Universal](https://www.google.com/search?q=LICENSE).
