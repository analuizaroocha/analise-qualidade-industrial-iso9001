# analise-qualidade-industrial-iso9001
Dashboard estratégico em Power BI para monitoramento de conformidade ISO 9001 e análise estatística de Pareto industrial.


📊 Case: Dashboard de Gestão de Qualidade Industrial (ISO 9001:2015)

📌 Visão Geral do Projeto
Este projeto apresenta o desenvolvimento de uma solução de Business Intelligence para a CSI Filtros e Não Tecidos, focada no monitoramento estratégico de reclamações de clientes. O objetivo central foi transformar dados brutos em insights acionáveis para sustentar a melhoria contínua e a conformidade com a norma ISO 9001:2015.

🛠️ Stack Tecnológica & Metodologia
Ferramenta de BI: Microsoft Power BI

Processamento de Dados (ETL): Power Query para limpeza, padronização e tratamento de inconsistências.

Modelagem de Dados: Implementação de arquitetura Star Schema (Esquema Estrela) com tabelas fato e dimensões, garantindo performance e escalabilidade do modelo.

Linguagem DAX: Criação de medidas para análise estatística, incluindo cálculos de acumulados e inteligência de tempo.

📈 Análises Estratégicas Realizadas
1. Diagnóstico de Distribuição (Origem)
Mapeamento da concentração de reclamações por categoria.

Insight: Identificou-se que 50% das ocorrências são atribuídas diretamente a clientes, enquanto 36,11% estão relacionadas a fornecedores/matéria-prima.

2. Análise de Priorização (Princípio de Pareto)
Aplicação da regra 80/20 para isolar os "poucos vitais". Esta análise permitiu identificar os clientes e causas de maior impacto, direcionando os esforços e recursos para resolver a maior concentração de problemas com máxima eficiência.

3. Monitoramento de Tendência (Análise Temporal)
Acompanhamento do volume de ocorrências ao longo dos anos para validar a eficácia das ações corretivas.

Resultado: O painel comprova uma evolução positiva, atingindo o marco de apenas 3 registros no ano de 2024, evidenciando o sucesso das estratégias de qualidade.

🚀 Diferenciais Técnicos do Modelo
Tabela Calendário: Criação de dimensão temporal dedicada para filtros dinâmicos e comparativos anuais (YoY).

Deployment & Escalabilidade: Arquitetura preparada para receber novos registros automaticamente e escalar para novos KPIs, como custo de reclamação e Lead Time de resolução.

UX Design: Interface desenvolvida com foco na experiência do gestor, permitindo navegação fluida entre filtros de origem e períodos.
📸 Visualização do Dashboard



<img width="1067" height="543" alt="image" src="https://github.com/user-attachments/assets/c77f6569-f028-426d-9dcd-98644a1d3bb4" />







<img width="976" height="543" alt="image" src="https://github.com/user-attachments/assets/11976fdd-fad0-4244-9cf5-9c95c49de979" />









⚠️ Nota de Confidencialidade
Para respeitar o sigilo industrial, os dados utilizados foram anonimizados. Nomes de clientes e informações sensíveis foram alterados, preservando apenas a estrutura lógica e o design funcional do projeto.
