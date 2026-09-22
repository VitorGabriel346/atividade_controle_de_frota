# 🚚 Sistema de Controle e Análise de Frota Automotiva

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)]()

---

## 📌 Visão Geral do Projeto

Este projeto consiste na **análise exploratória de dados (EDA)** e desenvolvimento de um script em Python focado no controle operacional e financeiro de uma frota corporativa de veículos. O objetivo principal é transformar dados brutos de telemetria e cadastro de veículos em **indicadores operacionais (KPIs)** para otimizar custos com manutenção e abastecimento.

---

## 🎯 Problema de Negócio

Gestores de frota enfrentam desafios constantes na identificação de gargalos operacionais, tais como:
- Custos elevados e não previstos com manutenção preventiva e corretiva.
- Baixa eficiência no consumo de combustível por categoria de veículo.
- Falta de visibilidade sobre a disponibilidade da frota por filial e departamento.

---

## 📊 KPIs e Indicadores Analisados

A análise foca nos seguintes eixos estratégicos:

1. **Status Operacional da Frota:** Mapeamento de veículos Ativos, em Manutenção e Inativos.
2. **Eficiência Energética:** Análise da média de km/l por tipo de combustível (Flex, Diesel, Híbrido) e modelo.
3. **Gestão Financeira de Manutenção:** Custo acumulado no ano (*YTD - Year to Date*) por departamento e filial.
4. **Controle Preventivo:** Acompanhamento de datas relativas à última e próxima revisão agendada.

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python 3
- **Manipulação e Tratamento de Dados:** `pandas`, `numpy`
- **Visualização de Dados:** `matplotlib`, `seaborn`
- **Ambiente de Desenvolvimento:** Jupyter Notebook / Google Colab

---

## 📂 Estrutura do Repositório

```text
├── data/
│   └── base_frota_automotiva.csv    # Base de dados estruturada da frota
├── notebooks/
│   └── Sistema_de_controle_de_frota.ipynb  # Notebook com análise e tratamento dos dados
└── README.md                         # Documentação do projeto
