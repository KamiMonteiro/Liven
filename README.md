# Desafio Brasileirão 📊

Repositório com a análise completa do Campeonato Brasileiro Série A, integrando dados de partidas, estatísticas, cartões e gols. A análise contempla a construção de bases, visualizações -  tabelas comparativas -, além de insights sobre fatores que impactam o resultado das partidas.

---

## 📁 Estrutura de arquivos

- `data/`
  - Dados `.csv`: full do campeonato, estatísticas, cartões, gols, etc.
- `desafio_brasileirao.ipynb`
  - Notebook principal com todo o pipeline: limpeza, unificação, análises e visualizações.
- `README.md`
  - Documentação do projeto.
- `LEGEND.md`
  - Explicação das colunas das principais tabelas usadas.

---

## 🧠 Objetivos

1. **Limpeza e integração de bases**
   - Garantir que apenas partidas com dados completos sejam mantidas.
   - Remover dados NaN redundantes.
2. **Construção de base unificada**
   - Criação de `df_merged` com estatísticas do mandante e visitante lado a lado, e resultado da partida.
3. **Análise exploratória**
   - Gráficos comparativos: posse, chutes, escanteios, cartões, faltas, passes, etc.
   - Tabela comparativa de métricas por resultado.
4. **Insights**
   - Ver se posse de bola está relacionada a vitórias.
   - A vantagem de jogar em casa (mandante).
   - Eficácia ofensiva (chutes no alvo vs posse).

---

## 🚀 Como executar

```bash
git clone https://github.com/KamiMonteiro/Liven.git
cd Liven
pip install -r requirements.txt
jupyter lab
# ou jupyter notebook
