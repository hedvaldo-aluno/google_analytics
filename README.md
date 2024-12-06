# GOOGLE DATA ANALYTICS

**OBS: Para esse resumo, irei utilizar o seguinte caso: Imagine que você é um analista de dados contratado para ajudar uma loja de varejo a melhorar a gestão de estoque e minimizar produtos encalhados.**
## AS SEIS FASES DO PROCESSO DE ANÁLISE DE DADOS

1. **Perguntar**: Definir questões claras e relevantes que guiarão a análise.
    * Quais produtos têm maior risco de encalhe, e quais precisam de reabastecimento frequente?
    * Existem padrões sazonais que influenciam o estoque?
    * Quais categorias de produtos têm maior rotatividade?
    
2. **Preparar**: Coletar, limpar e organizar os dados necessários para a análise.
    * Coletar dados de vendas, estoque atual, pedidos anteriores e feedback de clientes.
    * Organizar esses dados em planilhas ou bancos de dados.
    * Limpar o conjunto, removendo entradas duplicadas ou inconsistentes, como produtos com identificadores     inválidos.

3. **Processar**: Transformar os dados em um formato utilizável, aplicando técnicas de manipulação e integração.
    * Calcular métricas-chave, como a taxa de rotatividade de produtos e os dias médios em estoque.
    * Integrar dados de vendas com dados de tendências sazonais.
    * Criar novas colunas com informações úteis, como margens de lucro por produto.

4. **Analisar**: Utilizar métodos estatísticos e ferramentas analíticas para examinar os dados e extrair insights.
    * Identificar produtos com baixa rotatividade ou queda nas vendas.
    * Encontrar correlações entre vendas e sazonalidade.
    * Agrupar os produtos por categorias e analisar quais apresentam melhor desempenho.

5. **Compartilhar**: Comunicar os resultados de forma eficaz, utilizando visualizações e relatórios.
    * Criar visualizações, como gráficos de barras para produtos encalhados e linhas para tendências de vendas ao longo do tempo.
    * Elaborar um relatório com as recomendações, destacando produtos que devem ser promovidos ou retirados do catálogo.

6. **Agir**: Tomar decisões informadas com base nos insights obtidos e implementar ações que gerem valor.
    * Implementar promoções para produtos encalhados.
    * Ajustar o calendário de pedidos para priorizar itens de alta demanda.
    * Planejar estratégias sazonais, como aumentar o estoque de itens populares em determinadas épocas.

## CICLO DE VIDA DOS DADOS
1. **Planejamento**: Definir como os dados serão coletados e gerenciados.
    * Definir quais dados serão necessários, como vendas diárias, produtos em estoque, sazonalidade e histórico de promoções.
    * Planejar a coleta de dados integrando sistemas de ponto de venda (PDV) e de gestão de estoque.

2. **Captura**: Recolher dados de diversas fontes.
    * Coletar dados de vendas diretamente do sistema PDV, registros de entrada e saída de mercadorias e feedback de clientes sobre produtos.
    * Agregar dados externos, como tendências de mercado e relatórios de concorrentes, se relevante.

3. **Gerenciamento**: Armazenar e manter a integridade dos dados.
    * Armazenar os dados em um banco de dados centralizado e organizado por categorias, como tipo de produto, localização da loja e datas de vendas.
    * Garantir que os dados sejam atualizados regularmente e protegidos contra acesso não autorizado.

4. **Análise**: Examinar os dados para descobrir padrões e insights.
    * Identificar padrões de vendas para produtos com alta e baixa rotatividade.
    * Usar análises preditivas para prever demanda futura e planejar estratégias de reabastecimento e descontos.

5. **Arquivo**: Armazenar dados que não são mais utilizados ativamente, mas que podem ser relevantes no futuro.
    * Arquivar os dados de vendas e estoque de períodos anteriores para fins de referência histórica e análises de longo prazo.
    * Garantir que os dados arquivados sejam organizados para permitir acessos rápidos, caso necessário.

6. **Destruição**: Eliminar dados que não são mais necessários, garantindo a conformidade com regulamentos e políticas de privacidade.
    * Realizar a destruição de dados com segurança para evitar vazamentos ou uso indevido.

## METODOLOGIA SMART

1. **Específica (Specific)**:  A pergunta deve ser clara e bem definida.
    * Identificar os produtos com maior tempo no estoque e determinar ações para reduzir o volume de itens encalhados.

2. **Mensurável (Measurable)**:  Deve ser possível quantificar a resposta ou resultado.
    * Monitorar a redução do estoque de produtos encalhados em 20% no período de 3 meses.

3. **Orientada para a Ação (Actionable)**:  A resposta deve fornecer informações que podem levar a ações concretas.
    * Implementar promoções direcionadas para itens com baixa rotatividade e ajustar os pedidos futuros com base nos padrões de vendas.

4. **Relevante (Relevant)**:  A pergunta deve ser pertinente ao contexto e objetivos do projeto.
    * Melhorar a gestão do estoque é crucial para reduzir custos de armazenamento e aumentar o capital disponível para novos produtos.

5. **Com Tempo Definido (Time-bound)**:  Deve haver um prazo claro para a resposta ou análise, permitindo foco e eficiência.
    * A análise e implementação das ações devem ser concluídas dentro de 6 semanas, com resultados iniciais avaliados no final de 3 meses.
  
## CRIANDO UM DATA STORYTELLING

1. **Definir o Objetivo** 
    * Qual mensagem você quer transmitir?
    * Que decisão ou ação você espera que seu público tome?

2. **Entender o Público**
    * Quem vai consumir a história?
    * Quais são os níveis de familiaridade deles com o tema e os dados?

3. **Analisar os Dados**
    * Limpe, organize e processe os dados para garantir precisão e relevância.
    * Identifique padrões, outliers e correlações significativas.

4. **Escolher a Visualização Certa**
    * Utilize gráficos apropriados para cada tipo de dado.
    * Evite sobrecarregar a visualização com informações irrelevantes.

5. **Criar a Narrativa**
    * Conte uma história com introdução, desenvolvimento e conclusão.
    * Conecte os insights aos objetivos e proponha ações baseadas nos dados.

6. **Refinar e Testar**
    * Reavalie a clareza e impacto da sua história.
    * Peça feedback e ajuste conforme necessário.
  
## MODELAGEM DE DADOS

Modelagem de dados é o processo de criação de diagramas que representam visualmente como os dados são organizados e estruturados, conhecidos como **modelos de dados**. Assim como a planta de uma casa ajuda diferentes profissionais a entenderem sua estrutura, os modelos de dados ajudam usuários com diferentes necessidades a compreender a estrutura geral dos dados.

### NÍVEIS DE MODELAGEM DE DADOS

1. **Conceitual**  
   * Visão geral de alto nível, mostrando como os dados interagem na organização.  
   * Focado em requisitos de negócios, sem detalhes técnicos.  

2. **Lógico**  
   * Aborda detalhes técnicos como entidades, atributos e relacionamentos.  
   * Define como registros são identificados, mas não inclui nomes reais de tabelas ou colunas.  

3. **Físico**  
   * Mostra como o banco de dados opera, incluindo nomes de tabelas, colunas e tipos de dados.  

---

### TÉCNICAS DE MODELAGEM DE DADOS

1. **Diagrama ERD (Entity Relationship Diagram)**  
   Representa visualmente o relacionamento entre entidades no modelo de dados.  

2. **Diagrama UML (Unified Modeling Language)**  
   Descreve a estrutura detalhada de um sistema, incluindo entidades, atributos e relacionamentos.  

---

### IMPORTÂNCIA DA ANÁLISE DE DADOS

- Facilita o entendimento dos dados e sua relação nos sistemas de informação.  
- Melhora a colaboração e alinhamento entre equipes.  
- Ajuda a mapear dados com base em análises, garantindo que sejam organizados e estruturados de maneira útil para os objetivos da organização.  

---

## DADOS LARGOS (WIDE DATA)

### ESTRUTURA
Cada variável é representada em uma coluna, e cada linha representa uma unidade ou entidade.

**Exemplo**:  
| Cliente | Jan | Fev | Mar |  
|---------|-----|-----|-----|  
| A       | 100 | 150 | 200 |  
| B       | 80  | 120 | 140 |  

### CARACTERÍSTICAS
- Facilita a leitura direta para relatórios ou dashboards.  
- Usado em situações onde todas as variáveis para cada entidade são importantes para a análise.  

### VANTAGENS
- Mais intuitivo para visualizações simples.  
- Ideal para análises descritivas.  

### DESVANTAGENS
- Difícil de expandir se novas variáveis forem adicionadas.  
- Algumas ferramentas estatísticas ou de aprendizado de máquina preferem dados longos.  

---

## DADOS LONGOS (LONG DATA)

### ESTRUTURA
Cada observação é registrada em uma linha separada, com colunas que indicam a variável e seu valor.

**Exemplo**:  
| Cliente | Mês | Gasto |  
|---------|-----|-------|  
| A       | Jan | 100   |  
| A       | Fev | 150   |  
| A       | Mar | 200   |  
| B       | Jan | 80    |  
| B       | Fev | 120   |  
| B       | Mar | 140   |  

### CARACTERÍSTICAS
- Usado frequentemente para análises estatísticas e machine learning.  
- Facilita a agregação ou transformação de dados.  

### VANTAGENS
- Ideal para análise de séries temporais e regressões.  
- Compatível com ferramentas analíticas como Python, R e bibliotecas como tidyverse.  

### DESVANTAGENS
- Mais difícil de interpretar diretamente.  
- Pode gerar tabelas maiores, dependendo do número de observações.

# ÉTICA DE DADOS E RESPONSABILIDADE

Mais do que evitar danos, a ética em dados deve buscar o bem (**beneficência**) e melhorar a vida das pessoas, reconhecendo que os dados representam indivíduos reais.

---

## PROTEÇÃO E CONTROLE

- **Prioridade à privacidade:** Garantir que os usuários tenham controle sobre suas informações.  
- **Opções de controle:** Implementar consentimento, revogação e exclusão dos dados de forma acessível e transparente.

---

## O FUTURO DA ÉTICA EM DADOS

- **Crescimento exponencial:** Com o aumento do volume de dados, questões éticas são cada vez mais relevantes.  
- **Capacitação dos usuários:** Tornar os usuários mais informados e no controle de seus dados é uma necessidade crescente.

---

# PRIVACIDADE DE DADOS

## DEFINIÇÃO
Refere-se à proteção das informações e atividades pessoais durante transações de dados, garantindo que o acesso, uso e coleta sejam responsáveis.  

## DIREITOS
Incluem o direito legal dos indivíduos de controlar seus próprios dados.  

## IMPORTÂNCIA E ABERTURA
1. **Confiança:** A privacidade depende da confiança; as pessoas devem acreditar que suas informações serão tratadas com responsabilidade.  
2. **Dados abertos:** Discussões sobre acesso, uso e compartilhamento livre de dados precisam equilibrar transparência com proteção individual.  

---

# ANONIMIZAÇÃO DOS DADOS

## DEFINIÇÃO
Processo de proteger informações sensíveis ao remover ou alterar elementos que identificam diretamente um indivíduo, como nome, endereço ou CPF.  

## TÉCNICAS
Inclui métodos como ocultação, hash ou mascaramento, que dificultam rastrear ou identificar uma pessoa.  

## IMPORTÂNCIA 
1. **Setores Críticos:** Utilizada amplamente em setores como saúde e finanças, onde a privacidade é essencial.  
2. **Proteção de Privacidade:** Garante segurança individual e conformidade com regulamentações de dados em um mundo cada vez mais baseado em informações.  

---

# CONSIDERAÇÕES ÉTICAS EM IA

## PRECONCEITOS
- Algoritmos podem perpetuar injustiças se treinados com dados enviesados, prejudicando comunidades sub-representadas.  

## USO ÉTICO 
- Sistemas de IA devem ser aplicados com responsabilidade, especialmente em decisões críticas, como concessão de crédito e curadoria de conteúdo.  

---

# EDUCAÇÃO E COLABORAÇÃO

1. **Capacitação:** Desenvolvedores e usuários precisam entender as práticas responsáveis para reduzir riscos.  
2. **Trabalho conjunto:** A colaboração entre pesquisadores, profissionais e comunidades é vital para criar soluções éticas.  

---

# IA RESPONSÁVEL

- **Benefícios Amplos:** A IA tem o potencial de melhorar vidas em diversas áreas.  
- **Desenvolvimento Ético:** Um compromisso coletivo garante que esses benefícios sejam acessíveis e que danos sejam minimizados.  

# BANCOS DE DADOS RELACIONAIS

- **Utilização:** Utilizam tabelas interconectadas para gerenciar e analisar dados de forma eficiente.  
- **Relações:** Relações são estabelecidas por campos comuns entre as tabelas, permitindo conexões e consultas de dados interligados.  

---

## CHAVES PRIMÁRIAS

- **Definição:** São identificadores únicos para cada linha de uma tabela, garantindo a integridade dos dados.  
- **Importância:** Cruciais para estabelecer relações consistentes entre diferentes tabelas.  

---

## CHAVES ESTRANGEIRAS

- **Definição:** Funcionam como pontes, referenciando a chave primária de outra tabela para criar vínculos.  
- **Função:** Facilitam a associação de dados relacionados, permitindo acessar informações distribuídas em várias tabelas.  

---

# O QUE É METADATA?

- **Definição:** Metadata é a informação que descreve os dados, como a data em que uma foto foi tirada ou o remetente de um e-mail.  
- **Importância:** Não é o dado em si, mas ajuda a entender e utilizar os dados de forma eficaz.  

---

## TRÊS TIPOS DE METADATA PARA ANALISTAS DE DADOS

1. **Metadata Descritiva:** Identifica os dados, como o título ou ISBN de um livro.  
2. **Metadata Estrutural:** Mostra como os dados estão organizados, como capítulos de um livro ou a relação entre diferentes versões de um documento.  
3. **Metadata Administrativa:** Fornece detalhes técnicos, como tipo de arquivo, data de criação, entre outros.  

---

## IMPORTÂNCIA DO METADATA

- Muitas empresas enfrentam desafios para utilizar seus dados devido a inconsistências na organização entre diferentes sistemas.  
- **Função da Metadata:** Atua como uma fonte centralizada de informações sobre os dados, incluindo sua localização e conexões entre sistemas.  

---

## GOVERNANÇA DE DADOS E ESPECIALISTAS EM METADATA

- **Governança de Dados:** Gerencia formalmente os ativos de dados, abordando questões de segurança, privacidade e usabilidade.  
- **Especialistas em Metadata:** Desempenham um papel crucial na organização, padronização e manutenção da qualidade e acessibilidade dos dados.  

---

## CARREIRA DE ANALISTA DE METADATA

- **Função:** Analistas de metadata ajudam as empresas a entender seus dados e tomar decisões informadas.  
- **Ideal para quem:** É uma carreira ideal para quem tem paixão por explorar dados e torná-los acessíveis a outros.  

---

## TIPOS DE DADOS

1. **Dados Internos (Primários):** Gerados dentro de uma organização, encontrados em sistemas próprios da empresa.  
2. **Dados Externos (Secundários):** Provenientes de fontes externas, como outras empresas, governos ou bancos de dados públicos.  

---

## ACESSO AOS DADOS

- **Dados Internos:** Obtidos de diferentes departamentos internos.  
- **Dados Externos:** Disponíveis por meio de iniciativas de dados abertos, como o portal Data.gov nos EUA, que promove transparência e inovação.  
