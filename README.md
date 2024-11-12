# Análise de Clientes de Cartão de Crédito: Perfis de Consumo e Padrões de Comportamento

Este projeto analisa dados de clientes de cartão de crédito com o objetivo de entender padrões de comportamento, identificar perfis de consumo e explorar fatores que influenciam o uso do crédito. A análise é conduzida para apoiar estratégias de retenção de clientes e gestão de risco com base em variáveis demográficas e comportamentais.

## Objetivo do Projeto
O objetivo principal é segmentar clientes com base em variáveis como idade, renda, tipo de cartão, e escolaridade. Queremos responder a perguntas como:
- Quais são os padrões de uso de crédito entre diferentes grupos demográficos?
- Existe uma correlação entre a renda e o tipo de uso do cartão?
- Quais fatores podem ser considerados na criação de estratégias de retenção e redução de risco?

## Etapas da Análise

1. **Exploração dos Dados**: Analisamos a distribuição e características das variáveis principais, como idade, renda, limite de crédito, e tipo de cartão. Essa etapa inclui limpeza e padronização dos dados para garantir consistência nas análises.

2. **Análise Descritiva**: Nesta fase, usamos estatísticas descritivas para identificar comportamentos gerais nos dados e explorar relações entre as variáveis, como a influência da renda sobre o limite de crédito ou o impacto da idade no uso do cartão.

3. **Visualização de Dados**: Com o suporte das bibliotecas de visualização, geramos gráficos para ilustrar padrões e tendências, o que facilita a identificação de correlações e insights visuais, como clusters de idade e tipo de cartão preferido.

4. **Modelagem de Segmentação**: Utilizamos técnicas de agrupamento (como o k-means) para segmentar clientes em grupos com características semelhantes, identificando perfis distintos que podem ser úteis em estratégias de marketing e retenção.

## Bibliotecas Utilizadas
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

## Principais Insights Obtidos

1. **Perfis de Clientes**:
   - A análise revelou grupos de clientes com padrões distintos de uso de crédito e preferências em relação a limites de cartão e tipos de transações.
   - Segmentos de clientes de alta renda tendem a usar mais o crédito disponível e têm preferência por cartões premium.

2. **Impacto da Renda e Idade**:
   - Clientes mais jovens mostraram um comportamento de consumo diferente em relação aos clientes mais velhos, com uma maior propensão ao uso frequente de crédito, embora com limites mais baixos.
   - A renda e o tipo de cartão apresentam uma correlação, com clientes de maior renda optando por cartões com benefícios adicionais.

3. **Risco e Retenção**:
   - Identificamos comportamentos que indicam potencial risco, como a utilização frequente do limite total do cartão. Esses insights são valiosos para a criação de estratégias preventivas.
   - Clientes de certos perfis demográficos (ex.: renda média e cartões de nível básico) mostraram uma maior chance de rotatividade, o que sugere a necessidade de estratégias de retenção específicas.

## Como Utilizar este Projeto

1. Clone este repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/seu-repositorio.git
2. Instale as dependências listadas no arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
3. Execute o notebook para visualizar as etapas da análise e os gráficos gerados. Cada célula no notebook representa uma etapa da análise, desde a exploração de dados até a segmentação e visualização de insights.
