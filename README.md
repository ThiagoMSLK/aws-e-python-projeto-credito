# 💳 Projeto de Análise de Crédito — AWS & Python

### 📋 Descrição do Projeto

Este projeto foi desenvolvido com o objetivo de analisar dados de crédito utilizando Python e serviços da AWS, com foco em boas práticas de engenharia de dados, otimização de custos e avaliação de viés nos dados.

Inicialmente, os dados foram disponibilizados de forma parcial para reduzir o consumo de armazenamento no Amazon S3 e permitir a análise via consultas SQL no Amazon Athena.
No entanto, durante a exploração, foi identificado que o conjunto reduzido apresentava tendências e viés estatístico, o que comprometia a qualidade da análise.

Diante disso, optou-se por utilizar o conjunto de dados completo, executando a análise fora do ambiente da AWS, diretamente em Python, como forma de preservar a integridade dos resultados sem elevar significativamente os custos de infraestrutura em nuvem.

### 🎯 Objetivos

- Analisar dados de crédito com foco em padrões, riscos e possíveis vieses.

- Realizar tratamento e exploração de dados utilizando Python e SQL (Athena).

- Avaliar trade-offs entre performance e custo no uso de serviços AWS.

- Demonstrar flexibilidade na integração entre nuvem e ambiente local.

### ⚙️ Tecnologias Utilizadas

- Python 3.10+ – processamento, análise e visualização

- Pandas / NumPy / Matplotlib / Seaborn – análise exploratória de dados

- Amazon S3 – armazenamento de dados em nuvem

- Amazon Athena – consultas SQL sobre dados armazenados no S3

- Google Colab – ambiente de desenvolvimento e execução
  
### 🧠 Aprendizados Técnicos

- Identificação e mitigação de viés em dados amostrais.

- Uso combinado de serviços serverless (Athena/Glue) com análise local em Python.

- Controle de custos no uso de infraestrutura AWS.

- Melhoria da eficiência e precisão analítica com dados completos.

###Thiago Martins LK
- <a href="https://www.linkedin.com/in/thiagomartinslk" target="_blank">Meu LinkedIn</a>
- <a href="https://www.kaggle.com/thiagomartinslk" target="_blank">Meu Kaggle</a>
- <a href="https://github.com/ThiagoMSLK" target="_blank">Meu GitHub</a>
