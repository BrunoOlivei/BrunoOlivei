# Experiências de trabalho

## Engenheiro de Dados Sênior

**Empresa:** NAVA
**Período:** janeiro de 2025 atual

**Descrição das atribuições, atividades e projetos realizados:**

Atualmente atuo como Engenheiro de Dados Sênior na NAVA, alocado em um cliente do setor de seguros e previdência privada.

Minha principal responsabilidade é desenvolver e manter pipelines de dados, garantindo a integração e transformação de dados provenientes de diversas fontes, como bancos de dados relacionais, APIs e arquivos CSV. Utilizo tecnologias como Python, Apache Spark e Azure DataFactory, para orquestração e processamento de dados em larga escala. Além disso, sou responsável por desenvolver e otimizar processos de conciliação de dados de operações.

**Realizações**

Trabalhando em conjunto com time de negócios para, entender as necessidades e regras de negócio que envolvem o cancelamento de apólices de seguros de diversos ramos e as fórmulas de cálculo de devolução de prêmio, baseadas em características específicas da combinação de motivo de cancelamento, produto, ramo e outros dados, desenvolvi de um sistema, dentro do Databricks, baseado no paradigma de programação orientada a objetos, criando classes responsáveis por cada etapa de um processo de cálculo de devolução de prêmio e conciliação com o valor calculado pelo sistema.

Criando a classe que consulta os dados de movimentações de apólices de diversos produtos de seguros (emissão, endossos, renovações, cancelamentos) e dados de parcelas pagas e a pagar para cada família de produto. Realizando a ingestão de dados de arquivos excel e csv contendo características que determinam as regras de cálculo de devolução de prêmio para cada combinação de produto x ramo x código de moyivo de cancelamento, além de outras características como tipo de tabela com percentuais de retenção de prêmio utilizar, percentuais de retenção de prêmio baseados no período de cobertura, etc.

Consolidação de todas as informações, bases de dados consultadas e ingestionadas. Métodos que criam colunas novas, baseada em cálculos, como quantidade de prazo de dias vigentes entre outras 15 colunas que são utilizadas nas regras de cálculo. Classe para cada família de produto contendo suas regras de cálculo, baseando-se em todas as informações consolidadas nas etapas anteriores e nos requisitos de negócio. Cálculo de pró-labore e comissão baseado no produto. Viewes baseada nas necessidades de cada área de negócio.

Esse projeto identificou erros no cálculo realizado pelo sistema  gerando um prejuízo de 38 milhões de reais anuais e possíveis multas de órgãos reguladores devido a pagamentos menores realizados aos clientes. O projeto virou case de sucesso na empresa e foi utilizado para desenvolver um novo motor de cálculo de devolução de prêmio para substituir o usado no sistema.

Também criei pipelines de conciliação entre apólices que foram canceladas e se as emissões das respectivas apólices foram criadas com datas, valores, e códigos corretos, com envio de e-mail automático para time de negócios alertando sobre possíveis inconsistências. Com esse projeto o time de operações de seguros conseguiu identificar falhas sistêmicas e solicitar a correção aos times de tecnologia.

Realizei ingestões de dados, de arquivos de diversos formatos, utilizando a arquitetura Medalhão (Medallion), normalizando nomes de colunas, tipagem de dados, e através da condução de reuniões com times de cada domínio de area, criando a dicionarização das tabelas e de cada coluna.

**Competências**

* SQL
* Python
* PySpark
* Databricks
* Azure DevOps
* Azure DataFactory
* Azure Datalake Storage
* Programação Orientada a Objetos (POO)
* Unity Catalog
* Data Lakehouse
* ETL (Extração, transformação e carregamento)



## Desenvolvedor BackEnd

**Empresa:** DMX Desing
**Período:** outubro de 2024 a dezembro 2024

**Descrição das atribuições, atividades e projetos realizados:**

Participei do desenvolvimento de um software baseado na web, cujo núcleo do negócio é a intermediação de fretes entre comerciantes e transportadoras, como Correios do Brasil, IMile e Total Express. A ferramenta foi desenvolvida utilizando TypeScript com NestJS, Prisma, Jest, PostgreSQL, Azure DevOps, Azure Bus Service, Twilio e Asaas, com atuação focada no desenvolvimento back-end da aplicação.

Iniciei um projeto MVP de atendimento para salões de beleza, que utiliza LLM para conversação automatizada via WhatsApp com clientes. O sistema gerencia horários disponíveis e oferece aos clientes, por meio de mensagens no WhatsApp, agendamentos baseados na disponibilidade dos colaboradores, além de realizar upsell baseado no histórico de cada cliente.

O LLM é projetado para aprender com o comportamento dos clientes e sugerir serviços personalizados, emitir lembretes para compra de serviços e identificar preferências de dias, horários e profissionais.

Estruturei o projeto para utilização TypeScript, NestJS, Prisma, Jest, PostgreSQL, e Cohere para LLM.

**Competências**

* TypeScript
* Jest
* Testes Unitários
* NoSQL
* Programação orientada a objetos (POO)
* Desenvolvimento de back end
* Docker
* Algoritmos
* LLM
* Azure DevOps
* Azure Bus Service
* NestJS
* Prisma
* Banco de Dados
* SQL
* Interface de programação de aplicativos (API)
* Git
* Kubernets
* AWS Lambda
* AWS SQS
* AWS RDS

 

## Desenvolvedor Pleno

**Empresa:** Qyon
**Período:** março de 2022 a outubro de 2024

**Descrição das atribuições, atividades e projetos realizados:**

Sólida experiência em desenvolvimento backend com linguagem Python, desenvolvimento de APIs RESTful com frameworks Flask e FastAPI.
Forte atuação com banco de dados SQL e NoSQL, como PostgreSQL, MySQL, SQL Server, MongoDB, DynamoDB e Redis.
Ampla experiência em análise, engenharia e visualização de dados, atuando com desenvolvimento de ETLs utilizando python e frameworks como pandas, numpy, pyspark, além da análise e visualização utilizando matplotlib, seaborn e PowerBI.

**Realizações:**

Fui responsável por criar um sistema de agendamento interno, onde utilizamos diversas tecnologias atuais, para atender a demanda do setor de suporte, na implantação e migração dos dados dos clientes para nossos sistemas. Construído utilizando FastAPI, SQLAlchemy, MySQL, MongoDB, RabbitMQ, APIs do WhatsApp e API do Microsoft Teams.

Desenvolvemos um sistema onde o cliente recebe automaticamente uma mensagem, no seu número de WhatsApp, um link para agendamento com ad datas e horários disponíveis conforme a agenda do analista de implantação.

Cada analista tem controle total para liberar horários e datas de atendimento, com configurações simples e apenas 3 cliques, consegue configurar todos os horários e datas respeitando horários de almoço, pausa entre os atendimentos e bloqueios de horários, como feriados, além de outras funcionalidades como monitoramento das etapas e feedback do cliente.

Com essa ferramenta conseguimos diminuir o tempo de implantação de um cliente, de 122 dias para 22 dias nos três primeiros meses que a ferramenta entrou em operação

Fui head do projeto de dados, onde primeiro construímos um pipeline de dados coletando dados diariamente de usabilidade nos diversos módulos do nosso sistema, de cada cliente espalhados por diversas contas AWS e tipos de bancos de dados como PostgreSQL, MySQL, SQLServer, DynamoDB além de APIs.

Desenvolvemos utilizando python, asyncio, rabbitmq, pandas e numpy com deploy na AWS EKS programado para rodar 1 vez por dia todos os dias.
Utilizamos primeiramente o PostgreSQL para armazenar esses dados coletados, e disponibilizamos para stakeholders internos, através de APIs conectadas ao Power BI.

Com crescimento da empresa, migramos para ferramenta Databricks, utilizando airflow para consumo dos dados de usabilidade dos clientes. Também desenvolvemos um projeto de enriquecimento de leads coletando dados abertos da receita federal, rd station e com arquitetura medalhão alimentamos o CRM utilizado pela empresa com lotes de leads enriquecidos com base nas estratégias estabelecidas pelo comercial.

**Competências:**

* Banco de dados
* Interface de programação de aplicativos (API)
* Microsoft Excel
* Ciência de dados
* Resolução de problemas
* ETL (Extração, transformação e carregamento)
* Análise de dados
* Programação orientada a objetos (POO)
* Algoritmos
* Processamento de linguagem natural (PLN)
* Amazon DynamoDB
* Desenvolvimento de back-end
* Analítica de dados
* NLTK
* Dashboards
* Git
* MongoDB
* Python
* SQL
* Estatística
* Pandas
* Flask
* Competências interpessoais
* PostgreSQL
* Testes
* Análise de dados nos negócios

## Administrador de Clínicas e Consultórios

**Empresa:** Consultório Dra. Giovana de Moraes
**Período:** outubro de 2015 a fevereiro de 2020

**Descrição das atribuições, atividades e projetos realizados:**

Sólida experiência no gerenciamento das atividades da área Administrativa, atuando no controle das contas a pagar e receber, processos fiscais, contábeis e da área do estoque, além de apoiar no atendimento a pacientes, visando a prospecção de possíveis clientes de tratamentos estéticos.
Responsável pela coordenação de campanhas promocionais e de estudos de mercado, avaliando as ações da concorrência e seu público-alvo.
Forte atuação na definição de métodos de pesquisa, planejamento, análise de custo e controle da prestação de serviços, desenvolvendo processos focados na redução dos custos e aumento da produtividade.

Gerenciamento e desenvolvimento de pessoal administrativo e de operações, responsável pelo planejamento de estrutura de cargos e salários, aplicação de treinamentos e avaliação de desempenho, formando equipes técnicas integradas e focadas em resultados.

**Realizações:**

Com desenho de processos de atendimento, trabalho de prospecção de clientes alcançamos um crescimento de faturamento de 144% em um mês e sustentando esse faturamento com pequenas variações durante os meses subsequentes até a pandemia.

**Competências:**

* Finanças
* Microsoft Excel
* Serviço de atendimento ao cliente (SAC)
* Resolução de problemas
* Competências interpessoais

## Analista de Negócios e Risco

**Empresa:** Atlântica Importação e Exportação
**Período:** maio de 2014 a outubro de 2015

**Descrição das atribuições, atividades e projetos realizados:**

Responsável pela captação e organização das informações relacionadas as operações comerciais, tanto mercado interno quanto externo, bolsa de mercadorias e futuros (BM\&F) e estoque, elaborando relatórios gerenciais diários e mensais para tomada de decisão da gerência.
Ampla experiência na elaboração de preços de compra e venda, baseando-se nos valores de dólar e café no mercado futuro.
Experiência com o sistema SAP alimentando, controlando e conferindo os dados informados por outros setores.
Elaboração de relatórios contábeis e gerenciamento de fluxo de caixa.
Realizações:
Melhoria dos controles internos de compra e venda com objetivo de informar com mais rapidez e diminuir assim o risco de perda financeira. Metodologia de marcação a mercado das posições de compra, venda (mercado interno e externo), bolsa, dólar junto a auditoria e diretoria da empresa.
Responsável pelo aprimoramento dos controles internos, implantação junto ao departamento de t.i. dos controles no sistema (sap) melhorando a qualidade das informações reduzindo retrabalho e tempo para tomada de decisões, participei da implantação do método de contabilização da marcação a mercado.

\*\*Competências: \*\*
•	Finanças
•	Microsoft Excel
•	Resolução de problemas
•	Análise de dados
•	Competências interpessoais
 
Empresa: Cooparaiso
Cargo: Analista de Negócios e Risco
Período: novembro de 2011 a maio de 2014
Descrição das atribuições, atividades e projetos realizados:
Controle e conferência das operações realizadas em bolsa de mercadorias e futuros (café) bm\&f e ice (nova york) das compras e vendas no mercado físico interno e externo, registro das operações, solicitação de remessa e resgate de valores, cotação de taxa cambial junto as agências bancárias, elaboração de relatórios de estoque, compras e vendas, fluxo de embarque e recebimento, fluxo de caixa e fechamentos contábeis.
Coordenação dos embarques de vendas de café, junto aos departamentos que fazem parte do processo visando identificar possíveis falhas para não atrasar o faturamento e embarque e assim o recebimento, prezando a saúde do fluxo de caixa da empresa.
Implantação de diversos controles e relatórios no sistema desenvolvido pela própria empresa junto ao departamento de T.I.
Responsável pela criação de controles internos e a implantação junto ao t.i. e adaptação as normas internacionais de contabilidade.
Realizações:
Criamos uma ferramenta que possibilitou ver o posicionamento da empresa perante um mercado de café, cotado em bolsa e com grande volatilidade, assim possibilitando a visão dos gestores da área e diminuindo o risco de perda financeira.
Competências:
•	Finanças
•	Microsoft Excel
•	Resolução de problemas
•	Análise de dados
•	Competências interpessoais
 
Empresa: Cooparaiso
Cargo: Analista de Crédito e Cobrança
Período: agosto de 2008 a novembro de 2011
Descrição das atribuições, atividades e projetos realizados:
Captação de recurso junto a bancos, análise de crédito e repasse dos recursos captados aos cooperados, elaboração e controle de contratos jurídicos de financiamento, atualização de cadastro. Fluxo de caixa e gerenciamento do contas a pagar do setor.
Responsável pela captação, controle e repasse de 14 milhões de reais junto as instituições financeiras aos cooperados e implantação do sistema score de análise de crédito.
Atendimento balcão e telefone, liberação de limite de crédito no curto prazo, controle da carteira a receber vencida e cobrança por telefone e correspondência, lançamento de títulos sistema.
Realizações:
Responsável pela cobrança da carteira de títulos vencidos acima de 45 dias. Redução de 55% da carteira.
Competências:
•	Finanças
•	Microsoft Excel
•	Serviço de atendimento ao cliente (SAC)
•	Competências interpessoais

