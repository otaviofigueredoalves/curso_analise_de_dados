# Resumo: Transforme Dados em Insights (Etapa 2)

## 1. Sobre Análise de Dados
- **Análise Natural:** As pessoas analisam dados naturalmente no dia a dia. Por exemplo: ao perceber que você se sente mais produtivo de manhã ou que o melhor horário para malhar é à tarde (baseado nos padrões do seu tempo livre).
- **O Papel Corporativo:** Nas empresas, o papel do analista é identificar o problema de negócio, analisar os dados para solucioná-lo e orientar a execução de uma ação.
- **O Objetivo:** Alcançar a meta de negócio utilizando as 6 etapas da análise de dados: Perguntar, Preparar, Processar, Analisar, Compartilhar e Executar (Agir).

### 1.1. Análise de Dados de Pessoas (People Analytics)
- É a prática de coletar e analisar dados referentes aos funcionários de uma empresa.
- **Objetivo:** Obter insights que ajudem a melhorar a cultura, a retenção de talentos e a forma geral como a empresa opera.

---

## 2. As 6 Etapas da Análise de Dados (Framework do Google)
Para guiar o trabalho do analista de ponta a ponta, utilizamos este framework estruturado:

1. **ASK (Perguntar)**
   *A fase onde é definido o problema do projeto, o escopo e o contexto para alcançar a finalidade.*
   * **Exemplos de perguntas investigativas (RH):** 
     * O que os funcionários devem aprender para ter sucesso no primeiro ano?
     * Já temos dados históricos de novos funcionários?
     * Por que os funcionários estão insatisfeitos? E qual é a causa raiz disso?

2. **PREPARE (Preparar)**
   *Fase de definição do plano de coleta e separação do que será útil para o projeto.*
   * **Métricas:** Definir as perguntas específicas que guiarão a coleta.
   * **Segurança e Ética:** Estabelecer regras de acesso, garantir o sigilo e comunicar aos colaboradores para que seus dados serão usados.
   * **Prevenção:** Antecipar possíveis problemas ou vieses antes de iniciar a coleta.

3. **PROCESS (Processar)**
   *Colocação do plano em prática: limpeza e tratamento dos dados brutos.*
   * **Consentimento:** Garantir que os dados coletados possuem permissão (compliance).
   * **Acesso:** Limitar o acesso aos dados brutos apenas aos analistas necessários para evitar vazamentos.
   * **Limpeza:** Descartar dados nulos, lixos ou corrompidos e utilizar apenas o que é completo e relevante.
   * **Armazenamento:** Salvar os dados processados em um local de banco de dados seguro.

4. **ANALYZE (Analisar)**
   *A fase de interpretação para identificar padrões e validar hipóteses (fazer as contas).*
   * **Descobertas (Exemplos práticos):** 
     * Processo de contratação muito longo = maior taxa de abandono do candidato.
     * Processo de avaliação eficiente = maior taxa de satisfação e menor rotatividade (turnover).
   * **Transparência:** Todo o processo deve ser documentado exatamente como foi descoberto, passando credibilidade técnica à pesquisa.

5. **SHARE (Compartilhar)**
   *Fase de apresentação dos resultados e relatórios para os tomadores de decisão (Stakeholders).*
   * Compartilhar os relatórios apenas com gerentes ou líderes autorizados.
   * Apresentar os resultados de forma muito clara (com painéis ou gráficos), garantindo que todo o contexto foi entendido.

6. **ACT (Agir)**
   *Fase final onde a empresa traça e executa um plano de ação real para resolver o problema com base nos seus insights.*
   * **Exemplo de Ação:** Padronizar o processo de contratação da empresa para torná-lo transparente.
   * **Validação:** Realizar a mesma pesquisa no ano seguinte para comparar os resultados (ex: a taxa de retenção realmente melhorou pós-mudanças?).

---

## 3. O Papel do Analista e a Ciência de Dados
A "Ciência de Dados" é um termo amplo que engloba três grandes disciplinas. É fundamental entender qual combina com seu perfil:

* **Estatística:** Foco absoluto no rigor matemático. Ideal para quem quer se proteger contra decisões equivocadas sob incerteza. Valoriza a precisão sobre a velocidade.
* **Aprendizado de Máquina (Machine Learning):** Ideal para perfis de engenharia que gostam de automações, algoritmos e extrema performance de sistemas.
* **Análise de Dados (Analytics - O Seu Foco!):** O analista é visto como **explorador, detetive e artista**. É ideal para quem lida bem com a ambiguidade de negócios, explora dados de forma ágil para achar insights de mercado e prefere a "descoberta rápida" em vez da perfeição matemática absoluta.

---

## 4. Tipos Comuns de Dados
Antes de limpar ou processar qualquer planilha, é vital saber identificar os tipos de dados contidos nela para evitar que seus cálculos quebrem:

* **Numéricos:** Dados puramente quantitativos que podem sofrer operações matemáticas ou financeiras. *(Ex: peso, idade, preço, altura).*
* **Textos (Strings):** Palavras, frases ou misturas de letras e números. Servem exclusivamente como **identificadores** e nunca para cálculos. *(Ex: nome do cliente, endereço, CPF, CEP, número de telefone).*
* **Data (Date/Timestamp):** Dados que representam um ponto temporal específico. Essenciais para identificar tendências históricas. *(Ex: data do pedido, data de nascimento, log de horário).*
* **Categóricos:** Dados que dividem a informação em grupos ou rótulos discretos. *(Ex: cor do produto [azul/verde], avaliação textual [Bom/Ruim], status de fidelidade [Ouro/Prata]).*


## QUESTÕES PRÁTICAS + GABARITO
### 1. Qual das 6 etapas (Framework do Google) é responsável por definir o plano de coleta, as métricas, os mecanismos de segurança e as regras de acesso antes mesmo de colocar a mão na massa?

a) Processar (Process)
b) Preparar (Prepare)
c) Analisar (Analyze)
d) Perguntar (Ask)
### 2. Você recebeu uma planilha de Vendas. Uma das colunas se chama "Status de Fidelidade", contendo os valores: Ouro, Prata e Bronze. Qual é a classificação correta desse tipo de dado?

a) Dados Numéricos
b) Dados de Texto (String)
c) Dados Categóricos
d) Dados de Data (Date)
### 3. O módulo cita que o perfil do Analista é visto como um "explorador/detetive". Se você gosta de explorar dados de forma ágil para achar insights de negócios rápidos e lida bem com a ambiguidade, você está focado em qual disciplina?

a) Estatística, porque protege contra erros.
b) Aprendizado de Máquina (Machine Learning), porque foca na performance.
c) Análise de Dados (Analytics), porque prioriza a descoberta acima da perfeição matemática.
d) Engenharia de Hardware.
### 4. Pergunta Aberta (Discursiva): Na etapa de Processar (Process), aprendemos que o analista deve limpar a base de dados (descartando lixos, nulos ou inconsistências). Na sua opinião, por que essa limpeza prévia é tão crucial antes de seguirmos para a etapa de "Analisar" (que é onde se faz as contas)?

### GABARITO
- 1. Letra B (Preparar) - Exato! A fase de Processar (onde a maioria das pessoas se confunde) é a execução da limpeza. Mas a fase onde você define as regras, os planos de métricas e os acessos de segurança antes de tudo acontecer é a Preparação.

- 2. Letra C (Dados Categóricos) - Perfeito! Ouro, Prata e Bronze dividem os clientes em categorias (rótulos) claras. Saber disso evita que você tente (por acidente) somar "Ouro + Prata", pois o computador não entenderia o cálculo.

- 3. Letra C (Análise de Dados) - Certíssimo! Enquanto o estatístico foca em não errar de jeito nenhum e o engenheiro de machine learning foca no robô, o analista quer descobrir os "furos" do negócio de forma ágil para ajudar a empresa a agir rápido.

- 4. Resposta Aberta
    R: Essa limpeza é crucial pois garante que a hipótese seja validada corretamente, ou, a formulação de uma nova hipótese basedado em dados completos e úteis. Por exemplo: analisando avaliações de um restaurante que é 1 estrela, mas não limpar os dados que são incompletos ou nulos, avaliações sem justificativa...

Excelente exemplo prático! A sua analogia do restaurante foi matadora. Se você tentar tirar uma "Média de satisfação" misturando dados reais com linhas onde o cliente colocou letras aleatórias, deu nota e não justificou, ou deixou a nota em branco, o seu cálculo matemático vai quebrar (dando erro) ou, pior ainda, vai dar um resultado falso que fará o dono do restaurante tomar a decisão errada. Limpar (Processar) garante que a Análise seja matematicamente segura.