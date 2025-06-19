
---

## 📘 LEGEND.md

```markdown
# Legenda — Colunas do Dataset Unificado

## Identificação da partida
- `partida_id`: ID único da partida
- `mandante`, `visitante`: nomes dos clubes
- `vencedor`: time que venceu (ou string vazia em caso de empate)

## Estatísticas por time
Prefixos em colunas:
- `mandante_`: estatísticas do time da casa
- `visitante_`: estatísticas do time visitante

### Métricas numéricas:
- `posse_de_bola` (%): posse média da bola
- `chutes`, `chutes_no_alvo`: finalizações totais e no alvo
- `passes`: número total de passes
- `precisao_passes`: % de acertos nos passes
- `faltas`: faltas cometidas
- `cartao_amarelo`, `cartao_vermelho`: cartões recebidos
- `impedimentos`: número de impedimentos
- `escanteios`: número de escanteios cobrados

## Resultado e análise
- `resultado`: classificado como “Mandante”, “Visitante” ou “Empate”
- Tabelas comparativas: médias agrupadas por `resultado`
- Gráficos: radar, scatter, barras para posse, chutes, passes etc.

---

## 🎯 Objetivo das análises

- **Gráficos de barras**: avaliam média de posse, chutes, cartões e faltas por resultado
- **Tabela Plotly**: visão comparativa clara entre métricas por resultado
