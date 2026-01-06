# 📊 Tibia Coin & Farming Data Analysis

Projeto pessoal de **análise de dados aplicada** focado no controle financeiro, análise de desempenho e tomada de decisão baseada em dados, utilizando um mercado virtual (Tibia) como fonte de dados reais e imperfeitos.

> Apesar de o contexto ser um jogo, os problemas abordados são equivalentes aos encontrados em análises financeiras, de mercado e de performance no mundo real.

---

## 🎯 Objetivo do Projeto

- Monitorar ganhos diários (em KK) de diferentes atividades
- Converter ganhos para Tibia Coins (TC) e valores monetários
- Analisar preços de mercado evitando ruídos e outliers
- Avaliar consistência de ganhos ao longo do tempo
- Criar cenários de esforço, metas e dias disponíveis (folgas)

---

## 🧠 Principais Perguntas Respondidas

- Qual foi o desempenho diário, mensal e anual?
- A **média** ou a **mediana** representa melhor minha performance?
- Qual é um preço de Tibia Coin **realista**, considerando liquidez?
- Quantos dias preciso jogar para atingir uma meta?
- Quantos dias posso “folgar” sem comprometer o objetivo mensal?

---

## 🧩 Estrutura da Análise

### 📁 Extrato
- Registro de conversões de Tibia Coins para R$
- Controle por data real
- Cálculo automático de preço por **250 TC** (lote real de mercado)
- Critério documentado para evitar distorções de preço

### 📁 Resumo Mensal
- Total de ganhos em KK
- Média e mediana diária
- Conversão para TC
- Projeção de dias necessários para atingir metas

### 📁 Planejamento e Cenários
- Quantidade de dias do mês
- Dias efetivamente jogados
- Simulação de dias extras / folgas
- Comparação entre cenário médio e cenário mediano

---

## 📊 Decisões Analíticas Importantes

### Média vs Mediana
- **Mediana** usada para métricas sensíveis a outliers
- **Média** usada para volume total e projeções
- Ambas mantidas para contexto e comparação

### Preço do Tibia Coin
> O valor do Tibia Coin utilizado é o **menor preço entre as ofertas com maior volume disponível**, priorizando liquidez e evitando ruídos ou valores não representativos do mercado.

Esse critério reflete:
- Preço operacional real
- Intenção de mercado
- Sustentabilidade do valor

---

## 🛠️ Ferramentas Utilizadas

- Google Sheets / Excel
- Fórmulas condicionais (SUMIFS, IF, DATE)
- Agregações temporais (dia, mês, ano)
- Organização e modelagem de dados

---

## 📌 Aprendizados

- Importância de dados bem modelados antes da análise
- Impacto de outliers em métricas simples
- Valor da documentação de critérios analíticos
- Diferença entre dado “teórico” e dado “utilizável”
- Planejamento baseado em capacidade real, não ideal

---

## 🚀 Próximos Passos (Possíveis Evoluções)

- Visualizações em Power BI
- Migração parcial para SQL ou Python
- Análise comparativa entre atividades (bosses vs hunts)
- Automatização de coleta de preços

---

## 📎 Observação Final

Este projeto foi desenvolvido como **iniciativa pessoal**, mas segue princípios aplicáveis a contextos profissionais de análise de dados, planejamento e tomada de decisão baseada em evidências.
