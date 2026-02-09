# 📈 Dashboard de Gestão de Investimentos & Patrimônio 
> **Bootcamp Microsoft Copilot AI + Excel**

Este repositório contém o projeto final de controle financeiro, focado em transformar dados brutos em inteligência estratégica para tomada de decisão. O projeto une a robustez das fórmulas de Excel com a agilidade da Inteligência Artificial (Copilot).

---

## 🛠️ Tecnologias e Metodologias Utilizadas

* **Microsoft Excel Avançado:** Uso de Tabelas Oficiais para garantir a integridade referencial.
* **Power Query (ETL):** Automatização da limpeza e padronização dos dados de entrada.
* **Microsoft Copilot (IA):** Engenharia de prompts para otimização de fórmulas complexas e validação de lógica financeira.
* **Design de Dashboard (UX):** Interface limpa, sem linhas de grade, focada em KPIs (Key Performance Indicators).

---

## 🧠 Glossário de Fórmulas Implementadas

Para garantir a precisão dos cálculos, foram utilizadas as seguintes lógicas:

| Funcionalidade | Fórmula Base | Objetivo Técnico |
| :--- | :--- | :--- |
| **Busca de Ativos** | `=XLOOKUP()` | Substituição do PROCV para buscas mais seguras e rápidas à esquerda e à direita. |
| **Cálculo de Dividend Yield** | `=(Dividendos / Preço_Médio)` | Medir a rentabilidade passiva em relação ao custo de aquisição. |
| **Rentabilidade Total** | `=(Valor_Atual - Custo_Total) / Custo_Total` | Avaliar o ganho ou perda de capital desde o início da carteira. |
| **Lógica de Rebalanceamento** | `=IF(Ativo_Atual < Meta; "Comprar"; "Aguardar")` | Automação da tomada de decisão baseada em metas percentuais. |
| **Extração de Dados** | `=TEXTBEFORE()` | Limpeza de códigos de ativos (tickers) extraídos de fontes externas. |

---

## 📖 Guia de Uso

Para utilizar o simulador de forma eficiente, siga estes passos:

1.  **Entrada de Dados:** Acesse a aba `Base_Dados` e insira suas movimentações (Compra/Venda).
    * *Dica:* Use o formato de Tabela para que o dashboard atualize automaticamente.
2.  **Atualização de Preços:** Clique em `Dados > Atualizar Tudo` para buscar as cotações em tempo real via Excel Data Types.
3.  **Análise no Dashboard:** * Utilize a **Segmentação de Dados** para filtrar por Classe de Ativo (Ações, FIIs, Tesouro).
    * Observe o gráfico de **Evolução Patrimonial** para entender a tendência do seu crescimento financeiro.
4.  **Auditoria com IA:** Utilize o Copilot para perguntar: *"Qual setor da minha carteira está com maior risco?"* ou *"Crie uma projeção de dividendos para os próximos 6 meses baseada no histórico"*.

---

## 👤 Autora

**Jéssica G.** 📍 Varginha - MG | Estudante de RH & Analista de Dados  
*Focada em unir Tecnologia, Processos e Pessoas através da análise inteligente de dados.*

---

📫 **Contato:**
[JESSICA RIBEIRO] - [(https://www.linkedin.com/in/jessica-ribeiro-105814116?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)]
