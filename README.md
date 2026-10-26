# 📊 Controle Financeiro e Análise de Performance | Power BI

## 📌 Visão Geral

Este projeto apresenta uma solução de Business Intelligence aplicada à gestão financeira, com foco no acompanhamento de receitas, custos, despesas e resultado financeiro.

A partir da consolidação de dados de recebimentos, pagamentos e plano de contas, foi desenvolvido um dashboard interativo no Power BI para acompanhar a evolução financeira, comparar períodos, analisar a composição dos gastos e identificar concentrações relevantes de receita.

Pergunta central do negócio:

Como está o desempenho financeiro da empresa e quais fatores devem ser investigados para apoiar decisões de gestão?

## 🔎 Contexto do Negócio

A empresa registra suas movimentações financeiras em planilhas separadas e utiliza um plano de contas para classificar receitas, custos e despesas. A ausência de uma visão consolidada dificulta o acompanhamento da evolução financeira, a comparação entre períodos e a identificação dos componentes que mais impactam o resultado.

Diante desse cenário, o projeto busca transformar dados financeiros em informações que apoiem o monitoramento do desempenho e a investigação de oportunidades de melhoria na gestão dos recursos.

## 🎯 Perguntas de Negócio

Resultado e rentabilidade

- Qual é o resultado financeiro da empresa ao longo do período?

- Como a margem financeira evolui?

- Como o resultado do ano atual se compara ao ano anterior?

Evolução financeira

- Como os recebimentos evoluem mensalmente?

- Como os custos e as despesas se comportam ao longo do ano?

- Quais meses apresentam variações relevantes nos resultados financeiros?

Análise de recebimentos

- Como os recebimentos se distribuem entre receitas operacionais e não operacionais?

- Quais estados concentram a maior parcela dos recebimentos?

- Como a receita evolui em comparação ao ano anterior?

Análise de pagamentos

- Como os pagamentos se distribuem entre custos e despesas?

- Como os custos e as despesas se dividem entre categorias operacionais e não operacionais?

- Qual é a composição dos custos e das despesas entre valores fixos e variáveis?

- Quais categorias e períodos merecem investigação devido ao seu impacto financeiro?

## 📈 KPIs e Métricas

- Recebimentos: acompanhar o total de entradas financeiras registradas

- Custos: monitorar os custos registrados nos pagamentos

- Despesas: monitorar as despesas registradas nos pagamentos

- Resultado financeiro: avaliar a diferença entre recebimentos e saídas consideradas

- Margem financeira: medir o resultado financeiro em relação aos recebimentos

- Variação anual (%): comparar os valores do período atual com os do período anterior


**Critérios de cálculo**

  Resultado financeiro

     Resultado financeiro = Recebimentos − Custos − Despesas

  Margem financeira

     Margem financeira = Resultado financeiro ÷ Recebimentos

  Variação anual (%)

     Variação anual = (Valor atual − Valor anterior) ÷ Valor anterior

Nota: como a análise utiliza registros de recebimentos e pagamentos, o resultado financeiro apresentado não deve ser interpretado automaticamente como lucro contábil.

## 🧹 Tratamento de Dados — Power Query

O tratamento dos dados foi desenvolvido no Power Query para preparar as informações financeiras para análise.

As etapas contemplam:

- Importação das planilhas de pagamentos, recebimentos e plano de contas.

- Remoção de linhas e colunas desnecessárias.

- Ajuste da estrutura das tabelas e promoção dos cabeçalhos.

- Transformação dos dados de pagamentos para uma estrutura adequada à análise temporal.

- Padronização dos campos utilizados na classificação das movimentações.

- Preparação dos dados para integração e modelagem no Power BI.

O objetivo é estruturar uma base consistente para o cálculo dos indicadores e a construção das análises.

## 🧩 Modelagem e Medidas — Power BI e DAX

A modelagem e as medidas DAX foram utilizadas para consolidar os indicadores financeiros e permitir sua análise por período, classificação, estado e cliente.

Entre os recursos utilizados estão:

- Medidas para cálculo de recebimentos, custos e despesas.

- Cálculo do resultado e da margem financeira.

- Comparação entre ano atual e ano anterior.

- Análises por classificação e tipo de movimentação.

- Segmentação dinâmica entre custos e despesas.

- Títulos dinâmicos de acordo com a seleção do usuário.

## 💡 Principais Insights

A análise visual inicial permite identificar pontos que merecem aprofundamento:

- Evolução dos recebimentos: agosto apresenta um pico de receita, enquanto junho registra um valor inferior aos demais meses observados. É necessário investigar quais movimentações explicam essa variação.

- Concentração geográfica: São Paulo representa a maior parcela dos recebimentos entre os estados exibidos, indicando uma concentração que pode ser quantificada pela participação percentual.

- Composição dos pagamentos: os custos variáveis representam uma parcela relevante dos custos apresentados no dashboard, tornando importante investigar quais contas compõem esses valores.

- Comparação entre períodos: os indicadores permitem avaliar mudanças no desempenho financeiro e identificar quais componentes contribuíram para as variações.

Essas observações são pontos de partida para a investigação analítica. A confirmação dos valores, das medidas e das causas deve preceder conclusões definitivas.

## 🎯 Recomendações ao Negócio

A partir dos indicadores e das perguntas investigativas, as recomendações priorizam:

- Investigar os meses com maiores oscilações de recebimentos, custos e despesas.

- Avaliar a concentração dos recebimentos por estado e cliente.

- Identificar as contas que mais contribuem para os custos e as despesas.

- Comparar períodos equivalentes para distinguir crescimento, redução e efeitos de sazonalidade.

- Utilizar os resultados para apoiar decisões de acompanhamento financeiro e priorização de análises.

As recomendações finais devem estar vinculadas aos achados confirmados nos dados.

## 🔭 Próximos Passos Analíticos

- Analisar a participação percentual por estado e cliente.

- Decompor as variações anuais por categoria financeira.

- Investigar as principais contas responsáveis pelos picos mensais.

- Comparar valores realizados e orçamento, caso os dados estejam disponíveis.

- Analisar tendências e sazonalidade em períodos mais longos.

- Validar continuamente as medidas, os filtros e a reconciliação dos totais entre as páginas.

## b🛠️ Ferramentas

Power BI — visualização e análise dos indicadores.

Power Query — tratamento e preparação dos dados.

DAX — criação de medidas e cálculos analíticos.

Excel — arquivos de origem dos dados financeiros.

## 🔄 Abordagem Analítica

O projeto seguiu uma abordagem orientada à tomada de decisão:

**Demanda do Gestor → Problema de Negócio → Perguntas de Negócio → KPIs → Análise → Insights → Hipóteses → Recomendações**

O objetivo não foi apenas monitorar indicadores, mas interpretar a performance, identificar sinais de atenção e direcionar perguntas que podem apoiar decisões operacionais e gerenciais.

## 🔗 Dashboard**
Link do Projeto: [https://app.powerbi.com/view?r=eyJrIjoiNTVlMTc5YzUtZTNiZC00YWU0LWI0MjAtYzEyMzQwYWZhZGNjIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9  ](https://app.powerbi.com/view?r=eyJrIjoiNmY0N2NkOTMtM2JjNC00ZjAxLWJiNDItYmMxZTRlMTE4ODQ4IiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)

<img width="1273" height="716" alt="image" src="https://github.com/user-attachments/assets/672b51bc-bdc6-488d-9bb4-7dab87c06f01" />
<img width="1270" height="711" alt="image" src="https://github.com/user-attachments/assets/a51fb1a4-ee8b-44d9-958f-6d4bf31a5bb3" />
<img width="1276" height="715" alt="image" src="https://github.com/user-attachments/assets/5e4c36b6-b22a-4139-a928-e821c86cceaa" />




>
