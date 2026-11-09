# Projeto do Terceiro Semestre - Logística - Otimização de Trajetos de Inspeção do IPEM-SP

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos

# Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Equipe](#Equipe)
* [Backlog do produto](#Product-Backlog)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Registro das Sprints](#Registro-das-Sprints)


# Projeto (API) 
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. 

Desenvolvimento de uma plataforma logística para otimizar os trajetos das equipes de inspeção do IPEM-SP com base em dados históricos. A solução aplica Pesquisa Operacional e mapas interativos para criar rotas inteligentes, comparar o cenário real com o otimizado e gerar dashboards de indicadores. Seu objetivo principal é reduzir tempos e distâncias de deslocamento, além de balancear com precisão a carga de trabalho operacional.

# Equipe - GAVCA
<div align="center">
  
![Demo](DOCS/Logo.gif)

|    Função     | Nome                                  |        LinkedIn & GitHub           |
| :--------------------: | :------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |  Luiz Felipe Massa   |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luiz-felipe-m-084620123?utm_source=share_via&utm_content=profile&utm_medium=member_ios) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/felipemassa03)              |
| Scrum Master  |  Pedro Henrique de Sousa Dias  |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](http://linkedin.com/in/pedro-henrique-0b1abb32b) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/pedroworks73-dev)
| Team Member  | João Ricardo Rodrigues Araújo  |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-ricardo-rodrigues-ara%C3%BAjo-705560149?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/trabalhofatec2025)     |
| Team Member   | Rodrigo Luiz Ramos dos Santos  |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-luiz-santos-430081269?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DigdinLogistico)        |
| Team Member |  Augusto Adriano Silva de Oliveira   |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/augustoprofile) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Litzank)              |
|  Team Member  | Isadora Ferreira De Paulo Moura |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/isadora-ferreira-34603a332?utm_source=share_via&utm_content=profile&utm_medium=member_android) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Isadora01if)        | 
</div>

# Objetivo do Projeto
Desenvolver uma solução para apoiar o planejamento das equipes de fiscalização do IPEM-SP, utilizando dados históricos para analisar os deslocamentos, identificar oportunidades de otimização das rotas e melhorar a distribuição das fiscalizações entre as equipes:

* Mapa das fiscalizações 
* Rotas históricas e rotas otimizadas 
* Dashboard de indicadores
* Simulação de cenários 
* Exportação de relatórios 

## Tecnologias Utilizadas

* Power Point
* Power BI
* Microsoft Excel (Office)
* Python (Colab)
* GitHub

## Questões para Análise

Para aprofundar a compreensão sobre o comércio exterior dos municípios paulistas, se deve investigar as seguintes questões (se possível):
*	Como as equipes foram distribuídas historicamente? 
*	Qual seria a melhor distribuição das fiscalizações entre as equipes? 
*	Qual a redução potencial de quilômetros e tempo de deslocamento? 
*	Quais municípios e tipos de fiscalização concentram maior demanda? 
*	Como balancear a carga de trabalho?
*	Como comparar a operação real com a otimizada? 

# Product Backlog

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
| US01 | Como gestor de projeto, quero o dashboard sobre a região do vale do paraíba, para de maneira a primaria focarmos no tratamento das informações da nossa região. | Alta | 3 | 01 |
| US02 | Como gestor de projeto, quero gráfico de fiscalizações, para verificar quais cidades recebem mais fiscalizações por ano e que assim seja possível determinar com maior prioridade quais são os focos dos fiscais. | Média | 2 | 01 |
| US03 | Como gestor de projeto, quero uma determinação dos fiscais, para verificar quais fiscais tem maior taxa de fiscalizações| Média | 4 | 01 |
| US04 | Como gestor de projeto, quero dados de serviço por cidade, para verificar quais tipos de serviços são prestados pelo fiscais| Média | 4 | 01 |
| US05 | Como gestor de projeto, quero uma mapa demonstrativo da cidade, para verificar quais são as regiões tem maior foco de fiscalizações | Média | 5 | 01 |
| US06 | Como gestor de projeto, quero a reestruturação do BI em três telas, para organizar melhor o fluxo de navegação e visualização das informações. | Alta | 1 | 02 |
| US07 | Como gestor de projeto, quero uma capa inicial com botões de navegação e identidade visual, para padronizar a apresentação do projeto. | Média | 2 | 02 |
| US08 | Como gestor de projeto, quero novos filtros globais no topo do painel, para permitir análises mais dinâmicas por cidade, fiscal e serviço. | Alta | 3 | 02 |
| US09 | Como gestor de projeto, quero visualizações sobre frequência de motoristas, histórico temporal e locais recorrentes, para identificar padrões operacionais. | Alta | 4 | 02 |
| US10 | Como gestor de projetos, quero simular diferentes cenários de alocação de equipes e fiscalizações, para apoiar a tomada de decisão estratégica. | Média | 8 | 03 |
| US11 | Como gestor de projetos, quero exportar relatórios técnicos dos cenários analisados, para documentar e comprovar os ganhos de eficiência. | Baixa | 5 | 03 |


# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| Video do Problema | 04/09/2026 | Feito | [Video](https://youtube.com/shorts/7Hbv3pHuFiA)|
| 01                | 02/10/2026 | Feito   | [MVP](MVP/sp1.md)  |
| 02                | 30/10/2026 | Feito   | [MVP](MVP/sp2.md)  |
| 03                | 27/11/2026 | A fazer   | [MVP](MVP/sp3.md)  |
| Feira de Soluções | 03/12/2026 | A fazer   | [MVP](#)  |
