# 1. Habilidades de um analista de dados
- **Curiosidade (Curiosity):** ato de aprender algo novo. Buscar o porquê e o onde de tal coisa. Ex: faturamento caiu em 10%, por que caiu? Quando?
- **Entendendo o contexto (Context):** ver a imagem inteira. Bater o olho e ver que um dado está fora do contexto. Como um telefone no campo de CEP ou um coringa em um jogo de cartas sem ele.
- **Mentalidade técnica (Technical Mindset):** capacidade de fatiar um problema grande em menores. Se a empresa quer aumentar o faturamento, o analista vai:
    - Analisar faturamento do ano passado;
    - Identificar top 5 clientes;
    - Cruzar com os produtos mais comprados.
- **Design de dados (Data Design):** organizar os dados de forma estruturada. É a habilidade de projetar a informação para ser útil.
- **Estratégia de dados (Data Strategy):** visão de liderença, gerencia as pessoas (todos sabem ler seu gráfico), cria processos (evita gargalos ou passos repetitivos) e escolhe ferramentas certas (usar excel, python ou sql pra X tarefa).

---

# Aplicando as habilidades analíticas
- Uma produtora lançou filmes recentes que não tiveram tanto impacto. Foram filmes ruins que deram prejuízo. Notaram que estúdios concorrentes se recuperaram de uma crise semelhante lançando remakes.
- Contrataram um analista pra realizar uma Analise Exploratória de Dados (EDA) para entender o que o público gostou no passado e tentar replicar o sucesso.

### 1. OBJETIVOS DO PROJETO
- Identificar fatores chaves para o sucesso de um filme no final de semana de estreia;
- Entender a relação entre orçamento de um filme e sua receita;
- Determinar quais gêneros de filmes são mais rentáveis.

### 2. Conjunto de dados disponíveis
- Nome;
- Data de lançamento;
- Receita da noite de estreia;
- Receita do final de semana de estreia;
- Orçamento (custos);
- Custos de marketing;
- Avaliações (ratings);
- Gênero.

---

## Aplicando habilidades
**1. Curiosidade:** se aumentar o orçamento do filme tem mais bilheteria na estreia? Será que precisa de novas colunas no banco como dados demográficos de quem comprou o ingresso?

**2. Contexto:** feriados afetam a receita. Filmes infantis faturam muito mais nas férias. Sem o contexto sua análise sobre por que um filme infantil falhou na Europa em detemrinada data estará distorcida.

**3. Mentalidade técnica:** como você vai limpar, organizar e arrumar esse banco de dados (células vazias ou valores errados) antes de qualquer conclusão

**4. Design de dados:** pega a planilha e aplica agrupamentos lógicos, organiza os dados de receita e depois por gênero. Essa simples escolha pode revelar que comédias tem margens de lucro maiores que dramas.

**5. Estratégia de dados:** se a produtora quer um relatório simples com poucos dados estáticos, usar excel. Se a diretoria quer um dashboard em tempo real que atualize os números da bilheteria ao vivo, usar power BI ou tableu. Exemplo de tempo: direcionar esforços para rodar primeiro as análises que vão impactar o cronograma de filmagens do próximo trimestre

---

> **O Problema (A missão):** O estúdio está fazendo filmes ruins e perdendo dinheiro. Eles querem que você olhe o passado para prever quais filmes darão lucro no futuro.

- **Curiosidade em ação:** É você olhando para a tabela e dizendo: "Poxa, será que gastar o triplo com os atores famosos realmente aumentou a bilheteria na estreia?"
- **Contexto em ação:** É você lembrando que não adianta olhar só para o faturamento de filmes infantis sem cruzar isso com o calendário de férias escolares, senão o seu relatório estará enviesado.
- **Mentalidade Técnica em ação:** É não entrar em pânico com o tamanho do problema. Você divide ele começando pela etapa chata: procurar furos e células vazias na planilha de orçamento antes de fazer os gráficos bonitos.
- **Design de Dados em ação:** É usar seu bom senso para organizar a planilha. Se você ordenar primeiro pela coluna "Receita" e depois pela "Gênero", talvez descubra ali mesmo que comédias dão muito mais lucro que dramas.
- **Estratégia de Dados em ação:** É a sua gestão de recursos. Se os diretores do estúdio querem a resposta só no mês que vem, você pode usar uma ferramenta X. Se eles quiserem ver o painel atualizando todos os dias com a bilheteria global, você terá que usar o Tableau (ou Power BI).

---

# 2. Pensamento analítico
- Envolve identificar e definir um problema, em seguida, resolvê-lo usando dados de maneira organizada e estruturada

- **1. Visualização (Visualization):** representação gráfica das informações (gráficos, tabelas dinâmicas e mapas). Visualização ajuda a entender o cenário e explicar os dados;
- **2. Estratégia (Strategy):** Ajuda a ver o que você quer alcançar e como vai chegar lá. Garante que não perca tempo coletando lixo, garabte que todos os dados processados são úteis pra meta.
- **3. Orientação a problema (Problem-orientation):** Identificar, descrever e resolver problemas, mantendo o problema inicial no topo da mente do projeto.
    - Ex: armazém sem suprimenetos, você testa várias ferramentas e métricas mas o alvo no fim será sempre garantir que o estoque esteja cheio. Para se manter orientado analistas fazem muitas perguntas ao cliente.
- **4. Correlação (Correlation):** capacidade de identificar relação entre dois ou mais pedaços de dados que pareciam isolados. Exemplo: estação de chuva aumenta as vendas de guarda-chuvas. ATENÇÃO: correlação não significa causalidade. Dois dados que crescem ou caem na mesma direção nem sempre estão relacionados.
- **5. Pensamento macro e micro (Big-picture and detail-oriented thinking):** 
    - **Macro:** olhar o quebra cabeça pronto. Vê imagem completa da empresa, enxerga oportunidades e inovações sem travar em uma peça chata. Diminui o zoom e ver o mercado;
    - **Micro:** foco em encaixar as peças perfeitamente. Ajuda a descobrir todos os aspectos que farão o plano funcionar sem erros.

---

# 3. Principais habilidades analíticas
- **Pensamento analítico:** processar dados com lógica;
- **Pensamento crítico:** descobrir quais são as perguntas certas a serem feitas;
- **Pensamento criativo:** propor respostas novas, fora da caixa e inesperadas.

## 3 perguntas principais

### 1. Qual a causa raíz do problema? (root cause)
- **5 Porquês** (perguntar por que 5 vezes):
    - Por que não pode aumentar o salário dos funcionarios? R: falta orçamento
    - Por que falta orçamento? R: gastos em manutenção
    - Por que há tanto gasto em manutenção? R: problemas frequentes
    - Por que há problemas frequentes? R: os matunedores colocam peças baratas que não possuem boa qualidade
    - **PROBLEMA REAL:** o problema não é a empresa que não quer aumentar o salário dos funcionários, mas sim os profissionais da manutenção que não realizam o serviço com peças de qualidade.

### 2. Onde estão as lacunas do nosso processo?
- **Análise de lacunas (gap analysis):** método de comparar "Onde estamos agora" (estado atual) com "Onde queremos chegar?" (estado futuro)
- Ao identificar o tamanho e forma da lacuna o analista consegue desenhar um plano de ação para que a empresa consiga atravessar do estado atual até o objetivo de forma eficiente.

### 3. O que nós NÃO consideramos antes?
- Serve como **auditoria**. Parar tudo e pensar de forma crítica quais informações, variáveis ou públicos podem ter ficado de fora do processo. Fazer isso evita surpresas negativas e garante estratégias mais seguras.

---

# 4. Usando os 5 por quês
A técnica dos Cinco Porquês (Five Whys) é uma ferramenta de raciocínio simples e poderosa para isso: basta perguntar "Por quê?" repetidamente até que a verdadeira causa se revele (na média, isso ocorre no quinto "por que", mas pode variar).

### Estudo de Caso 1: Reclamações de Clientes (Supermercado Online)
**1. Por que as entregas estão ruins?** 
- (após filtrar dados do SAC): Maioria reclamava que os produtos chegavam amassados

**2. Por que chegava amassado?** 
- (lendo texto das reclamações): Clientes citavam caixas mal embaladas;

**3. Por que os produtos estão mal embalados?** 
- (investigar a operação no galpão): Empacotadores não aplicam procedimentos corretos

**4. Por que os empacotadores não aplicam procedimentos corretos?**
- (puxar dados do RH): 35% de todos os empacotadores no turno eram recém-contratados, não tinham concluído o treinamento oficial

**5. Por que trabalham mesmo sem treinamento obrigatório?**
- **ROOT:** Departamento do RH tá reformulando sistema de treinamento, como medida palitativa, forneceu um guia rápido inútil de uma página para os novatos.

> **Solução:** analista apresentou os dados para a diretoria, que interviu, cobrou o RH e exigiu reciclagem de todos os novatos.

### Estudo de Caso 2: Controle de Qualidade (Fábrica de Irrigação)
- Fábrica notou aumentou drástico de defeito nas bombas de água.

**1. Por que houve aumento nos defeitos?** 
- (Pós reunião com engenheiros): máquinas da linha de montagem estavam cortando as peças descalibradas.

**2. Por que as máquinas estão descalibradas?**
- Problema começou logo após último ciclo de manutenção. Mal calibradas pelos técnicos

**3. Por que foram mal calibradas na manutenção?**
- (Pós investigar o manual): método de calibração atual era inadequado para aquelas máquinas

**4. Por que o método ficou inadequado?**
- Empresa instalou novo software nas máquinas. Os técnicos não perceberam que a atualização alterava os padrões de calibração física

**5. Por que os técnicos não sabiam as novas regras de calibração?**
- **ROOT:** Equipe de TI atualizou os computadores mas esqueceu de enviar manual PDF com as novas instruções de calibração.

> **SOLUÇÃO:** manual antigo foi descartado e o novo foi imediatamento impresso e entregue.

---

# 5. Dados impulsionam bons resultados
- **Data-Driven Decision-Making** usa fatos reais para guiar a estratégia de um negócio. Permite validar teorias, entender oportunidades, traçar planos precisos e ter mais segurança na escolha.
- **Exemplo do RH:**
    - Um presidente de uma empresa quer descobrir qual benefício corporativo mais valorizam para investir dinheiro nisso. RH diz que os funcionários preferem trabalhar de chinelo. Diretor afirmou isso por achismo, baseado no que viu no escritório. Clássico *gut feeling*. A empresa conduziu uma pesquisa estruturada em dados. Resultado revela que benefício mais desejado era um vale transporte gratuito. A intuição do diretor falhou por que ele anda de carro. Visão de mundo limitada

### As 5 habilidades:
**1. Curiosidade e contexto:** duvidar da primeira resposta e investigar os padrões. O contexto é vacina contra a bolha, nem todos os funcionários vão trabalhar de carro;
**2. Mentalidade técnica:** analista não deve ignorar intuição, mas deve se basear em dados. Um presentimento sobre o mercado deve fazer o analista ir atrás de fatos e números pra provar ou refutar a hipótese.
**3. Design de dados:** estruturar banco de forma organizada e lógica para que não haja dúvidas sobre os resultados
**4. Estratégia de dados:** tomar decisões baseadas em dados. A estratégia é a visão de alto nível que garante que você usa a tecnologia certa e que conveça o resto da empresa a confiar nos relatórios e agir.

---

# 6. Impacto dos dados

### CASO 1: RH do Google
- Houve uma época em que o RH perguntou: os gerentes agregam algum valor na empresa? Ou deveriamos acabar com os chefes e deixar todo mundo trabalhar como contribuidor individual?
- **1. Primeira análise:**
    - Cruzaram avaliações de desempenho;
    - Plotaram em um gráfico;
    - Visual revelou que equipes com melhores gerentes são mais felizes, produtivas e tinham intenção de continuar no google;
    - Conclusão: bons gerentes importam.
- **2. Aprofundamento:** Saber que importam não é o bastante. O que faz deles bons gerentes? Equipe precisa de mais dados
    - Lançam programa de indicação (vote no gerente favorito e justify);
    - Entrevista os gerentes que ficam no topo e no fundo do gráfico.
- **3. Ação (act):** descobriram padrões comportamentais exatos que diferenciavam sucesso do fracasso. Com isso criaram sistema de avaliação oficial baseado nesses fatos. Graças ao data-driven a cultura do google se solidificou.

### CASO 2: ONGs
Organizações sem fins lucrativos dependem do engajamento do público para sobreviver. Jornalistas escrevem matérias sobre essas causas na esperança que o leitor vire voluntário
- **Dúvida:** como o jornalista sabe se o texto realmente convenceu a pessoa?
- **Solução analítica:** analistas de dados usam rastreados (trackers) para monitorar quais tópicoss de texto geravam mais cliques, retenção, comentários, compartilhamentos e direcionamentos para site de doação.
- **Resultado:** informações compiladas pelos analistas fizeram com que recomendassem aos jornalistas focar nos temas exatos e as abordagens textuais que mais batiam na emoção do leitor.

---

# Questões + Gabarito

**1. O seu resumo fala sobre "Correlação" dentro do Pensamento Analítico (Ex: a chuva aumenta as vendas de guarda-chuvas). Mas há um aviso CRUCIAL de atenção lá. Qual é a regra fundamental sobre correlação?**
- a) A correlação prova exatamente qual é a causa raiz de um problema.
- b) Correlação NÃO significa causalidade. Dois dados que crescem na mesma direção nem sempre estão diretamente ligados (um não necessariamente causa o outro).
- c) A correlação serve apenas para dados financeiros no Power BI.
- d) Se dois dados não crescerem ao mesmo tempo, a planilha está errada.

**2. A "Análise de Lacunas" (Gap Analysis) serve para traçar um plano de ação eficiente e é focada em responder qual grande pergunta de negócios?**
- a) O que nós NÃO consideramos antes?
- b) Qual é a causa raiz desse problema financeiro?
- c) Onde estamos agora (estado atual) comparado a onde queremos chegar (estado futuro)?
- d) Como automatizar a limpeza dos dados nulos?

**3. Um Analista de Dados de alto nível não pode ser um "robô" lógico, ele precisa misturar 3 tipos de pensamento. Qual deles é descrito como a capacidade de "propor respostas novas, fora da caixa e inesperadas"?**
- a) Pensamento Crítico (para fazer boas perguntas).
- b) Pensamento Criativo.
- c) Pensamento Analítico (para processar dados com lógica).
- d) Pensamento Estratégico.

**4. Pergunta Aberta (Discursiva): Seu resumo aborda perfeitamente o "Pensamento Macro" (ver a imagem completa) e o "Pensamento Micro" (foco em encaixar perfeitamente cada peça pequena). Na prática corporativa, o que aconteceria com o analista se ele tivesse APENAS o Pensamento Micro? Qual seria a grande falha no trabalho dele?**
- **R:** o problema é que focar só no micro (parte do problema) pode acabar gerando resultados enviesados ou que não fazem muito sentido dentro do contexto da empresa

### Respostas Corretas e Comentários:
- **1. Letra B - Correto.** Essa é a "casca de banana" mais comum da área de dados. O clássico exemplo: No verão, as vendas de sorvete sobem e os ataques de tubarão também sobem (ambos estão no mesmo gráfico, há uma correlação). Significa que tomar sorvete atrai tubarões? Não! É apenas uma correlação estatística por causa do calor, não uma causalidade.
- **2. Letra C - Exato.** A Análise de Lacunas (Gap Analysis) é literalmente a construção da "ponte". Onde estou, onde quero estar, e o que falta (lacuna) para eu chegar lá.
- **3. Letra B - Perfeito.** É o lado "artista" do analista. Olhar para os mesmos números que todo mundo já viu e pensar em uma solução que ninguém na sala de reuniões havia sugerido.
- **4. Resposta Aberta - Precisão cirúrgica.** Você tocou na palavra-chave: Contexto. Um analista puramente "micro" conserta os problemas técnicos de uma planilha e cria um gráfico perfeitamente calculado, mas que não serve pra nada comercialmente, pois ele não viu o cenário "macro" de que a empresa havia mudado de estratégia na semana passada. O macro te dá o mapa da floresta, o micro te ensina a cortar a árvore. É preciso ter os dois.
