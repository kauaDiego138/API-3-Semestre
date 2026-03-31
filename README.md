# API-3-Semestre (Grupo - LOGISAFE)
<br>

## Aprendizado por Projeto Integrado (API) - Template

Template para os projetos de API, ensinando na utilização do repositório digital "GitHub". 

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos.

## Cliente
CADI / ONSV

<br>

## Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Equipe](#Equipe)
* [Backlog do produto](#Product-Backlog)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Registro das Sprints](#Registro-das-Sprints)

<br>


## Projeto (API) 
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. 
Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO). 
Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC com definição das datas do kickoff e das sprint

O projeto tem como objetivo a criação de um sistema utilizando diferentes fontes de dados decorrente dos anos de 2015 há 2025, criando um  Business Intelligence para a análise da segurança viária em todos os estados do Brasil.

## Equipe
|    Função     | Nome                                |  GitHub        |   Linkedln   |                                                                                                                                 
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | -----------------------------------------------------------------: |
|  Product Owner|   Kauã Diego de Sousa Manoel | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/KauaDiego138)  | [![LinkedIn Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/kauã-diego-manoel-b7069a34b)
|  Scrum Master | Lucas Daniel da Silva Faria  | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasDaniel7777)    |  [![LinkedIn Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-daniel-0349b83bb)
|  Team Member  | Daniel Junior Soares de Oliveira |[![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DanielJunior777) | [![LinkedIn Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-junior-9b49a3304/)
|  Team Member  | Fabiano Almeida Cardoso de Souza | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Fabiano1301)| [![LinkedIn Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/fabiano-almeida-854646386/)
|  Team Member  | Julio Eduardo Bustamante Mancisidor| [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/mancisidor2024)| [![LinkedIn Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://br.linkedin.com/in/julio-eduardo-bustamante-mancisidor-753576387)


## Objetivo do Projeto
O projeto objetiva implementar uma solução de Business Intelligence para a análise da segurança viária no Brasil. Através de dashboards dinâmicos, a ferramenta mensura índices de eficiência e desempenho em cidades de grande porte (acima de 250 mil habitantes), permitindo a identificação de gargalos críticos e o suporte à tomada de decisão baseada em dados.

## Tecnologias Utilizadas

* Jira Software
* Power BI
* Microsoft Excel
* Slack
* Python (Colab)
* Mysql

<br>

## Product Backlog

| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
| 1 | Alta | Como analista de dados, quero acessar bases públicas da PRF, DATASUS, DENATRAN e IBGE para iniciar a integração das informações de segurança viária,identificando e organizando dados sobre acidentes, frota de veículos e população, garantindo que estejam estruturados e prontos para uso nas próximas etapas  |  3 horas  | 1  |
| 2 | Alta |Como analista, quero visualizar os dados no Python/Google Colab para entender sua estrutura, identificando colunas, tipos de dados e possíveis inconsistências, afim de obter uma visão inicial das bases. |  5 horas  | 1      |
| 3 | Alta | Como analista, quero receber dados limpos e padronizados para garantir consistência e confiabilidade nas análises, com tratamento de valores nulos, remoção de duplicidades e padronização das informações. | 6 horas | 1  |
|4  | Alta | Como analista, quero acessar os dados de acidentes com veículos pesados para focar a análise nesse tipo de sinistro, permitindo identificar padrões e características específicas dessas ocorrências.  |   7 horas    | 1   |
| 5 | Alta | Como analista, quero ter as variáveis organizadas (estado, município, ano e tipo de veículo) para facilitar análises e cruzamentos futuros, garantindo uma estrutura clara e padronizada dos dados. | 4 horas  | 1  |
| 6 | Alta | Como gestor de transporte, quero visualizar a taxa de mortalidade por estado para entender o impacto dos acidentes com veículos pesados, permitindo identificar regiões mais críticas. | 5 horas | 2|
| 7 | Alta | Como cientista de dados, quero acessar os dados necessários para calcular a taxa de mortes por 100 mil habitantes, permitindo comparações mais justas entre estados com diferentes populações. | 5 horas | 2 |
| 8 | Alta | Como analista de mobilidade, quero receber indicadores de sinistros por 10 mil veículos da frota para avaliar o risco relativo da circulação, considerando o volume de veículos em cada região. | 4 horas | 2 |
| 9 | Alta | Como pesquisador de segurança viária, quero acessar dados históricos de mortalidade entre 2015 e 2025 para analisar a evolução ao longo do tempo e identificar tendências relevantes. | 6 horas | 2 |
| 10 | Média | Como gestor público, quero visualizar os estados com maior taxa de letalidade para apoiar a priorização de ações e políticas públicas | 4 horas | 2 |
| 11 | Média | Como analista estratégico, quero comparar os indicadores estaduais com a média nacional para avaliar o desempenho relativo de cada região. | 3 horas | 2 |
| 12 | Alta | Como analista de dados, quero visualizar um dashboard interativo no Power BI para acompanhar os indicadores de segurança viária, facilitando a análise e a tomada de decisão. | 6 horas |  3 |
| 13 | Alta | Como gestor de transporte, quero visualizar indicadores de mortalidade, severidade e sinistros por estado para entender o cenário nacional e identificar regiões mais críticas.| 4 horas | 3 | 
| 14 | Alta | Como cientista de dados, quero acessar dados integrados de frota, população e motocicletas no dashboard para permitir análises mais completas e indicadores mais precisos| 4 horas | 3 |
| 15 | Alta | Como analista de segurança viária, quero visualizar um ranking de eficiência dos municípios com mais de 250 mil habitantes para identificar os mais seguros e apoiar análises comparativas. | 6 horas| 3 |
| 16 | Média | Como gestor público, quero visualizar os municípios mais seguros e mais perigosos para facilitar a interpretação dos resultados e a priorização de ações. | 3 horas | 3 |
| 17 | Média | Como equipe de desenvolvimento, queremos acessar e versionar os artefatos do projeto no GitHub para garantir organização, rastreabilidade e controle das alterações. | 2 horas | 3 |

<br>

## APP de tarefas do grupo LOGISAFE:
https://LogSafe.base44.app

<br>

## Registro das Sprints

|      Sprint       |  Previsão  |  Status  | Histórico |
|-------------------|------------|----------|-----------|
|        01         | 14/04/2026 | a fazer  | [MVP](https://github.com/kauaDiego138/API-3-Semestre/blob/848039befbb5e511ef0f810240ca86ece5a88297/MVPS/mvp%201.md) |
|        02         | 12/05/2026 | a fazer  | [MVP](https://github.com/kauaDiego138/API-3-Semestre/blob/377de1c967c349ac2fdbe10bd4bedbe00eb9edb8/MVPS/mvp%202.md)  |
|        03         | 02/06/2026 | a fazer  | [MVP]([MVP/sp3.md](https://github.com/kauaDiego138/API-3-Semestre/blob/831ad93b6dca86770d0d1a86e07d03c13d5ce1a6/MVPS/mvp%203.md))  |
| Feira de Soluções | 18/06/2026 | a fazer  | |

