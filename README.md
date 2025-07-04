# 🐾 Previsão de Exames por Espécie

Este projeto utiliza séries temporais para prever a quantidade de exames mensais realizados por espécie (como cães, gatos, etc.), com base em dados históricos fornecidos pela clínica/veterinária **LaudeasyVet**.

## 📈 Objetivo

Desenvolver um modelo de previsão para estimar o número de exames do próximo mês, por espécie, auxiliando no planejamento e logística da equipe.

---

## 🧰 Tecnologias Utilizadas

- Python 3.x
- Pandas
- Statsmodels (`SARIMAX`)
- Jupyter Notebook
- Git / GitHub

---

## 📊 Dados

O arquivo `laudos_piloto002.xlsx` contém os dados históricos dos laudos emitidos, organizados por espécie e por mês.

> **Obs:** Os dados foram semi-preparados para fins de modelagem.

---

## 📘 Notebooks

- `Pred_Especies_proximo_mes.ipynb`: Notebook principal com a limpeza dos dados, análise exploratória e modelo SARIMAX aplicado para cada espécie.

---

## ⚙️ Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/pehgamarra/PrevisaoEspecie.git
   cd PrevisaoEspecie
