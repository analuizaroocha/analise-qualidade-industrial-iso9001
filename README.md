# analise-qualidade-industrial-iso9001
Dashboard estratégico em Power BI para monitoramento de conformidade ISO 9001 e análise estatística de Pareto industrial.


📊 Case: Dashboard de Gestão de Qualidade Industrial (ISO 9001:2015)
📌 Visão Geral do Projeto
Este projeto apresenta o desenvolvimento de um ecossistema de Business Intelligence focado no departamento de Qualidade de uma indústria. O objetivo central foi transformar o volume de reclamações de clientes em indicadores estratégicos (KPIs) para apoiar a manutenção da certificação ISO 9001:2015.

🛠️ Stack Tecnológica
Ferramenta de BI: Microsoft Power BI

Tratamento de Dados (ETL): Power Query (Linguagem M)

Cálculos Estatísticos: Linguagem DAX

Modelagem: Star Schema (Tabelas Fato e Dimensões)

🏗️ Etapas do Desenvolvimento
1. ETL e Tratamento de Dados
Limpeza e padronização da base histórica de reclamações.

Tratamento de valores nulos e correção de tipagem de dados.

Criação de uma Tabela Calendário dinâmica para permitir análises temporais precisas (YoY, MoM).

2. Modelagem de Dados
Implementação de esquema estrela (Star Schema), garantindo performance e escalabilidade.

Criação de tabelas dimensões para Clientes, Origens de Reclamação e Calendário, conectadas à tabela Fato de Ocorrências.

3. Análise com Foco em Negócio
Gráfico de Pareto (Análise 80/20): Implementação via DAX para identificar os 20% de causas/clientes que geravam 80% dos problemas de qualidade.

Cálculo de Eficácia: Monitoramento da redução de reclamações pós-implementação de ações corretivas.

📈 Resultados Obtidos
Redução Drástica de Reclamações: O dashboard demonstra visualmente a queda de ocorrências, atingindo apenas 3 registros no ano de 2024.

Agilidade na Decisão: Redução do tempo de resposta do departamento de qualidade ao identificar rapidamente a origem (Canais) das reclamações mais frequentes.

Conformidade ISO: Automação dos relatórios necessários para as auditorias de manutenção da ISO 9001.

📸 Visualização do Dashboard

<img width="1067" height="543" alt="image" src="https://github.com/user-attachments/assets/c77f6569-f028-426d-9dcd-98644a1d3bb4" />
<img width="891" height="491" alt="image" src="https://github.com/user-attachments/assets/9eef23f5-645b-45a6-bccc-1c5e7e4d7370" />



⚠️ Nota de Confidencialidade
Para respeitar o sigilo industrial, os dados utilizados foram anonimizados. Nomes de clientes e informações sensíveis foram alterados, preservando apenas a estrutura lógica e o design funcional do projeto.
