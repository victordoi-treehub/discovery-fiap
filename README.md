# ContabiAI - Desafio Contabilizei – FIAP

A Contabilizei é uma empresa que opera em um ecossistema complexo, integrado por múltiplos sistemas, APIs, ferramentas como Power BI, CRM, plataformas de chamados e, claro, um vasto Data Lake. 

Embora esses componentes sejam fundamentais para a operação e gestão da empresa, o acesso a informações de forma rápida e precisa ainda apresenta desafios significativos, especialmente para usuários internos que nem sempre possuem conhecimentos técnicos avançados. 

## O Problema

Atualmente, a busca por informações relevantes exige que os colaboradores naveguem por diferentes sistemas e interfaces, façam consultas manuais ou dependam de equipes técnicas para acessar dados específicos. Além disso, há casos em que informações críticas não estão armazenadas diretamente no Data Lake, mas estão disponíveis em tempo real através de APIs ou outros sistemas de consulta. Essa fragmentação dificulta a autonomia dos usuários, sobrecarrega os times técnicos e pode gerar atrasos na tomada de decisão.

- **Complexidade**: A necessidade de navegar por múltiplos sistemas e ferramentas para obter informações específicas.
- **Dependência técnica**: Usuários internos dependem frequentemente de suporte técnico para realizar consultas e gerar relatórios simples.
- **Fragmentação de dados**: Informações relevantes estão dispersas entre o data lake e diversos sistemas conectados por APIs.
- **Perda de tempo**: Acesso manual e não integrado às informações gera ineficiência operacional.

## A Solução

Este projeto propõe o desenvolvimento de uma LLM (Large Language Model) que se conecta ao ecossistema da Contabilizei utilizando o Model Context Protocol (MCP).
O MCP Server será o núcleo da solução, permitindo que a LLM se integre diretamente a sistemas como DataLake, Power BI, CRM, plataformas de chamados e APIs da empresa. Com isso, a LLM será capaz de:

- Criar um Datalake e fazer a ingestão de dados dos sistemas da Contabilizei.
- Consultar dados disponíveis em tempo real, mesmo que não estejam no data lake.
- Responder com precisão às perguntas feitas em linguagem natural, eliminando a necessidade de consultas técnicas complexas.
- Fornecer informações acionáveis e relevantes, centralizando o acesso aos dados dispersos.
- Garantir que os usuários internos tenham autonomia para buscar informações com rapidez e segurança.

Essa abordagem revolucionará a forma como os colaboradores acessam e utilizam os dados disponíveis, promovendo eficiência, autonomia e maior assertividade na tomada de decisões. 

A LLM com MCP Server será o elo que conecta todos os sistemas da Contabilizei, transformando dados dispersos em respostas unificadas e poderosas.
