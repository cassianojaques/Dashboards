📊 Base Centralizada de Startups Aceleradas

Dashboard desenvolvido para apresentar os negócios acelerados pela organização, permitindo cruzamentos avançados de filtros (região, setor, estágio, ano, perfil dos empreendedores, entre outros) e extração de dados segmentados em CSV, apoiando principalmente o time de comunicação e a gestão interna.

O projeto partiu de um cenário em que não existia uma base de dados centralizada. Foi necessário consolidar informações dispersas de diferentes programas em um repositório único (datalake) e, a partir dele, estruturar uma base tratada que alimenta o dashboard. Um dos principais desafios foi lidar com heterogeneidade entre programas, startups participantes de múltiplas edições e remoção de duplicidades, garantindo consistência e confiabilidade dos dados.

O dashboard permite responder perguntas como: quantas startups do Sudeste atuando em Saúde foram aceleradas em 2024? ou quais negócios do Nordeste trabalham com Inteligência Artificial no mercado B2B?. Entre os principais indicadores estão o número de negócios acelerados, perfil dos empreendedores (gênero, etnia, região), setores de atuação, estágio de maturidade e os Objetivos de Desenvolvimento Sustentável (ODS) da ONU representados.

A solução foi construída no Looker Studio, com ETL prévio e padronização de dados, e é utilizada internamente como ferramenta recorrente de consulta estratégica. O cenário apresentado é real, com dados anonimizados.

![image](https://github.com/cassianojaques/Dashboards/blob/main/dashboard%20acelerados.png?raw=true)
