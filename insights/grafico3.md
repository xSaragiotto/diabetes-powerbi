## 📊 Gráfico: Diagnóstico por Faixa de Risco

![Diagnóstico por Faixa de Risco](../assets/grafico_diagnostico_faixarisco.png)

Este gráfico apresenta a contagem de pacientes agrupados por faixa de risco (`FaixaRisco`), segmentados pelo diagnóstico de diabetes (`Outcome`). Cada barra representa uma faixa de risco (Baixo, Médio, Alto) e está dividida por cor conforme o valor de `Outcome`:

- `Outcome = 0`: Pacientes **sem diagnóstico de diabetes**
- `Outcome = 1`: Pacientes **com diagnóstico de diabetes**

### 🔍 Interpretação

- A faixa **Médio** concentra o maior número de pacientes, com uma proporção significativa de casos positivos.
- A faixa **Alto** apresenta uma proporção maior de pacientes diagnosticados com diabetes, validando o score como indicador de risco.
- A faixa **Baixo** possui poucos pacientes e baixa incidência de diagnóstico.

### 🛠️ Como foi construído

- **Visual**: Gráfico de barras empilhadas horizontal
- **Eixo Y**: `FaixaRisco`
- **Eixo X**: Contagem de `Outcome`
- **Legenda**: `Outcome` (separando 0 e 1)

### 🎯 Objetivo da Visualização

- Validar o score de risco personalizado como ferramenta preditiva
- Identificar a distribuição de diagnóstico entre os perfis de risco
- Apoiar decisões clínicas e estratégias de prevenção com base em dados
