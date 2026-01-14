    Dashboard Startups Aceleradas

Dashboard desenvolvido para apresentar os negócios acelerados pela organização, permitindo cruzamentos avançados de filtros (região, setor, estágio, ano, perfil dos empreendedores, entre outros) e extração de dados segmentados em CSV, apoiando principalmente o time de comunicação e a gestão interna.

O projeto partiu de um cenário em que não existia uma base de dados centralizada. Foi necessário consolidar informações dispersas de diferentes programas em um repositório único (datalake) e, a partir dele, estruturar uma base tratada que alimenta o dashboard. Um dos principais desafios foi lidar com heterogeneidade entre programas, startups participantes de múltiplas edições e remoção de duplicidades, garantindo consistência e confiabilidade dos dados.

O dashboard permite responder perguntas como: quantas startups do Sudeste atuando em Saúde foram aceleradas em 2024? ou quais negócios do Nordeste trabalham com Inteligência Artificial no mercado B2B?. Entre os principais indicadores estão o número de negócios acelerados, perfil dos empreendedores (gênero, etnia, região), setores de atuação, estágio de maturidade e os Objetivos de Desenvolvimento Sustentável (ODS) da ONU representados.

A solução foi construída no Looker Studio, com ETL prévio e padronização de dados, e é utilizada internamente como ferramenta recorrente de consulta estratégica. O cenário apresentado é real, com dados anonimizados.

![image](https://github.com/cassianojaques/Dashboards/blob/main/dashboard%20acelerados.png?raw=true)
---


    Painel do Empreendedor

Dashboard desenvolvido para acompanhar a jornada de aceleração de cada negócio participante, centralizando informações operacionais e os principais links e materiais utilizados ao longo do programa, além do controle de presenças e ausências em encontros e eventos.

O painel é destinado diretamente ao empreendedor. Cada negócio possui acesso apenas ao seu próprio dashboard, sem visibilidade sobre os demais participantes. Essa individualização foi viabilizada por meio de uma combinação de parâmetros e filtros por ID, permitindo a criação de um único modelo de dashboard replicável para todos os negócios do programa.

Os dados são atualizados automaticamente a partir de uma base em Google Sheets, que serve como fonte do painel. O controle de presença é realizado com base nas respostas aos formulários de feedback de cada encontro ou evento; na ausência de resposta, o participante é considerado ausente, garantindo um critério simples e consistente de acompanhamento.

A solução foi construída no Looker Studio, com foco em automação, escalabilidade e baixo esforço operacional, eliminando controles manuais e facilitando o acompanhamento contínuo da participação dos negócios ao longo da jornada de aceleração.

![image1](https://github.com/cassianojaques/Dashboards/blob/main/painel%20empreendedeor1.png?raw=true)
![image2](https://github.com/cassianojaques/Dashboards/blob/main/painel%20empreendedor2.png?raw=true)
