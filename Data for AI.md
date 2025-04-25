# Data for AI 🚀  
**Exam Weight: 36%**

## Data Analytics Fundamentals


## Types of Data Analysis

1. **Descriptive Analysis**  
   Resume o que aconteceu com base em dados históricos. É o ponto de partida que fornece insights básicos sobre tendências e padrões.

2. **Diagnostic Analysis**  
   Explica por que algo aconteceu, geralmente comparando dados e descobrindo correlações e causas.

3. **Predictive Analysis**  
   Usa dados passados para prever eventos futuros. Por exemplo, pode ser usado para identificar e bloquear requisições web maliciosas com base em padrões de logs de segurança.

4. **Prescriptive Analysis**  
   Sugere ações a serem tomadas com base nas previsões, otimizando decisões e estratégias.

---

## Data Analytics Verticals

Data analytics é utilizado em diferentes setores para gerar valor por meio de decisões orientadas por dados. Alguns exemplos incluem:

- Gaming
- Social Media
- Ecommerce
- Online stores
- Clickstreaming
- Recommendation engines
- IoT (Internet of Things)
- Log processing

---

## Aplicação Prática

Coletas de dados anônimos, como as realizadas em jogos para melhorar a experiência do usuário, são formas comuns de aplicar análises descritivas e preditivas em tempo real. Esses dados ajudam a escalar a coleta de informações e identificar tendências para tomada de decisão estratégica.

---

## Benefícios do Data Analytics

- **Escala de coleta de dados**  
  Acelera a visualização de tendências através de um grande volume de pontos de dados.

- **Tomada de decisões orientadas por dados**  
  Fornece suporte para decisões mais assertivas em negócios e tecnologia, otimizando processos e resultados.

---

## Ferramentas AWS para Data Analytics

Plataformas da Amazon Web Services usadas com frequência em pipelines de análise de dados:

- **Amazon EMR**: Processamento de grandes volumes de dados com frameworks como Hadoop e Spark.
- **Amazon S3**: Armazenamento escalável de dados.
- **Amazon RDS**: Banco de dados relacional gerenciado.
- **Amazon Athena**: Consulta interativa de dados no S3 usando SQL.

---

## Conclusão

Data analytics fundamenta a tomada de decisões em diversos contextos de mercado, usando diferentes técnicas analíticas e ferramentas específicas. Sua aplicação abrange desde análise de comportamento de usuários em plataformas digitais até estratégias de segurança e otimização operacional em grande escala.

# Data Quality

## Introdução
Na Gelato, uma empresa de tecnologia de mídia, a qualidade dos dados tornou-se um fator crítico para a expansão dos negócios. A diretora de vendas solicitou uma visão de 360° dos clientes. Contudo, os relatórios do Salesforce revelaram sérios problemas de qualidade de dados, prejudicando as estratégias de marketing, vendas e suporte.

## Problemas Identificados

### Registros Ausentes
- Apenas 200 contas listadas para a região oeste, embora haja mais de 500 clientes na Califórnia.

### Registros Duplicados
- Clientes com múltiplas localizações aparecem como registros distintos.

### Falta de Padrões de Dados
- Estados registrados de forma inconsistente: "CA", "Calif", "Cali", e "Surfin', EUA".

### Registros Incompletos
- Contas comerciais sem setor, receita e número de funcionários.
- Contas de consumidores sem telefone e e-mail.

### Dados Obsoletos
- Mais da metade dos registros não foram atualizados nos últimos 6 meses.

## Impactos de Dados Ruins
- Queda de até 20% na produtividade
- Perda de 12% da receita anual
- 40% das iniciativas empresariais falham
- Prejuízos: receita, insights, eficiência, atendimento ao cliente e reputação

## Importância de Dados de Qualidade
- Permite prospecção eficiente
- Melhora a pontuação e o encaminhamento de leads
- Garante insights de conta
- Aumenta eficiência e confiança dos clientes
- Facilita o alinhamento de territórios e comunicação eficaz

## Dados na Inteligência Artificial
- Dados ruins resultam em IA tendenciosa e vulnerável
- Dados de qualidade aumentam a acurácia e confiabilidade dos modelos
- Garantem conformidade regulatória e maximizam o ROI

## Diagnóstico de Uso de Dados

### Etapas Realizadas
1. Entendimento dos objetivos dos departamentos
2. Identificação de dados necessários
3. Avaliação dos sistemas usados

### Descobertas
- Departamentos usam fontes diferentes (Salesforce, planilhas, etc.)
- Ausência de padrões e processos uniformes

## Tabela: Objetivos de Negócio vs. Dados Necessários
| Objetivo | Departamentos | Dados Necessários |
|---------|---------------|--------------------|
| Anunciar novos serviços | Marketing | Nome, Empresa, E-mail, Endereço, Telefone, Setor, Receita, Funcionários |
| Pontuação de leads | Vendas | Nome, Empresa, E-mail, Telefone, Receita, Status, Fonte |
| Rastrear leads | Vendas | Nome, E-mail, Receita, Status, Etapas |
| Alinhar territórios | Vendas, Suporte | Nome, Empresa, Setor, Receita |
| Solicitações de serviço | Suporte, Jurídico | Empresa, Prioridade, SLA, Tipo |
| Vendas cruzadas | Vendas | Empresa, Receita, Setor |
| Cobranças | Jurídico, Finanças | Empresa, Produtos |

## Avaliação de Qualidade de Dados

| Dimensão | Descrição | Avaliação |
|----------|------------|----------|
| Idade | Quando foi a última atualização? | Relatório de data de modificação |
| Completude | Campos obrigatórios estão preenchidos? | Verificação de campos em branco |
| Precisão | Os dados são corretos? | Comparar com fonte confiável (AppExchange) |
| Consistência | Formato e linguagem padronizados? | Relatório de variação de valores |
| Duplicidade | Existem registros repetidos? | Ferramentas de deduplicacão do Salesforce |
| Uso | Os dados estão sendo utilizados? | Análise de relatórios e dashboards |

## Ferramentas Recomendadas
- **AppExchange - Data Quality Analysis Dashboards**: fornece relatórios e painéis para medir a qualidade dos dados

## Plano de Gerenciamento de Dados

| Padrão | Descrição | Exemplo |
|--------|------------|---------|
| Nomeação | Convenções para nome de empresas | Não abreviar nomes |
| Formatação | Datas e moedas | dd/mm/aaaa, moedas em R$ |
| Fluxo de trabalho | Criação, revisão, atualização | Direcionar pedidos da Califórnia para reps locais |
| Qualidade | Métricas de idade, uso, precisão | Leads ativos atualizados mensalmente |
| Responsáveis | Quem é dono de cada dado | Reps regionais |
| Segurança | Permissões e privacidade | Acesso restrito por região |
| Monitoramento | Frequência e responsáveis por revisão | Revisar dados incompletos mensalmente |

## Implementação no Salesforce

### Funcionalidades Chave
- **Campos obrigatórios**: garantir preenchimento de dados críticos
- **Regras de validação**: formatar telefone, e-mail, etc.
- **Flows**: automatizar atribuição de leads e solicitações
- **Layouts de página**: simplificar e personalizar campos
- **Painéis**: facilitar visualização de dados relevantes
- **Ferramentas de enriquecimento**: atualizar dados automaticamente
- **Gerenciamento de Duplicatas**: evitar entradas repetidas
- **Tipos de campo**: usar listas padronizadas para estados, moeda, datas

# Data Literacy Modules - Salesforce Trailhead

## Data Literacy Basics

### O que é Alfabetização em Dados?
É a capacidade de explorar, entender e comunicar usando dados. Alfabetização em dados é essencial para resolver problemas, formular boas perguntas e tomar decisões baseadas em evidências.

### Características de Pessoas que Trabalham Bem com Dados
Adaptadas de Stephen Few:
- Interesse e curiosidade
- Criatividade e exploração
- Mente aberta e flexibilidade
- Capacidade de priorizar perguntas úteis
- Honestidade e ceticismo
- Pensamento analítico e sintético
- Comunicação clara

### Exemplos Inspiradores
- **Florence Nightingale:** usou visualizações para reduzir mortes em hospitais.
- **John Snow:** usou mapas e dados para identificar a bomba de água contaminada durante uma epidemia de cólera.

---

## Well-Structured Data

### Características de Dados Úteis
- **Alto volume:** dados relevantes e em grande quantidade.
- **Histórico:** permite análise de tendências.
- **Consistência:** ajustados para mudanças como inflação.
- **Multivariados:** qualitativos e quantitativos.
- **Atômicos:** detalhados até o nível mais baixo.
- **Limpos:** sem erros ou lacunas.
- **Claros:** linguagem compreensível, não codificada.
- **Estrutura Dimensional:** dimensões (qualitativas) e medidas (quantitativas).
- **Segmentados:** agrupados por características (ex: gênero).
- **Com pedigree conhecido:** origem e alterações registradas.

### Organização de Dados
- Cada variável deve estar em uma coluna.
- Cada observação em uma linha.
- Cabeçalhos claros para colunas.

### Reestruturação de Dados
Ferramentas: Tableau Prep, R, Python, ETL.

#### Pivot
Transforma colunas em linhas para permitir análises melhores.

#### Split (Divisão)
Divide uma única coluna com múltiplas informações (ex: "Companhia: Código") em colunas separadas.

---

## Variables and Field Types

### Variáveis
- **Qualitativas:** não mensuráveis numericamente (ex: nome, cor).
  - **Nominal:** sem ordem (ex: frutas).
  - **Ordinal:** com ordem (ex: níveis de satisfação).
- **Quantitativas:** mensuráveis (ex: altura, idade).
  - **Discretas:** contáveis (ex: número de filhos).
  - **Contínuas:** infinitamente divisíveis (ex: tempo, massa).

---

## Aggregation and Granularity

### O que é Agregação?
É o processo de resumir dados quantitativos:
- **Sum:** soma total
- **Average:** média aritmética
- **Median:** valor central
- **Min/Max:** menor e maior valor
- **Count:** total de registros
- **Count Distinct:** total de valores únicos

### O que é Granularidade?
É o nível de detalhe dos dados. Quanto mais desagregado, maior a granularidade.

#### Exemplo:
- **Alta agregação / baixa granularidade:** soma total de idades.
- **Baixa agregação / alta granularidade:** idade de cada participante exibida individualmente.

#### Visualizações:
- **Bar chart (agregado)**
- **Jitter plot (desagregado)**

---

## Salesforce Data Cloud: Quick Look

### Visão Geral
O Data Cloud é a plataforma de dados da Salesforce, integrada com inteligência artificial e automação, promovendo uma visão unificada do cliente em tempo real.

### Vantagens
- Unificação de dados estruturados e não estruturados.
- Baseada em metadados compartilhados entre Salesforce apps.
- Suporte nativo para integração com Snowflake, BigQuery, Redshift e Databricks.
- Sem necessidade de copiar os dados (“zero copy integration”).

### Aplicações por Área

| Equipe        | Experiência com Data Cloud |
|---------------|----------------------------|
| **Vendas**    | Ofertas personalizadas em tempo real. |
| **Serviço**   | Alertas proativos com base em dados. |
| **Marketing** | Mensagens adaptadas em tempo real. |
| **Comércio**  | Experiências adaptadas (ex: carrinhos abandonados). |
| **TI**        | Aplicações com dados em tempo real (ex: fraude). |
| **MuleSoft**  | Acesso em tempo real a sistemas legados. |
| **Tableau**   | Monitoramento em tempo real de KPIs. |
| **Slack**     | Visualizações de dados em tempo real por canal. |
| **Saúde**     | Conexão entre dados clínicos e não clínicos. |
| **Finanças**  | Conselhos personalizados no momento certo. |
| **AppExchange** | Extensão com apps parceiros para publicidade, enriquecimento de perfis, etc. |

## Build Your Data Literacy
## Is Your Data AI-Ready?
## Data Management Best Practice Guide
## Determine Data Requirements
## Data Quality Dimensions Cheat Sheet
