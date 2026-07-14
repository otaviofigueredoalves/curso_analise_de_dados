# Resumo Geral Definitivo: As 6 Etapas da Análise de Dados
*(Mesclado: Etapas 2, 3 e 4)*

O ciclo de vida de um projeto de dados segue o framework do Google. Todo o conteúdo aprendido (ferramentas, habilidades e teorias) se encaixa em uma destas seis fases:

## 1. ASK (Perguntar)
**A fase de definição do problema, do escopo e do contexto para alcançar a finalidade.**
- **O Papel:** O analista identifica a necessidade real do negócio e foca em resolver o problema certo. Tudo começa definindo o problema (ex: melhorar reconhecimento de marca, resolver insatisfação do RH).
- **Habilidades em Ação:** 
    - **Curiosidade:** Buscar o porquê e onde algo aconteceu.
    - **Pensamento Crítico:** Descobrir as perguntas certas.
    - **Orientação ao Problema:** Manter a meta inicial no topo da mente.
- **Ferramentas de Raciocínio (As 3 Perguntas):**
    1. *Qual a causa raiz?* Uso da técnica dos **5 Porquês**.
    2. *Onde estão as lacunas?* Uso da **Gap Analysis** (onde estamos vs onde queremos chegar).
    3. *O que não consideramos?* Auditoria mental para evitar viés.

## 2. PREPARE (Preparar)
**A fase de definição do plano de coleta, regras de acesso e separação do que será útil.**
- **Geração e Coleta:** Planejar como os dados serão gerados e quais conjuntos de dados (Datasets) estão disponíveis.
- **Segurança e Ética:** Definir métricas, estabelecer regras de acesso sigiloso, garantir o consentimento (compliance) e prevenir possíveis problemas antes da coleta.
- **Ecossistema:** Onde tudo fica guardado. É formado por Hardware (cloud/servidores), Software (ferramentas) e Pessoas. É aqui que o analista planeja onde os dados brutos vão morar antes de serem tocados.

## 3. PROCESS (Processar)
**A execução da limpeza. Transformar dados brutos em material limpo e útil.**
- **O Trabalho Pesado:** Essa fase consome **60 a 80% do trabalho** de um analista.
- **Ação:** Descartar lixos, nulos ou dados corrompidos. Manter a integridade do banco de dados (ex: células vazias). Se a limpeza for malfeita, as contas da próxima etapa darão errado.
- **Habilidades em Ação:** 
    - **Mentalidade Técnica:** Capacidade de não entrar em pânico. Fatiar o problema gigante de organizar planilhas em pequenas etapas diárias.

## 4. ANALYZE (Analisar)
**Fase de interpretação, exploração e matemática. Onde os padrões e tendências se revelam.**
- **A Ciência de Dados:** É aqui que o *Data Analyst* se diferencia do *Data Scientist*. O Analista busca responder perguntas atuais para decisões rápidas; o Cientista cria modelos para prever o desconhecido.
- **Lidando com os Dados:** É preciso classificar corretamente o que é Numérico, String, Date ou Categórico antes de fazer gráficos.
- **Habilidades em Ação:**
    - **Correlação:** Identificar relações entre duas variáveis. Mas cuidado: **Correlação não significa causalidade.**
    - **Pensamento Macro e Micro:** Ver a imagem completa do negócio (Macro) e focar em encaixar perfeitamente os cálculos matemáticos (Micro).
    - **Design de Dados:** Organizar as colunas e grupos lógicos de forma que a informação faça sentido comercial (ex: descobrir que comédias dão mais lucro que dramas ordenando as colunas certas).

## 5. SHARE (Compartilhar)
**Fase de apresentação dos resultados e relatórios para os tomadores de decisão (Stakeholders).**
- **Apresentação:** Uso da Visualização de Dados (gráficos, mapas, painéis) para explicar de forma simples. Os relatórios devem ir apenas para pessoas autorizadas.
- **Regra de Ouro:** Não entregue apenas o gráfico. Comece sempre pela conclusão (ex: "A taxa caiu 18% porque...").
- **Habilidades em Ação:**
    - **Estratégia de Dados (Data Strategy):** Decidir que tipo de relatório os gestores precisam (ex: Excel estático vs Dashboard do Power BI ao vivo).

## 6. ACT (Agir)
**Fase final onde a empresa executa um plano de ação real para resolver o problema inicial.**
- **Data-Driven vs Gut Instinct:** A decisão deve ser baseada em fatos matemáticos comprovados, e não apenas no instinto (achismo) do diretor.
- **O Fator Humano (SMEs):** Dados sozinhos perdem para "Dados + Experiência Humana". Especialistas na linha de frente (SMEs) ajudam o analista a entender as áreas cinzentas, explicando anomalias do dia a dia (ex: caminhão quebrou no dia do jogo) que um computador não saberia explicar.
- **Ação:** Implementar a solução e validá-la continuamente no futuro. Análise sem ação comercial não tem valor.

---

# Teste de Conhecimentos (Questões Discursivas do Glossário)
*Responda com as suas palavras baseado no Glossário Oficial do Módulo 1.*

**1. O que são Habilidades Analíticas? (Como você as definiria no contexto de resolução de problemas?)**
- **Sua Resposta:** Habilidades são 5: curiosidade - capacidade de questionar e ir atrás dos fatos; contexto - entender as regras de negócio, como os dados se relacionam com as regras de negócio, se X dado está dentro do contexto das regras de negócio ou de um grupo, se aquele dado é válido ou não; mentalidade técnica - capacidade de quebrar um problema em pequenas partes, lidando com cada parte de forma lógica e orientada (ex: faturamento caiu, compara o faturamento do ano anterior com o atual, limpa os dados e analisa); design de dados - é a capacidade de organizar os dados de forma estruturada, por exemplo, organizar o faturamento e a categoria 1 do lado do outro em ordem decrescente, visualizar que x categoria dá mais faturamento; estratégia de dados - capacidade de gestionar pessoas (todos sabem como usar os dados), processos (o processo ocorre sem obstáculos) e ferramentas (as ferramentas certas são utilizadas).
- **Comentário:** Você listou as 5 perfeitamente e, mais importante, deu um exemplo prático brilhante no Design de Dados (colocar faturamento e categoria lado a lado para encontrar o maior lucro).

**2. Qual é a diferença fundamental entre a atuação da Ciência de Dados (Data Science) e a Análise de Dados (Data Analysis)?**
- **Sua Resposta:** Ciencia de dados foca em criar novas perguntas, lidar com previsões e resultados incertos, foco alto em estatística. Analise de dados é a ação de responder perguntas que já existem, encontrar o problema do negócio e conduzir a empresa a melhorar sua posição/resolver os problemas de forma ágil.
- **Comentário:** Resumo perfeito. O cientista lida com previsões estatísticas pesadas para tentar adivinhar o futuro ou achar perguntas novas. O analista é o resolvedor de problemas velozes e ágeis do agora.

**3. Explique o que é a Tomada de Decisões Baseada em Dados (Data-Driven Decision-Making) e cite um exemplo de como ela é superior ao mero "Gut Instinct" (instinto).**
- **Sua Resposta:** Data-driven decision-making faz parte do ato 6 do processo da análise de dados, consiste em tomar a decisão baseada em dados reais e comprovados em vez de achismos, muitas vezes também unidos da experiencia humana. Exemplo: Fazenda teve uma safra ruim nesse semestre, deve ser por causa das condições climáticas (parece óbvio), porém quando foi feito uma pesquisa com os fazendeiros e os dados coletados, disseram na maioria das vezes que foram as pragas.
- **Comentário:** Seu exemplo da fazenda foi fantástico! O "óbvio" (chuva) mascarando a causa raiz real (pragas). O achismo (Gut Instinct) do dono da fazenda teria custado milhões no ano seguinte se ele tivesse comprado sistema de irrigação ao invés de pesticida. É exatamente para isso que o Data-Driven existe.

**4. O que compõe o famoso Ecossistema de Dados de uma empresa?**
- **Sua Resposta:** Ecossistema compõe hardware (nuvem e infraestrutura local), software (ferramentas de análise) e pessoas (analistas que fazem perguntas certas).
- **Comentário:** Matou a pau. Hardware (nuvem/servidores) + Software (ferramentas) + Pessoas. Sem pessoas para fazer as perguntas certas, as outras duas peças são inúteis.

**5. Como você aplicaria a sua Mentalidade Técnica se o seu gerente lhe desse um conjunto de dados gigantesco e extremamente confuso para organizar? O que você faria logo de cara?**
- **Sua Resposta:** Mentalidade técnica seria aplicada dividindo o volume gigantesco de dados em categorias e realizando a limpeza de dados inúteis.
- **Comentário:** Resposta impecável. O segredo é não se desesperar com o volume de dados. Fatiar (categorizar) e executar a limpeza passo a passo. Dividir para conquistar.