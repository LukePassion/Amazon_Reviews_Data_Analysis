# Análise de Dados de Resenhas da Amazon

## Descrição do Projeto

Este projeto consiste em uma análise detalhada de um conjunto de dados contendo resenhas de clientes da Amazon ao redor do mundo.
A análise foi realizada utilizando o PySpark no ambiente Databricks, com o objetivo de identificar padrões, tendências e insights relevantes sobre a qualidade do serviço da Amazon
e o comportamento dos clientes.

## Objetivos

1. **Análise Demográfica e Geográfica**:
   - Classificar países em grupos por volume de resenhas.
   - Identificar a distribuição de resenhas por país.

2. **Desempenho ao Longo do Tempo**:
   - Analisar o desempenho das resenhas ao longo de períodos específicos.
   - Avaliar a sazonalidade e tendências.

3. **Identificação de Clientes Influentes**:
   - Determinar os clientes com maior número de resenhas.
   - Avaliar a distribuição geográfica desses clientes influentes.

4. **Qualidade e Relevância das Avaliações**:
   - Analisar o comprimento das resenhas e sua relação com as classificações.

5. **Qualidade Global do Serviço**:
   - Avaliar métricas como médias de classificações, desvio padrão e a proporção de resenhas positivas e negativas.
   - Determinar insights gerais sobre a percepção do serviço pela base de clientes.

## Ferramentas e Tecnologias Utilizadas

- **PySpark**: Para processamento e análise de dados em larga escala.
- **Databricks**: Ambiente colaborativo para execução de tarefas de análise.
- **Python**: Para manipulação de dados e aplicação de funções personalizadas.
- **Linguagem SQL**: Para consultas e operações em conjunto com o PySpark.

## Estrutura do Projeto

### **Etapa 1: Análise Demográfica e Geográfica**
- Classificação de países em grupos de "High Volume", "Medium Volume" e "Low Volume" com base no número de resenhas.
- Identificação dos países pertencentes a cada grupo.

### **Etapa 2: Desempenho ao Longo do Tempo**
- Conversão das datas das resenhas para formato padrão.
- Análise da distribuição das resenhas por ano e mês.

### **Etapa 3: Identificação de Clientes Influentes**
- Determinação dos clientes com maior número de resenhas.
- Análise da distribuição geográfica dos clientes mais influentes.

### **Etapa 4: Qualidade e Relevância das Avaliações**
- Análise do comprimento das resenhas (curtas, médias e longas).

### **Etapa 5: Qualidade Global do Serviço**
- Cálculo da média, desvio padrão e outras estatísticas das classificações atribuídas pelos clientes.
- Determinação de métricas gerais para avaliar a percepção dos serviços da Amazon.

## Resultados e Insights

1. **Grupos por Volume de Resenhas**:
   - Países com maior volume de resenhas demonstraram diferenças significativas na experiência e percepção do serviço.

2. **Tendências Temporais**:
   - Picos de resenhas foram identificados em determinados períodos, indicando sazonalidade.

3. **Clientes Influentes**:
   - Um pequeno grupo de clientes foi responsável por uma quantidade desproporcional de resenhas, com distribuição geográfica concentrada em poucos países.

4. **Comprimento das Resenhas**:
   - Resenhas curtas tendem a ter classificações mais altas, enquanto resenhas longas indicam uma experiência mais detalhada, frequentemente com tom negativo.

5. **Qualidade Global do Serviço**:
   - A média geral das classificações foi satisfatória, mas com variações significativas em diferentes regiões.

## Conclusão

Este projeto fornece uma visão abrangente sobre como os clientes interagem com os serviços da Amazon, bem como suas percepções e tendências comportamentais.
A análise revela informações valiosas que podem ser usadas para melhorar estratégias de marketing, atendimento ao cliente e políticas de qualidade do serviço.

## Como Executar o Projeto

1. **Pré-requisitos**:
   - Conta no Databricks.
   - Instalação do Apache Spark e PySpark.

2. **Configuração**:
   - Faça upload do conjunto de dados no ambiente Databricks.
   - Execute os notebooks contendo o código PySpark.

3. **Conjunto de Dados**:
   - O dataset utilizado foi obtido da plataforma [Kaggle](https://www.kaggle.com/).

4. **Resultados**:
   - As análises estão organizadas em tabelas e gráficos gerados diretamente no Databricks.

## Licença

Este projeto está licenciado sob a Licença MIT. Sinta-se à vontade para usá-lo e modificá-lo conforme necessário.
