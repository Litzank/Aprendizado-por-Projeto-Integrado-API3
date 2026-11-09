# 📌 MVP - [Aprendizado-por-Projeto-Integrado-API3]

## 🎯 Propósito do MVP

## • Qual problema resolve?
Evolução e reorganização estrutural do BI, dividindo a apresentação em três seções bem definidas para tornar a visualização dos dados mais agradável, fluida e organizada para o usuário.

## • Qual hipótese será validada?
A nova divisão estrutural em três partes (Capa visual, Painel Principal com filtros e Seção de Apoio com motoristas/histórico temporal) melhora a interpretação das informações e a experiência visual na entrega do dashboard.

## • Qual valor será entregue ao usuário final?
Um layout de BI remodelado e intuitivo, trazendo capa de apresentação com identidade visual (GAVCA), dados consolidados com novos filtros e uma seção dedicada a análises operacionais de motoristas, locais fiscalizados e linha do tempo.

---

# 📝 Descrição da Solução
## • Funcionalidades principais incluídas
- **Capa Visual (Tela 1):** Tela inicial de apresentação com logo/arte do projeto e botão de navegação integrado para as telas seguintes.
- **Painel Principal (Tela 2):** Consolidação dos dados essenciais (Total de fiscalizações por cidade, principais fiscais e categorias de serviço) com filtros superiores dinâmicos.
- **Painel de Apoio e Métricas (Tela 3):** 
  - Gráfico de **Principais Motoristas** (frequência de viagens).
  - Análise temporal de **Contagem por Ano, Trimestre e Mês** (histórico detalhado).
  - Detalhamento de **Empresas/Locais** mais fiscalizados.
  - **Mapa da Região** interativo com exibição de coordenadas detalhadas.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Marcus Nascimento, Cliente direto para contato sobre atualizações e feedbacks, querem um programa rápido, responsivo, acessível e que disponibilize informações necessárias de maneira clara.
- **Persona 2:** Carlos Eduardo - Orientador de Projeto - Responsável por auxiliar no desenvolvimento do projeto.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Stories (Sprint 2)                                                                                                     | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------------------------------------------------------|------------|------------|
| US06 | Como gestor de projeto, quero a reestruturação do BI em três telas, para organizar melhor o fluxo de navegação e visualização das informações. | Alta | 01 |
| US07 | Como gestor de projeto, quero uma capa inicial com botões de navegação e identidade visual, para padronizar a apresentação do projeto. | Média | 02 |
| US08 | Como gestor de projeto, quero novos filtros globais no topo do painel, para permitir análises mais dinâmicas por cidade, fiscal e serviço. | Alta | 03 |
| US09 | Como gestor de projeto, quero visualizações sobre frequência de motoristas, histórico temporal e locais recorrentes, para identificar padrões operacionais. | Alta | 04 |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais | Status |
|--------|---------------------|--------|
| 01 | Entrega dos dashboards iniciais, filtros de informações e demonstrações de origem e destino | Concluído |
| 02 | Reorganização em 3 telas (Capa, Principal e Apoio), filtros globais e indicadores de motoristas/temporalidade | Concluído |
| 03 | Integração final de geolocalização e refinamentos visuais de compatibilidade | A Fazer |

---

## 🧳 Critérios de Aceitação

- BI dividido e estruturado em 3 telas operacionais (Capa, Principal e Apoio).
- Capa integrada com arte visual e botão funcional de redirecionamento.
- Filtros superiores de Cidade, Fiscal e Serviço operando em conjunto com os gráficos.
- Gráficos de motoristas, histórico temporal (2018) e empresas validados na Tela 3.

---

## 📈 Métricas de Validação

- Número de telas estruturadas no BI: 3
- Quantidade de filtros globais implementados: 3 (Cidade, Fiscal, Serviço)
- Indicadores operacionais adicionados na Tela 3: Frequência de Motoristas, Histórico Temporal e Empresas Recorrentes
- Validação visual com base nos prints do projeto: Aprovado

---

## 🚀 Próximos Passos
- Refinar os dados de geolocalização e expansão dos mapas interativos.
- Realizar os últimos testes de usabilidade e transição entre as telas do Power BI.
  
---

## 📂 Anexos / Evidências

- PowerBI

![Dashboard](../DOCS/PowerBi/Imagens/PBI-S2-01.png)

---

- PYTHON

<div align="center">
  
![Demo](../DOCS/PYTHON/Videos/PythonS2.gif)

</div>
