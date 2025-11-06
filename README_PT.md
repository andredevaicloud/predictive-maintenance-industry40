# ⚙ Manutenção Preditiva para Indústria 4.0 (Análise de Dados IoT)

[![Status](https://img.shields.io/badge/Status-Concluído%20V1-brightgreen.svg)]()
[![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue.svg)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-Projeto-lightgrey.svg)]()

## Visão Geral do Projeto

Este projeto é uma solução fundamental de Machine Learning para *Manutenção Preditiva* (PdM) em um ambiente de manufatura simulado. Ele demonstra a capacidade de analisar dados simulados de sensores de *Internet das Coisas (IoT)* para antecipar falhas de equipamento, um princípio central da *Indústria 4.0*.

O objetivo principal é sair da manutenção reativa para o *agendamento proativo*, economizando custos e minimizando o tempo de inatividade não planejado.

**[Veja a análise completa no Jupyter Notebook: IndustriaI40.ipynb](./IndustriaI40.ipynb)**

---

## Recursos Principais e Valor de Negócio

| Recurso | Descrição | Impacto de Negócio (Indústria 4.0) |
| :--- | :--- | :--- |
| *Simulação de Dados IoT* | Geração de um dataset sintético de séries temporais com anomalias induzidas (estado pré-falha). | *Prontidão de Dados:* Demonstra capacidade de estruturar dados de sensores industriais. |
| *Classificação ML* | Treinamento de um modelo de *Regressão Logística* para classificar o estado do equipamento. | *Eficiência Operacional:* Fornece um alerta binário claro e acionável para as equipes de manutenção. |
| *Zero Falsos Alarmes* | Alcançou *1.00 de Precision* para a classe "Risco de Falha". | *Redução de Custos:* Evita desligamentos desnecessários e gastos com mão de obra não programada. |
| *Alto Recall* | Alcançou *0.93 de Recall* para a classe "Risco de Falha". | *Mitigação de Riscos:* Capturou 93% das falhas iminentes, reduzindo drasticamente o risco de quebra catastrófica não prevista. |

## 🛠 Stack Tecnológico

| Categoria | Ferramentas / Bibliotecas |
| :--- | :--- |
| *Linguagem* | Python 3.x |
| *Ambiente* | Jupyter Notebook |
| *Manipulação de Dados* | Pandas, NumPy |
| *Machine Learning* | Scikit-learn (sklearn) |
| *Visualização* | Matplotlib, Seaborn |

## 🚀 Como Executar Localmente

1.  *Clonar o Repositório:*
    bash
    git clone [SEU LINK DO GITHUB]
    cd predictive-maintenance-industry40
    
2.  *Instalar Dependências:*
    bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    
3.  *Iniciar Jupyter:*
    bash
    jupyter notebook
    
4.  Abra e execute as células do notebook IndustriaI40.ipynb passo a passo.

---

### Autor
* *André dos Reis Soares*
* *LinkedIn:* www.linkedin.com/in/andré-soares-123463346
*