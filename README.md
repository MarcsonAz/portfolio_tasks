# portfolio_tasks

📊 Portfólio de Projetos – Estatístico & Analista de Dados

Projetos desenvolvidos com base na minha formação em Estatística e Estatísticas Públicas, e na minha experiência de 6 anos trabalhando com dados do setor público brasileiro, pesquisas amostrais, registros administrativos, R, SQL, produção de análises descritivas e inferenciais, relatórios técnicos e coordenação de equipes de dados.

Cada projeto abaixo é pequeno, modular e pensado para demonstrar habilidades essenciais de um Analista de Dados Pleno.

📁 Estrutura dos Projetos

Cada projeto terá:

Objetivo geral

Habilidades demonstradas

Checklist de etapas

Arquivos esperados

Possíveis extensões (nível pleno)

🧩 Lista de Projetos
1. 📈 Análise Descritiva de Dados Públicos (IBGE, PNAD Contínua ou SIDRA)

Objetivo: realizar uma análise descritiva clara, replicável e bem documentada usando dados públicos brasileiros.

Habilidades demonstradas:
✔ Manipulação de dados públicos
✔ Reprodutibilidade (R ou Python)
✔ Storytelling com dados
✔ Produção de relatório técnico

Checklist:

 Selecionar uma tabela pública (ex: taxa de desocupação por UF)

 Importar dados via API (SIDRA, PNADc IBGE, etc.)

 Realizar limpeza e padronização

 Criar métricas-chave (médias, variações, rankings)

 Produzir visualizações (gráficos de linha, barras, mapas)

 Elaborar insights e interpretações

 Produzir relatório técnico (RMarkdown / Quarto)

Arquivos esperados:

/src/ scripts R ou Python

/data/ dados brutos e tratados

analysis.Rmd ou analysis.qmd

Extensões:

Reproduzir análise do IBGE com outra fonte (RAIS, CAGED, DATASUS).

Criar dashboard simples (Shiny ou Streamlit).

2. 🗃 Projeto SQL – Do Bruto ao Tratado com Casos Reais

Objetivo: demonstrar proficiência prática em SQL simulando uma base administrativa pública.

Habilidades demonstradas:
✔ Consultas avançadas
✔ CTEs e Window Functions
✔ Criação de dicionário e documentação
✔ Pensamento analítico para bases administrativas

Checklist:

 Criar uma base fictícia (inspiração RAIS/CAGED/Servidores)

 Criar o esquema + dicionário de variáveis

 Carregar dados (SQLite, PostgreSQL ou DuckDB local)

 Criar consultas típicas do setor público:

 Evolução temporal

 Indicadores agregados

 Segmentações por UF, sexo, escolaridade

 Ranking de municípios (Window Functions)

 Criar relatório de consultas + interpretação

Arquivos esperados:

/sql/queries.sql

/db/schema.sql

/docs/dicionario.pdf

Extensões:

Criar uma API simples usando Flask/FastAPI para servir consultas.

Criar visualizações automáticas a partir das queries.

3. 📉 Projeto de Inferência Estatística – Fatores Associados a um Fenômeno Social

Objetivo: modelar um fenômeno relevante (ex: desocupação, escolaridade, rendimentos) usando métodos estatísticos típicos da área pública.

Habilidades demonstradas:
✔ Regressão linear / logística
✔ Seleção de variáveis
✔ Interpretação estatística clara
✔ Construção de dataset integrado

Checklist:

 Selecionar um tema (ex: renda média por características individuais)

 Obter microdados (PNADc amostra reduzida)

 Criar tratamento + engenharia de variáveis

 Ajustar modelos (lm, glm ou métodos robustos)

 Avaliar pressupostos

 Explicar resultados em linguagem acessível

 Produzir relatório técnico + gráficos

Arquivos esperados:

/src/modelagem.R

/data/tratado.csv

relatorio_inferencia.qmd

Extensões:

Comparar diferentes modelos.

Criar função própria de análise automática (pacote R mínimo).

4. 📊 Visualização Avançada – Painel sobre Servidores Públicos (dados fictícios)

Objetivo: reproduzir sua experiência recente produzindo visualizações avançadas para gestão pública.

Habilidades demonstradas:
✔ Storytelling visual
✔ Visualizações multi-layer
✔ Design de dashboards
✔ Comunicação de resultados

Checklist:

 Criar dataset fictício (com variáveis realistas: vínculos, cargos, salários, escolaridade)

 Criar gráficos avançados:

 Heatmaps

 Ridgeline / densidades

 Facets comparativos

 Séries temporais por grupo

 Montar mini-dashboard (Shiny/Streamlit/Quarto)

 Criar narrativa explicando achados

Arquivos esperados:

/dashboard/

/figs/

Extensões:

Adicionar filtros dinâmicos

Simular indicadores de gestão

5. 🧪 Reprodução de Pesquisa (Replication Study)

Objetivo: mostrar domínio em pesquisas amostrais e literatura metodológica.

Habilidades demonstradas:
✔ Capacidade de reproduzir resultados técnicos
✔ Compreensão de desenho amostral
✔ Revisão metodológica rigorosa

Checklist:

 Selecionar artigo curto com dados públicos

 Baixar e preparar dados

 Reproduzir todas as tabelas e gráficos

 Comparar resultados com os do artigo

 Explicar diferenças (se houver)

 Documentar limitações

Arquivos esperados:

replication_report.qmd

/src/replicate.R

Extensões:

Reproduzir estudo da ENCE/IBGE, IPEA, DIEESE etc.

6. 🛠 Mini Pipeline de Dados – ETL + Documentação

Objetivo: demonstrar experiência recente com gestão de equipe e organização de dados.

Habilidades demonstradas:
✔ ETL
✔ Padronização de tabelas
✔ Versionamento de dados
✔ Boas práticas de documentação

Checklist:

 Criar uma pasta com dados brutos

 Construir pipeline automático (R ou Python)

 Validar consistência (missing, ranges, tipos)

 Gerar tabela tratada + logs de execução

 Criar documentação da pipeline (README + dicionário)

Arquivos esperados:

/etl/01_extract.R

/etl/02_transform.R

/etl/03_load.R

/docs/data_dictionary.md

Extensões:

Automatizar pipeline com GitHub Actions

7. 🤖 Mini RAG para Consultas Textuais de Relatórios Públicos

(Opcional, mas demonstra habilidades modernas e diferenciais.)

Objetivo: criar um sistema simples que permita consultar trechos de relatórios públicos.

Habilidades demonstradas:
✔ IA aplicada a dados governamentais
✔ Processamento de linguagem natural
✔ Construção de protótipo

Checklist:

 Selecionar 3 relatórios públicos (ex: IPEA, IBGE)

 Criar vetorstore local

 Criar API simples de consulta

 Criar interface mínima (CLI ou Streamlit)

Extensões:

Integrar SQL + RAG

Criar avaliações de qualidade de resposta

🧭 Próximos Passos

Começar pelos projetos descritivos e SQL (mais rápidos).

Em seguida, avançar para o projeto de inferência.

Depois, criar o dashboard e o pipeline ETL.

Finalizar com o projeto RAG, se quiser diferencial de mercado.

🏁 Objetivo Final

Ter um portfólio sólido que mostre:

Capacidade analítica

Proficiência técnica (R, SQL, dashboards)

Comunicação de resultados

Entendimento profundo de dados públicos

Maturidade de profissional pleno
