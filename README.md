# Projeto Dashboard Power BI - Primeiro Dash que fiz


## Dashboard de RH

Este projeto é um **dashboard de indicadores de RH** desenvolvido para acompanhamento de métricas estratégicas e operacionais, utilizando dados de colaboradores, treinamentos, diversidade, desempenho e engajamento.  
O modelo foi construído no **Power BI**, em estilo executivo, com foco em visualização clara e KPIs de alto impacto.

---

## 📊 Estrutura do Dashboard

O dashboard utiliza diversos tipos de gráficos do Power BI, cada um mapeado para métricas específicas de RH.

| Tipo de Gráfico Power BI       | Métrica RH Adaptada                                  | Aba / Fonte na planilha `dados_rh_dashboard.xlsx` |
|--------------------------------|-----------------------------------------------------|-------------------------------------------------|
| Área / Linha                   | Evolução de colaboradores                           | `Evolucao_Colaboradores`                        |
| Pizza / Donut                  | Gênero, departamento, tipo de trabalho             | `Genero`, `Departamento`, `Tipo_Trabalho`      |
| Card Numérico                  | Total ativos, contratações, desligamentos          | `Cards`                                         |
| Barras Horizontais             | Permanência média, cargos                           | `Permanencia`, `Cargos`                         |
| Barras Verticais               | Treinamentos por setor, desempenho                  | `Treinamentos`, `Desempenho`                    |
| Círculo com número / KPI       | Turnover, horas treinadas, feedbacks               | `Indicadores_Circulares`                        |
| Blocos 01 / 02 / 03            | Tempo de contratação, eNPS, adesão a treinamentos  | `Blocos`                                        |
| Switches / Filtros visuais     | Presencial / Híbrido / Remoto                       | `Switches`                                      |
| Gantt / Stacked Horizontal     | Tempo de casa ou pipeline de RH                     | `Pipeline_TempoCasa`                            |
| Pirâmide (com %)               | Indicadores de diversidade                           | `Diversidade`                                   |

---

## 🎨 Tema Visual

- Paleta de cores:
  - **Roxo**: Cor principal
  - **Rosa**: Cor secundária
  - **Amarelo claro**: Destaques e métricas positivas
- Estilo: Executivo, limpo, com foco em **KPI cards**, gráficos de tendência e indicadores estratégicos.

## Imagens
<img width="600" height="700" alt="image" src="https://github.com/user-attachments/assets/daf432b3-2fb2-4975-9a57-8fe447111da2" />


---

## 🗂 Estrutura de Dados

O dashboard utiliza a planilha **`dados_rh_dashboard.xlsx`** como fonte de dados, que contém as seguintes abas:

1. `Evolucao_Colaboradores` — evolução mensal do número de colaboradores  
2. `Genero` — distribuição por gênero  
3. `Departamento` — número de colaboradores por departamento  
4. `Tipo_Trabalho` — quantidade de colaboradores por tipo de trabalho (presencial, híbrido, remoto)  
5. `Cards` — KPIs numéricos: total ativos, contratações, desligamentos  
6. `Permanencia` — permanência média por departamento  
7. `Cargos` — quantidade de colaboradores por cargo  
8. `Treinamentos` — treinamentos realizados por setor  
9. `Desempenho` — desempenho médio por departamento  
10. `Indicadores_Circulares` — KPIs circulares: turnover, horas treinadas, feedbacks  
11. `Blocos` — métricas paralelas: tempo de contratação, eNPS, adesão a treinamentos  
12. `Switches` — filtros visuais para tipo de trabalho  
13. `Pipeline_TempoCasa` — tempo de casa e pipeline de colaboradores (para gráfico Gantt)  
14. `Diversidade` — indicadores de diversidade (%)

---

## ⚙ Funcionalidades

- Visualização rápida de **indicadores-chave de RH**  
- Comparação de métricas entre **departamentos e cargos**  
- Segmentação por **tipo de trabalho (presencial, híbrido, remoto)**  
- Controle de evolução ao longo do tempo com **gráfico de linha**  
- Avaliação de **diversidade e inclusão** via gráfico de pirâmide  
- Apresentação de KPIs estratégicos via **cards e indicadores circulares**

---









