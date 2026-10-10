# Base de pesquisa Parkinson

## Método e limites

Esta base reúne registros bibliográficos públicos e o histórico das pesquisas Rybolt. Metadados de publicação não validam conclusões científicas. Sínteses são candidatas até revisão humana e conferência das evidências.

1. Definir pergunta, escopo temporal, critérios de inclusão/exclusão e estratégia de busca.
2. Registrar cada consulta, data, fonte, resultados e buscas vazias; não confundir ausência na busca com ausência de literatura.
3. Deduplicar fontes por PMID; conferir DOI quando disponível. Não completar campos bibliográficos ausentes por plausibilidade.
4. Fazer triagem por título/resumo; registrar motivo de inclusão/exclusão. Os registros iniciais ainda não foram triados.
5. Conferir texto integral e extrair desenho, população, mecanismos, estágios, desfechos, limitações e evidência que sustenta cada afirmação. Resumo truncado não equivale a artigo lido.
6. Separar fisiopatologia, progressão e escalas clínicas. Não presumir que uma única escala descreve toda a doença.
7. Revisão crítica e validação OWNER antes de promover uma síntese. Preservar divergências e referências rastreáveis.
8. Montar referências ABNT usando metadados conferidos, com links e data de acesso; revisão de formatação continua necessária.

Fontes bibliográficas: PubMed/NCBI, https://pubmed.ncbi.nlm.nih.gov/. Termos e limites: https://www.ncbi.nlm.nih.gov/About/disclaimer.html.

## Organização

- `sources/PMID.json`: metadados públicos deduplicados, ainda não triados.
- `runs/JOB.json`: protocolo executado, consultas e proveniência do trabalho.
- `candidates/JOB.md`: resultado candidato e lacunas, sem validação automática.

A base é cumulativa pelo histórico Git. Nenhum dado clínico privado, credencial, memória pessoal ou raciocínio interno é exportado. Atualizações ocorrem em branch/PR rascunho; sem merge, deploy ou acesso AWS pelo Rybolt.
