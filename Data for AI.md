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

# Distribuições de Dados e Inferência Estatística

## Introdução: Organização de Dados

Se você concluiu o módulo **Dados Bem Estruturados**, aprendeu que:
- Cada **variável (campo)** fica em uma **coluna**.
- Cada **observação (valor)** fica em uma **linha**.
- Variáveis podem ser:
  - **Discretas**: valores separados (ex: número de filhos).
  - **Contínuas**: valores contínuos (ex: altura, peso).

Distribuições mostram **todos os valores possíveis** e a **frequência** de ocorrência.

---

## Distribuição de Variáveis Discretas

**Exemplo: Cores de doces (variável nominal, qualitativa e discreta)**

| Cor    | Frequência |
|--------|------------|
| Marrom | 17         |
| Vermelho | 18       |
| Amarelo | 7         |
| Verde  | 7          |
| Azul   | 2          |
| Laranja | 4         |

Gráficos:
- **Distribuição de Frequência** (contagem total)
- **Distribuição de Proporção** (percentual sobre o total)

---

## Distribuição de Variáveis Contínuas

**Exemplo: Tempos de resposta (em milissegundos)**

Distribuição agrupada por intervalos:

| Intervalo (ms) | Frequência |
|----------------|------------|
| 500–600        | 3          |
| 600–700        | 6          |
| 700–800        | 5          |
| 800–900        | 5          |
| 900–1000       | 0          |
| 1000–1100      | 1          |

Representação gráfica: **Histograma**.

---

## Formatos de Distribuições

- **Simétrica**: Média = Mediana.
- **Assimétrica Positiva**: Média > Mediana (cauda para a direita).
- **Assimétrica Negativa**: Média < Mediana (cauda para a esquerda).

Exemplo usando alturas de pessoas.

---

## Histograma

- Eixo x: Faixas de valores (bins).
- Eixo y: Contagem (frequência) de dados naquele intervalo.

---

## Boxplot (Gráfico de Caixa)

Visualização compacta para distribuições:
- Caixa: 25º a 75º percentil.
- Linha interna: Mediana (50º percentil).
- Bigodes: valores extremos dentro de 1.5 x IQR.
- Pontos fora: outliers.

**Exemplo de Construção:**
1. Ordenar dados.
2. Calcular 25%, 50%, 75% percentis.
3. Definir IQR (Intervalo Interquartil).
4. Definir bigodes.
5. Indicar outliers.

**Comparação:**
- **Boxplot** ocupa menos espaço que histograma para comparar múltiplas distribuições.

---

## Variância e Desvio Padrão

- **Variância**: medida da dispersão dos dados em relação à média.
- **Desvio Padrão**: raiz quadrada da variância.

**Exemplo:**
Grupo A e Grupo B, ambos com média 7, mas com dispersão diferente.

**Formulário Variância:**
- População: soma dos quadrados / número de dados (n).
- Amostra: soma dos quadrados / (n - 1).

---

## Distribuições Contínuas e Curvas de Densidade

- Representam **todos os valores possíveis** de uma variável contínua.
- A área total sob a curva = 1 (100%).

---

## Distribuição Normal

Características:
- Forma de sino (simétrica).
- Média = Mediana.
- 68% dos dados entre -1 e +1 desvios padrão.
- 95% dos dados entre -2 e +2 desvios padrão.

Desvios padrão controlam "altura" e "largura" da curva.

---

## Intervalos de Confiança

- **Inferência Estatística**: concluir sobre uma população baseado em amostras.
- Intervalos de confiança indicam uma faixa na qual a média verdadeira provavelmente está.

**Exemplo:**
Peso médio de crianças de 10 anos entre 72,85 e 107,15 libras com 95% de confiança.

---

## Teste de Hipóteses

**Hipóteses:**
- **Hipótese Nula (H0)**: não há efeito.
- **Hipótese Alternativa (H1)**: há efeito.

**Valor-p:**
- Probabilidade de observar os resultados se H0 fosse verdadeira.
- Valor-p baixo → evidência contra H0.

**Nota:**
- Valor-p não "prova" nada sozinho.
- Interpretação moderna sugere cautela no uso de valor-p isoladamente.

---

## Questionário (Resumo)

**1. Verdadeiro ou Falso:** Valores de p podem ser manipulados?  
✅ Verdadeiro

**2. Quais são tipos de hipóteses?**  
✅ A e B (Hipóteses nulas e alternativas)

---  

# Journey Toward Data Fluency

## Introdução: Alfabetização em Dados

Data literacy é a base para o uso e comunicação com dados de forma eficiente.

O módulo **Data Literacy Basics** descreve variáveis quantitativas como características numericamente mensuráveis, por exemplo:
- Horas assistindo TV por dia
- Velocidade em milhas por hora
- Total de chuvas anuais
- Vendas em dólares
- Valor gasto em marketing

---

## O que é Correlação?

**Correlação** é uma técnica que mostra **se** e **quão fortemente** duas variáveis quantitativas estão relacionadas.

Exemplo:
- Número de calorias consumidas por dia e peso corporal.
- Vendas e gasto em marketing.

> **Nota**: Este módulo discute apenas **correlação de Pearson**.

### Correlação vs Causalidade
- **Correlação ≠ Causalidade**.
- Exemplo: vendas de ar-condicionado e protetor solar aumentam juntas, mas a causa real é o clima quente.

---

## Como a Correlação é Medida?

- Símbolo: **r** (correlação de Pearson)
- Varia de **-1** a **1**:
  - **r = 1**: Correlação positiva perfeita
  - **r = -1**: Correlação negativa perfeita
  - **r = 0**: Sem correlação linear

| Valor de r            | Interpretação             |
|------------------------|----------------------------|
| 0.90 a 1 ou -0.90 a -1  | Correlação muito forte     |
| 0.70 a 0.89 ou -0.70 a -0.89 | Correlação forte     |
| 0.40 a 0.69 ou -0.40 a -0.69 | Correlação moderada |
| 0.20 a 0.39 ou -0.20 a -0.39 | Correlação fraca     |
| 0 a 0.19 ou 0 a -0.19   | Correlação muito fraca ou nenhuma |

---

## Condições para Correlação Linear

Antes de rodar uma análise de correlação:
- Variáveis **quantitativas**.
- Relação **linear**.
- Verificar **outliers**.

**Exemplo: Anscombe’s Quartet**:
- Gráficos que mostram a importância de visualizar os dados, não apenas calcular.

---

## O que é Regressão Linear?

A **regressão linear** também mostra a direção e força da relação, mas cria uma **linha de melhor ajuste** para prever Y a partir de X.

**Diferenças principais:**
- **Regressão**: Prediz Y a partir de X.
- **Correlação**: Trata X e Y de forma intercambiável.

---

## A Linha de Regressão

- **Visual**: Linha reta melhor ajustada no scatter plot.
- **Previsão**: Permite estimar valores futuros de Y dados X.

**Exemplo:**
- Prever preço de uma casa baseado na metragem quadrada.

**Equação do exemplo:**
```
Y = 113*X + 98,653
```
- **113**: Inclinação da linha (aumento por metro quadrado).
- **98,653**: Intercepto em Y (preço base sem metragem).

Para uma casa de 1500 pés quadrados:
```
Y = (113 * 1500) + 98653 = $268,153
```

> **Atenção:** Só use a regressão para previsões **dentro da faixa de dados coletados**.

---

## O Valor r²

- **r² (coeficiente de determinação)**: Mede quão bem a linha de regressão se ajusta aos dados.
- Se r² = 1, o ajuste é perfeito.
- **Exemplo**: r² = 0.70 → 70% da variação dos dados é explicada pelo modelo.

---

## Tabela: Diferenças Entre Correlação e Regressão

| Característica                  | Correlação                                 | Regressão                                 |
|----------------------------------|-------------------------------------------|-------------------------------------------|
| X e Y intercambiáveis            | Sim                                       | Não                                       |
| Mostra relação                   | Sim                                       | Sim                                       |
| Predição                         | Não                                       | Sim                                       |
| Medida usada                     | r                                          | r²                                        |
| Modelo                           | Não                                        | Sim (equação da linha)                   |

---

# Questionário (Resumo)

**1. True or False:** Linear regression uses X and Y as interchangeable values.  
✅ False

**2. What does the r-squared value indicate?**  
✅ How well the model fits your observations.

---
# O Propósito dos Gráficos

## Por que usamos gráficos?

- Gráficos nos ajudam a identificar padrões e relações em dados de maneira rápida.
- Exemplo: Conta de luz → Gráfico de consumo mais fácil de entender que uma tabela.
- Aplicações: negócios, apresentações, decisões informadas.

> “Uma boa visualização pode fazer mais do que apenas responder a perguntas; ela pode ajudar você a ver que há outras perguntas que você precisa responder.” — Steve Wexler

---

## Apresentações Enganosas de Dados

### Exemplo de Eixo Manipulado
- Alterar o eixo (não começando do zero) pode exagerar diferenças.
- Gráficos lado a lado mostram como o eixo pode enganar.

### Gráficos Enganosos São Comuns
- Encontrados em mídias sociais, jornais, relatórios.
- Sempre avalie a **fonte** dos dados.

---

## Conhecendo a Fonte

| Tópico | Propósito | Perguntas |
|:---|:---|:---|
| Quem | Verificar interesses e credibilidade | Quem criou? Quem pagou? Há conflito de interesse? |
| O quê | Entender o tipo de dado | Quais métodos de coleta? Tipos de dado? Amostra? |
| Onde | Avaliar o contexto | Dados de qual local? Fonte confiável? |
| Quando | Atualidade dos dados | Dados recentes? Frequência de coleta? |
| Por quê | Motivações por trás dos dados | Houve incentivo financeiro ou político? |

---

## Revisando os Números

### Valores de Resumo Comuns
- Soma
- Contagem
- Média
- Mediana
- Modo
- Faixa
- Mínimo
- Máximo

### Taxas e Porcentagens
- Não olhar apenas o número absoluto.
- Exemplo: 0,3% dos beneficiários do DACA tiveram condenações, não 100%!

### Cuidado com Dados Insuficientes
- Falta de contexto pode levar a interpretações erradas.

---

## Entendendo Eixos e Escalas

### Tipos de Escalas
- **Qualitativas**: Categorias (Alimentação, Moradia)
- **Quantitativas**: Valores numéricos (0, 5, 10...)

### Intervalos Consistentes
- Intervalos desiguais distorcem a percepção.

---

## Tipos de Gráficos

| Tipo de Variável | Tipo de Gráfico | Descrição |
|:---|:---|:---|
| Qualitativa | Gráfico de barras | Comparação entre categorias |
| Qualitativa | Gráfico de pizza | Partes de um todo |
| Quantitativa | Gráfico de dispersão | Relação entre duas variáveis |
| Quantitativa | Gráfico de linhas | Tendência ao longo do tempo |
| Quantitativa | Histograma | Distribuição de dados |
| Quantitativa | Boxplot (gráfico de caixa) | Percentis e valores discrepantes |

---

## Boas Práticas de Visualização

- Gráficos de barras devem começar em zero.
- Gráficos de linhas **podem** não começar do zero.
- Evitar múltiplos eixos se puder → risco de confundir.
- Escolher a visualização apropriada para o tipo de dado.

---

## Problemas Comuns em Gráficos

- **Gráficos 3D**: Dificultam interpretação correta.
- **Gráficos de bolhas**: Difíceis de comparar.
- **Gráficos de pizza**: Devem somar 100%, dificultam comparações visuais pequenas.

---

## Cores e Design

- Evitar excesso de cores.
- Usar esquemas de cores amigáveis para daltônicos.
- Focar no dado, não apenas no apelo visual.

---

## Interpretando Gráficos com Cuidado

- Sempre questione: falta contexto? Dados omitidos?
- Fazer boas comparações (como Edward Tufte recomenda).
- Verificar margem de erro e incerteza.

---

## Correlação Não Implica Causalidade

- Exemplo: Vendas de sorvete e óculos de sol → causadas pelo calor, não uma pela outra.

---

## Atenção às Palavras

- Cuidado com títulos emocionais.
- Verifique se os rótulos estão corretos.
- Analise se a linguagem influencia a interpretação.

---

## Lista de Verificação SCAM

- **S**: Fonte → De onde vêm os dados?
- **C**: Gráfico → Há práticas enganosas?
- **A**: Eixos → Começam do zero? Escala consistente?
- **M**: Mensagem → A interpretação é justa e precisa?

---

# Conclusão

- Gráficos são poderosos para comunicação e decisão.
- Aprenda a analisar com criticidade: fontes, contexto, margem de erro, causalidade.
- Compartilhe suas análises para melhorar a alfabetização de dados das pessoas ao seu redor.

---

# Recursos

- Trailhead: Variação para comparações de dados
- Trailhead: Correlação e Regressão
- Edward Tufte (2006): *Beautiful Evidence*
- Alberto Cairo (2016): *A Arte da Verdade*
- Alberto Cairo (2020): *How Charts Lie*
- Leo Yu-Hu Lo et al (2022): *Misled by Visualization*

---

# Questionário (Resumo)

**1. O que a lista de verificação SCAM avalia?**  
✅ Fonte, Gráfico, Eixos e Mensagem

**2. O que significa margem de erro?**  
✅ O nível de incerteza em uma estimativa

# Por que usamos gráficos? Um pouco de história

Os seres humanos vêm criando gráficos para visualizar dados há muito tempo. Mapas de cidades, como o mapa da cidade de Nippur (cerca de 1400 a.C.), já eram feitos há milênios. Manuscritos como os de Ptolomeu no século II usavam representações visuais para descrever princípios astronômicos.

Hoje, continuamos usando gráficos para representar dados e melhorar nossa capacidade de contar histórias com eles.

Pense no painel de um carro: você vê a velocidade, o nível de combustível, e recebe alertas sobre possíveis problemas. O design do painel é cuidadosamente pensado para mostrar os dados mais importantes no momento certo.

Da mesma forma, visualizações de dados ajudam a:
- Fazer comparações
- Ver tendências
- Monitorar situações e progresso
- Tirar conclusões para resolver problemas e tomar melhores decisões

# Tipos de Gráficos

Segundo o Cambridge Dictionary, gráficos são "desenhos que mostram informações de maneira simples, frequentemente usando linhas e curvas para representar quantidades".

Este módulo foca em:
- Graphs (gráficos de linhas, barras, dispersão, etc.)
- Maps (mapas)
- Tables (tabelas)

**Nota:** Diagramas não são abordados aqui.

# Gráficos ajudam a fazer e responder perguntas

## Faça boas perguntas

O módulo Fundamentos de Alfabetização de Dados mostra a importância de fazer as perguntas certas.  
Andy Cotgreave descreve em seu artigo *Find Hidden Insights in Your Data: Ask Why and Why Again* como interagir com gráficos e fazer novas perguntas leva a melhores ações.

## O Ciclo de Análise Visual (Visual Analysis Cycle)

O ciclo é:

1. Desenvolver insights  
2. Agir (compartilhar)  
3. Obter dados  
4. Escolher mapeamento visual  
5. Visualizar dados  

**Nota:** Confira o módulo *Detailed Data Analysis* no Trailhead para saber mais.

## Faça comparações

Exemplos de perguntas:
- Como o lucro mudou ao longo do tempo?
- Um produto é mais rentável que outro?
- Qual campanha de marketing funcionou melhor?

Gráficos ajudam a:
- Ver padrões e tendências
- Identificar outliers
- Melhorar a formulação de novas perguntas

# Gráficos como Arte

Visualizações podem ser funcionais e também artísticas.  
Exemplo: no Tableau Public, Asha Daniels representou a diminuição do número de leopardos com pontos pretos organizados como manchas.

# Boas Visualizações Exigem Bons Dados

Antes de criar gráficos, verifique:
- Se os dados são de alta qualidade
- Se são apropriados para responder sua pergunta

# Princípios para criar gráficos eficazes

## Atributos pré-atencionais

Atributos como comprimento, cor e posição são processados instantaneamente pelo cérebro.

| Atributo | Tipo de Percepção |
|:--|:--|
| Comprimento | Excelente para quantitativo |
| Matiz de cor (Hue) | Excelente para qualitativo |
| Posição 2D | Excelente para quantitativo |

Exemplo:  
- Bar charts (gráficos de barras) usam comprimento para destacar diferenças.  
- Bubble charts (gráficos de bolhas) usam tamanho, mas são mais difíceis de interpretar.

## Codificando Dados com Gráficos

- **Qualitativos:** melhor com cor, forma, agrupamento espacial
- **Quantitativos:** melhor com comprimento, posição 2D, intensidade de cor

# A base dos gráficos: Fazer comparações

O tipo de comparação e o tipo de dados determinam o melhor gráfico.

| Comparação | Pontos | Linhas | Barras | Caixas | Formas |
|:--|:--|:--|:--|:--|:--|
| Categorias nominais | ✅ |  | ✅ |  | ✅ |
| Séries temporais | ✅ | ✅ | ✅ | ✅ | |
| Ranking | ✅ | ✅ | ✅ |  | |
| Parte para o todo | ✅ |  | ✅ |  | ✅ |
| Desvio | ✅ | ✅ | ✅ |  | |
| Distribuição | ✅ | ✅ | ✅ | ✅ | |
| Correlação | ✅ | ✅ |  |  | ✅ |
| Geoespacial | ✅ | ✅ | ✅ | ✅ | ✅ |

# Tipos Comuns de Gráficos

## Comparações nominais

- **Bar charts:** comparar categorias
- **Hue e Shape:** distinguir categorias em scatter plots ou gráficos de linhas

## Séries temporais

- **Line charts:** mostrar tendências ao longo do tempo
- **Vertical bar charts:** enfatizar valores individuais
- **Box plots:** comparar distribuições ao longo do tempo

## Ranking

- **Bar charts:** barras ordenadas para fácil comparação
- **Dot plots:** usar pontos quando baseline zero não é necessário

## Parte para o todo

- **Stacked bar charts:** dividir a barra em partes (contagens ou percentuais)
- **Pie charts:** bons somente com poucas categorias e diferenças grandes
- **Area charts:** para mostrar parte-todo ao longo do tempo

## Desvios

- **Divergent bar charts:** mostram lucro ou prejuízo em relação a zero
- **Line charts:** mostrar variações ao longo do tempo

## Distribuições

- **Histograms:** agrupar valores em bins
- **Frequency polygons:** usar linhas conectando contagens
- **Strip plots:** mostrar cada ponto individualmente
- **Box plots:** compactar informações sobre a distribuição

## Correlações

- **Scatter plots:** mostrar relação entre duas variáveis
- **Trend lines:** visualizar padrão geral
- **Bubble charts:** adicionar uma terceira variável pelo tamanho das bolhas
- **Table lens:** comparar múltiplas métricas com base em uma categoria comum

## Quando detalhes são importantes

- **Tables:** comparar valores individuais
- **Highlight tables:** usar cor para destacar diferenças

# Comparações em Mapas

## Tipos de mapas:

- **Choropleth maps:** preencher regiões com cor baseada em valor
- **Symbol maps:** usar bolhas dimensionadas e coloridas
- **Density maps:** mostrar concentração de pontos de dados (mapas de calor)

# Apresentando a Mensagem

## Visualizações acessíveis:

- **Maximize a proporção de dados para tinta:** minimize decoração desnecessária (Edward Tufte)
- **Rotulagem e títulos claros:** unidades e categorias sempre visíveis
- **Compatibilidade com daltônicos:** evitar combinações vermelho/verde

## Cuidado com Gráficos Enganosos:

Utilize o checklist **SCAM**:
- **Source:** De onde vieram os dados?
- **Chart:** O gráfico é honesto?
- **Axes:** Os eixos são apropriados?
- **Message:** A mensagem é justa e correta?

Sempre se pergunte:
- Este gráfico mostra os dados da melhor forma possível?
- Há mais perguntas a serem respondidas?
- Estou considerando o contexto completo dos dados?

## Is Your Data AI-Ready?
# A importância dos dados para o sucesso da IA Agente

Qual é uma das ações mais importantes que você pode tomar para implementar com sucesso a IA agente? Se você respondeu "gerenciar dados", parabéns.

## Exemplos de problemas com dados

- Uma companhia aérea foi forçada a reembolsar um viajante após um bot fornecer informações incorretas sobre política de luto.
- Um bot disse a empreendedores de Nova York que era aceitável infringir certas leis.
- Uma IA acusou incorretamente um astro da NBA de vandalismo.

O que deu errado?  
Pode ter sido:
- Supervisão deficiente
- Falta de proteções adequadas
- **Problemas com os dados**: dados ruins, rotulados incorretamente, de fontes desconhecidas ou espalhados em vários sistemas.

Pesquisas mostram:
- Quase 6 em cada 10 usuários de IA acham difícil obter o que precisam da IA atual.
- Mais da metade não confia nos dados usados para treinar sistemas de IA.

Essa falta de confiança prejudica a adoção da IA e a competitividade.

## A importância da IA centrada em dados

**Agentes de IA** prometem remodelar o trabalho e o relacionamento com clientes, mas para isso precisam de:
- Dados precisos
- Dados atualizados
- Dados acessíveis
- Dados completos

Esse conceito é chamado de **IA centrada em dados**, baseada apenas em dados de qualidade.

# O que sua empresa pode fazer agora

## 1. Conectar suas fontes de dados

Conecte marketing, vendas, serviços e comércio em **um único registro atualizado em tempo real**.  
Assim, o agente de IA poderá acessar toda a amplitude de dados.

## 2. Garantir a qualidade dos dados

Remova:
- Duplicatas
- Discrepâncias
- Erros
- Outros fatores que possam prejudicar os resultados da IA

# Como conectar todos os dados da sua empresa

O acesso **em tempo real** a dados de qualidade é essencial, mas muitas empresas ainda têm dados:
- Em silos
- Em formatos variados
- Espalhados em vários sistemas

A falta de harmonização de dados é o segundo maior obstáculo para extrair valor dos dados.

## Solução: Salesforce Data Cloud

- Conecta dados estruturados e não estruturados numa plataforma unificada.
- Suporte para processamento de áudio e vídeo (ex: webinars, chamadas).
- Modelo de dados semântico para ajudar humanos e IA a interpretar dados de forma consistente.

Esses dados alimentam o **Agentforce**, conjunto de ferramentas de IA para agentes da Salesforce.

Exemplo:
- Um Agente de Serviço pode acessar e-mails antigos, tickets, mensagens de voz e mais para melhor atender o cliente.

# Estabelecendo bases para agentes de IA centrados em dados

Os dados **não precisam ser perfeitos**, mas **precisam ser limpos**:
- Sem erros
- Sem formatos inconsistentes
- Sem duplicatas
- Sem rótulos incorretos

## Modelo de limpeza de dados (segundo especialistas da Tableau)

### 1. Remover observações duplicadas ou irrelevantes

- Duplicatas surgem ao combinar conjuntos de dados.
- Dados irrelevantes (ex: dados de idosos em análise de hábitos da geração Y) devem ser removidos.

### 2. Corrigir erros estruturais

- Ex: "N/A" vs "não aplicável" — devem ser padronizados para análise precisa.

### 3. Filtrar valores discrepantes

- Analisar outliers para decidir se devem ser mantidos ou removidos.

### 4. Lidar com dados ausentes

Métodos:
- Remover observações com valores ausentes (perde-se informação).
- Preencher com base em outras observações (risco de suposições incorretas).
- Ajustar a análise para lidar com valores ausentes.

### 5. Validar os dados

Após a limpeza, pergunte:
- Os dados fazem sentido?
- Seguem regras adequadas?
- Confirmam ou refutam teorias?
- Ajudam a descobrir tendências?

# Na era da IA, os dados são preciosos

Em breve, os dados:
- **Não apenas apoiarão**, mas serão a espinha dorsal de sistemas e processos.
- **Impulsionarão decisões** e **ações em tempo real**, com supervisão humana.

As empresas de sucesso:
- Não apenas coletarão dados
- Integrarão dados com tecnologias para aproveitar novas oportunidades

**Dados são uma grande fonte de diferenciação competitiva.**

Segundo Rahul Auradkar, VP Executivo da Salesforce:

> "Nesta nova era de IA e agentes, os dados e metadados dos clientes são o novo ouro para a empresa."

## Data Management Best Practice Guide
 	
# Gerenciamento de Dados com a Salesforce

O gerenciamento de dados é fundamental para o sucesso de qualquer cliente com a Salesforce. Garantir a obtenção de dados úteis pode ajudar sua equipe a atingir seus objetivos e descobrir o que vem por aí para o seu negócio.

Abaixo, você encontrará trilhas de aprendizado no **Trailhead** (plataforma de aprendizado prática e gratuita da Salesforce), artigos de instruções e tutoriais em vídeo, todos elaborados por especialistas da Salesforce para ajudar você a assumir o controle dos seus dados.

## Crie uma estratégia de gerenciamento de dados

Uma estratégia de dados clara:
- Mantém sua organização no caminho certo
- Alinha sua equipe sobre como os dados serão coletados, revisados e usados
- Impulsiona metas de negócios

Esses recursos ajudarão você a identificar e evitar desafios comuns.

## Melhore a qualidade dos dados

A qualidade dos dados impacta:
- Rastreamento
- Relatórios
- Eficácia da implantação do Salesforce

Esses recursos ajudarão você a descobrir:
- Fatores que afetam a qualidade dos dados
- Como preparar sua equipe para o sucesso

## Importar dados

Importe seus dados existentes para o Salesforce para:
- Incluir registros anteriores em seus relatórios e rastreamentos

**Comece com:**
- Série de vídeos "Excluir dados de teste", para aprender a excluir dados de teste antes de carregar dados reais.
- Outros tutoriais que ensinam como importar dados corretamente.

## Manter e limpar dados

Conforme você importa e coleta dados, siga práticas recomendadas para:
- Manter os dados limpos a longo prazo
- Assegurar dados úteis, relatórios acionáveis e rastreamento preciso

## Vá além com o gerenciamento de dados

Use os recursos para:
- Obter orientação adicional
- Conectar-se com especialistas da Salesforce
- Avançar no gerenciamento de dados

---

# História de Caso: CloudKicks

**Sobre a empresa:**  
A CloudKicks fabrica tênis confortáveis, projetados e personalizados para seus clientes.  
Com o crescimento do negócio de varejo online, a empresa passou a usar o Salesforce para:
- Gerenciar processos de vendas
- Centralizar dados de clientes

**Desafio enfrentado por Linda Rosenberg:**  
Linda, administradora da CloudKicks, precisava:
- Configurar rapidamente o Salesforce para capturar novos dados de pedidos
- Importar dados históricos de planilhas para relatórios trimestrais

**O problema:**  
Após a primeira importação, os relatórios não batiam com os números das planilhas originais.

**A investigação:**  
Linda:
- Assistiu vídeos
- Leu materiais de orientação
- Explorou a Comunidade Trailblazer
- Descobriu causas potenciais como dados duplicados, dados incompletos e padrões inconsistentes

**A solução:**  
- Revisou e limpou entradas duplicadas nas planilhas
- Reimportou os dados
- Relatórios passaram a bater com os dados originais

**Lição aprendida:**  
- A facilidade de inserir dados errados
- A importância de um plano formal de gerenciamento de dados

**Ações tomadas:**  
Linda reuniu gerentes e executivos para:
- Formalizar regras de coleta, nomeação e mensuração de dados

**Resultados para a CloudKicks:**
- Equipe de vendas entende como e onde inserir dados
- Gerentes têm clareza sobre expectativas nos relatórios
- Executivos confiam nos dados para guiar as decisões de negócios


## Determine Data Requirements

# Determinar Requisitos de Dados

A preparação de dados é um processo de refinamento iterativo. À medida que você se aprofunda nos dados, novas pistas surgem. Descobertas podem fazer com que você reavalie suposições anteriores e ajuste sua implementação de preparação de dados de acordo.

> **Nota:** As histórias da Descoberta de Einstein agora são chamadas de modelos. Você pode ainda ver o nome antigo em alguns lugares.

## Requisitos de Dados do Einstein Discovery

- Necessário um conjunto de dados do CRM Analytics com pelo menos:
  - 1 variável de resultado
  - 2 variáveis explicativas ou preditoras
- Suporte para até 50 variáveis.
- Mínimo de 400 observações conhecidas.
- Suporte para até 20 milhões de observações.

> Saiba mais em: **Capacidades e Requisitos do Einstein Discovery**.

## Considere os Estados de Registro Anteriores

- Fontes como Salesforce armazenam apenas o estado atual do registro.
- Fontes de logs armazenam versões históricas.
- Para acessar dados anteriores:
  - Tire snapshots históricos.
  - Use campos personalizados para valores anteriores.

## Determine o Nível de Granularidade

- Pergunte: Qual nível de insight é interessante para o objetivo?
- Use **agrupamento** no Gerenciador de Dados para ajustar granularidade.
- **Erro comum:** Agregar dados em excesso.

**Exemplo:**  
Para entender efeitos do dia da semana, use dados no nível **diário**, não mensal.

## Determinar Prazos Relevantes

- Concentre-se em janelas de tempo específicas relevantes para a variável de resultado.
- Eventos mais próximos do resultado geralmente são preditores mais fortes.
- Para previsões, use variáveis disponíveis no momento da decisão.

**Exemplo:**  
Para inadimplência, use score de crédito no momento da solicitação, não eventos pós-aprovação.

## Decida Quantos Dados Obter

- Mais dados = mais precisão.
- Se houver mais ruído nos dados, mais linhas são necessárias.
- Mais valores possíveis por coluna → mais dados necessários.

**Exemplo:**
- 10.000 linhas com 2 gêneros = 5.000 observações por gênero.
- 10.000 linhas com 50 estados = 200 observações por estado.

## Considere a Série Temporal

- Para dados que mudam ao longo do tempo:
  - Reflita as sequências temporais nos dados e no modelo.
- Proporcione dados que representem a realidade, com a granularidade adequada.

## Pense Proporcionalmente

- Mantenha a proporção das variáveis equilibrada.
- Evite viés extraindo subconjuntos desbalanceados.

**Nota:**  
Conjuntos de dados grandes (milhões de linhas) têm menor risco de viés acidental.

## Forneça Resultados Conhecidos

- Einstein Discovery analisa em torno de um resultado específico (ex.: margem de vendas, taxa de fechamento).
- Dados devem ter resultados conhecidos.
- Dados sem resultado (ex.: negócio nem fechado nem perdido) são ignorados.

## Considere o Preconceito e a Imparcialidade

- Dados podem refletir práticas tendenciosas.
- O Einstein Discovery:
  - Detecta variáveis proxy e impactos díspares.
  - Permite filtrar variáveis sensíveis (gênero, idade).

**Ações:**
- Excluir dados tendenciosos durante a preparação.
- Consulte: **Detectar e Remover Viés de um Modelo**.
- Aprenda mais em: **Criação Responsável de Inteligência Artificial no Trailhead**.

## Analisar sem Overfitting ou Underfitting

| Problema       | Abordagem |
|----------------|-----------|
| **Sobreajuste** (Overfitting) | Usar muitos campos detalhados faz o modelo memorizar ruído e falhar em dados novos. Evite usando menos variáveis específicas. |
| **Subajuste** (Underfitting) | Modelo simples demais que não captura padrões dos dados. |

> **Equilíbrio é fundamental**: nem muitos detalhes nem simplicidade excessiva.

## Data Quality Dimensions Cheat Sheet

# O que são Dimensões de Qualidade de Dados?

**Qualidade de Dados** é uma medida do grau em que os dados são adequados à finalidade.  
Uma boa qualidade de dados gera confiança nos dados.

As **Dimensões de Qualidade de Dados** são medidas específicas de atributos da qualidade dos dados.

---

## Completude

**Definição:**  
A completude mede o grau em que todos os registros esperados em um conjunto de dados estão presentes.  
No nível dos elementos de dados, é o grau em que todos os registros têm dados preenchidos quando esperado.

**Exemplo de Completude:**  
- Todos os registros devem ter um valor preenchido no campo `CustomerName`.

---

## Validade

**Definição:**  
A validade mede o grau em que os valores em um elemento de dados são válidos.

**Exemplo de Validade:**  
- O valor `CustomerBirthDate` deve ser uma data no passado.  
- O valor `CustomerAccountType` deve ser "Empréstimo" ou "Depósito".  
- O valor `LatestAccountOpenDate` deve ser uma data no passado.

---

## Singularidade (Exclusividade)

**Definição:**  
A singularidade mede o grau em que os registros em um conjunto de dados não são duplicados.

**Exemplo de Singularidade:**  
- Todos os registros devem ter um `CustomerID` e um `CustomerName` exclusivos.

---

## Pontualidade

**Definição:**  
Pontualidade é o grau em que um conjunto de dados está disponível quando esperado.  
Depende de acordos de nível de serviço (SLAs) estabelecidos entre os recursos técnicos e comerciais.

**Exemplo de Pontualidade:**  
- Todos os registros no conjunto de dados de clientes devem ser carregados até às **9h**.

---

## Consistência

**Definição:**  
Consistência mede o grau em que os dados são os mesmos em todas as instâncias.  
Pode ser avaliada definindo um limite de variação aceitável entre conjuntos de dados.

**Exemplo de Consistência:**  
- A contagem de registros carregados hoje deve estar dentro de **+/- 5%** da contagem de registros carregados ontem.

---

## Precisão

**Definição:**  
Precisão mede o grau em que os dados refletem corretamente o valor real.

**Exemplo de Precisão:**  
- Todos os registros na **Tabela de Clientes** devem ter campos precisos (`Nome do Cliente`, `Data de Nascimento do Cliente` e `Endereço do Cliente`) quando comparados ao **Formulário de Imposto**.

---

