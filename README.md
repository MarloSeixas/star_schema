# star_schema
Modelagem Dimensional – Star Schema
Objetivo
Desenvolver um diagrama dimensional no modelo Star Schema, baseado em um diagrama relacional previamente disponibilizado.

Foco
O foco do modelo é a análise de dados dos professores. Para isso, foi criado uma tabela fato que consolida informações sobre os professores, os cursos ministrados e os departamentos aos quais estão vinculados.

Desenvolvimento
Foi criado a tabela fato contendo os principais dados para análise do contexto, além das tabelas dimensão, que armazenam detalhes relevantes sobre professores, cursos, departamentos e disciplinas.

Para garantir um modelo mais completo, adicionei também uma tabela dimensão de datas, possibilitando análises temporais sobre a oferta de disciplinas e cursos. Defini a granularidade de forma estratégica para abranger diferentes níveis de detalhamento.

Resultado
O modelo resultante permite explorar informações sobre os professores de maneira eficiente, facilitando a extração de insights sobre sua atuação na universidade.
