## 📈 Gráfico: Distribuição de Diagnóstico por Faixa Etária

![Distribuição de Diagnóstico por Faixa Etária](assets/grafico2.png)

Este gráfico de linhas compara os níveis médios de glicose entre diferentes faixas etárias, segmentando os dados por diagnóstico de diabetes (`Outcome`). Ele ajuda a visualizar como a glicemia varia com a idade e se há diferenças significativas entre os grupos com e sem diabetes.

### 🔍 Interpretação

- **Eixo X**: Faixa Etária
  - Menor que 20
  - 20 a 29
  - 30 a 39
  - 40 a 49
  - 50 a 59
  - Maior que 60

- **Eixo Y**: Nível médio de glicose

- **Linhas**:
  - 🔵 Linha escura: Pacientes com diagnóstico de diabetes (`Outcome = 1`)
  - 🔵 Linha clara: Pacientes sem diagnóstico (`Outcome = 0`)

### 📊 Principais Observações

- Pacientes **com diabetes** apresentam níveis médios de glicose mais altos em todas as faixas etárias.
- A faixa **menor que 20 anos** tem os **maiores níveis médios de glicose** entre os diagnosticados (157.48).
- Entre os **não diagnosticados**, os níveis são mais baixos e caem drasticamente após os 30 anos.

### 🎯 Objetivo da Visualização

- Identificar se há **padrões consistentes de glicose por idade**.
- Avaliar se a **idade influencia diretamente os níveis glicêmicos** em pacientes com ou sem diabetes.
- Apoiar decisões clínicas e educacionais com base em dados segmentados.

### 🛠️ Construção no Power BI

- **Visual utilizado**: Gráfico de linhas
- **Eixo X**: `FaixaEtaria`
- **Eixo Y**: Média de `Glucose`
- **Legenda**: `Outcome`

> Este gráfico é essencial para entender o comportamento da glicose ao longo da vida e reforça a importância do monitoramento precoce em faixas mais jovens.
