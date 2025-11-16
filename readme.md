# Previsão de Acidentes em Rodovias de São Paulo

Trabalho desenvolvido para a disciplina de **Machine Learning**, com o objetivo de **prever a quantidade de acidentes em rodovias do estado de São Paulo** ao longo de um ano e **propor recomendações de pontos de melhoria** para reduzir a ocorrência desses eventos.

---

## Contexto do Projeto

Os acidentes rodoviários representam um grave problema de segurança pública e têm impactos sociais e econômicos significativos.  
Com base em dados históricos de acidentes e características das rodovias, este projeto busca **criar um modelo de aprendizado de máquina** capaz de estimar o número de acidentes futuros, auxiliando na **tomada de decisão e no planejamento de políticas preventivas**.

---

## Objetivos

- Desenvolver um modelo de **previsão de acidentes** por rodovia e período.  
- Analisar **fatores que influenciam** a ocorrência de acidentes (ex: tipo de rodovia, tráfego, clima, extensão, conservação, etc.).  
- **Identificar pontos críticos** e sugerir **recomendações de melhorias** com base nas previsões.  
- Aplicar **técnicas de aprendizado supervisionado** e validação de modelos.

---

## Metodologia

1. **Coleta de dados** (estamos aqui atualmente)
   - Fontes públicas, como DER-SP, DNIT, Infosiga-SP, entre outras.  
   - Dados complementares sobre infraestrutura, tráfego e clima.

2. **Pré-processamento**  
   - Limpeza, tratamento de valores ausentes e padronização.  
   - Engenharia de atributos e transformação de variáveis categóricas.

3. **Análise exploratória (EDA)**  
   - Visualização de padrões espaciais e temporais.  
   - Correlações entre variáveis explicativas e número de acidentes.

4. **Modelagem preditiva**  
   - Modelos testados: Regressão Linear, Random Forest, XGBoost, entre outros.  
   - Avaliação de desempenho usando métricas como MAE, RMSE e R².

5. **Recomendações**  
   - Análise dos pontos críticos.  
   - Sugestões de ações preventivas e melhorias em infraestrutura.