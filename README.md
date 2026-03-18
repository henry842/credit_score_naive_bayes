# 💳 Credit Score — Previsão de Inadimplência

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![Decision Tree](https://img.shields.io/badge/Decision_Tree-Scikit--Learn-F7931E?style=flat-square)
![Naive Bayes](https://img.shields.io/badge/Naive_Bayes-Scikit--Learn-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Concluído-00d4ff?style=flat-square)

**Classificação de risco de crédito com Árvore de Decisão e Naive Bayes.**

</div>

---

## 📋 Sobre o Projeto

Modelo de Credit Score para prever a probabilidade de inadimplência de clientes com base em variáveis financeiras e comportamentais. Projeto relevante para o setor financeiro, onde decisões de crédito impactam diretamente o negócio.

---

## 🔬 Pipeline

```
Coleta → EDA → Encoding → Análise de Correlação → Train/Test Split → Balanceamento → Modelagem → Avaliação
```

### Técnicas aplicadas:
- **EDA detalhada** — distribuição por perfil de inadimplência
- **Encoding** de variáveis categóricas
- **Balanceamento** — classes desbalanceadas são comuns em crédito
- **Visualização da Árvore** — interpretabilidade das regras de decisão

---

## 🤖 Modelos Comparados

| Modelo | Vantagem |
|--------|----------|
| Decision Tree | Interpretável, regras visíveis |
| Naive Bayes | Rápido, bom para baseline |

---

## 💡 Insights de Negócio

- Variáveis de renda e histórico de pagamento são os preditores mais fortes
- Clientes com múltiplos empréstimos ativos têm maior probabilidade de inadimplência
- A visualização da árvore permite explicar a decisão ao cliente

---

## 🛠️ Tecnologias

- **Scikit-Learn** — Decision Tree, Naive Bayes, métricas
- **Imbalanced-Learn** — balanceamento de classes
- **Pandas / Matplotlib / Seaborn**

---

## 🚀 Como Executar

```bash
git clone https://github.com/henry842/Projeto-de-Credit-Score.git
cd Projeto-de-Credit-Score
pip install -r requirements.txt
jupyter notebook credit_score.ipynb
```

---

<div align="center">
  <a href="https://github.com/henry842">👤 henry842</a> •
  <a href="https://github.com/henry842?tab=repositories">📂 Outros projetos</a>
</div>

---
---
