# Plano de estudos de Equações Diferenciais

## Missão da disciplina

Equações Diferenciais ensina a transformar hipóteses sobre mudança em modelos que podem ser analisados, resolvidos, verificados e interpretados. O objetivo não é memorizar uma coleção de técnicas, mas decidir:

**qual é a variável dependente → qual é a ordem e a estrutura da equação → qual método é justificável → que condições selecionam a solução → o que a solução significa no modelo.**

Este plano cobre o núcleo do Volume 1 de Zill e Cullen: equações diferenciais ordinárias (EDOs) de primeira ordem e de ordem superior, modelagem, vibrações, séries de potências e transformada de Laplace. O livro também exibe o sumário do Volume 2, mas sistemas, métodos numéricos, estabilidade, séries de Fourier, problemas de contorno e equações diferenciais parciais não são considerados concluídos neste plano apenas porque aparecem no PDF.

O agente deve consultar o [catálogo de referências](../Referencias/catalogo.md) antes de indicar capítulo, seção ou exercício. O registro de cada exercício deve conter, sempre que possível, `material_id`, capítulo/seção, página impressa e número do problema.

## Material-base e escopo

**Material principal:** `ED-ZILL-CULLEN-V1-2001`, *Equações Diferenciais — Volume I*, Dennis G. Zill e Michael R. Cullen, edição brasileira Pearson Makron Books, 2001.

O plano usa os capítulos 1 a 7 como fonte organizada, sem transformar a disciplina em uma sequência cega de capítulos. A paginação indicada no catálogo é a paginação impressa; o PDF pode apresentar outra contagem de páginas.

## Resultado esperado

Ao concluir o Volume 1, o estudante deve ser capaz de:

- identificar ordem, linearidade, homogeneidade, autonomia e tipo de uma EDO;
- traduzir uma situação física, química, biológica ou geométrica em uma equação com hipóteses explícitas;
- resolver EDOs de primeira ordem por separação, fator integrante, equações exatas, substituições e métodos adequados à estrutura;
- distinguir solução geral, particular, singular, implícita e explícita;
- tratar problema de valor inicial e discutir existência, unicidade e intervalo de validade;
- resolver EDOs lineares de ordem superior por fatoração, equação característica, coeficientes indeterminados e variação dos parâmetros;
- construir e verificar modelos de vibrações livres, amortecidas e forçadas e de circuitos elétricos análogos;
- reconhecer quando uma solução elementar não está disponível e usar séries de potências, Frobenius ou funções especiais;
- usar a transformada de Laplace para problemas com condições iniciais, entradas descontínuas, impulsos e funções periódicas;
- verificar soluções por substituição, condições iniciais, unidades, sinais, limites, estabilidade qualitativa e interpretação do modelo;
- explicar por que um método não se aplica, em vez de apenas apresentar um procedimento que produz uma expressão.

## Gate de entrada

Antes de iniciar a sequência principal, exigir desempenho operacional em:

- derivadas de funções elementares e regra da cadeia;
- integrais imediatas, substituição e integrais definidas;
- álgebra, fatoração, frações parciais e resolução de polinômios de baixa ordem;
- funções exponenciais, logarítmicas, trigonométricas e hiperbólicas;
- números complexos em nível suficiente para raízes da equação característica;
- interpretação de gráficos, taxas de variação e unidades;
- leitura de um problema, escolha de variáveis e declaração de hipóteses.

Se o bloqueio for de cálculo, registrá-lo como pré-requisito matemático e ativar uma recuperação específica. Não classificar uma EDO como incompreendida quando o erro observado é apenas algébrico ou de integração.

## Arquitetura do curso

| Unidade | Conteúdo central | Habilidade estável | Pré-requisitos principais |
|---|---|---|---|
| ED0 | Ponte de cálculo, modelagem e diagnóstico | ED-modelo-variacao | Cálculo diferencial e integral elementar |
| ED1 | Linguagem, classificação e modelos | ED-classificacao-modelagem | ED0 |
| ED2 | Métodos para EDOs de primeira ordem | ED-primeira-ordem-metodo | ED1; integração |
| ED3 | Aplicações de primeira ordem | ED-primeira-ordem-modelo | ED2 |
| ED4 | EDOs lineares de ordem superior | ED-linear-ordem-superior | ED2; álgebra linear elementar |
| ED5 | Vibrações, ressonância e circuitos | ED-modelos-dinamicos | ED4; trigonometria |
| ED6 | Coeficientes variáveis e séries | ED-series-frobenius | ED4; séries de potências |
| ED7 | Transformada de Laplace e entradas não suaves | ED-laplace-problema-inicial | integrais; ED4 |
| ED8 | Síntese, transferência e transição | ED-transferencia-volume-1 | ED1-ED7 |

## Unidades detalhadas

### ED0 - Ponte de cálculo, modelagem e diagnóstico

**Pergunta orientadora:** como uma taxa de variação se torna uma equação que representa um sistema real?

**Objetivos:**

- revisar derivada como taxa local e integral como acumulação;
- identificar variável independente, variável dependente, parâmetros e condições;
- traduzir frases como “proporcional a”, “taxa líquida” e “variação em relação ao tempo”;
- distinguir modelo, solução matemática e interpretação física;
- diagnosticar lacunas de cálculo sem esconder o problema dentro da técnica de EDO.

**Representações essenciais:** descrição verbal, diagrama de sistema, gráfico de taxa, equação diferencial, condição inicial e gráfico esperado.

**Erros a vigiar:** escrever uma equação antes de definir variáveis; confundir taxa com quantidade; misturar valor inicial com solução geral; usar constante sem unidade; aceitar uma solução que viola sinal ou limite óbvio.

**Evidência de saída:** construir dois modelos simples, explicar cada termo e prever qualitativamente o comportamento antes de resolver.

### ED1 - Linguagem, classificação e modelagem

**Fonte principal:** capítulo 1, seções 1.1 e 1.2.

**Pergunta orientadora:** o que a forma de uma EDO revela sobre as ferramentas disponíveis e sobre o comportamento possível?

**Objetivos:**

- definir EDO, ordem, solução e família de soluções;
- diferenciar EDO de equação diferencial parcial;
- classificar equações lineares e não lineares, homogêneas e não homogêneas;
- distinguir solução explícita, implícita, geral, particular, singular e trivial;
- identificar domínio, intervalo de validade e condições iniciais;
- formular modelos de crescimento, decaimento, juros, queda, resfriamento, drenagem, mistura, população e circuitos;
- manter separadas hipótese, equação, condição e conclusão.

**Representações essenciais:** tabela de classificação, campo de direções introdutório, gráfico de famílias de soluções e diagrama de balanço.

**Erros a vigiar:** chamar qualquer equação com derivada de “linear”; confundir homogeneidade de uma EDO com homogeneidade de uma função; ignorar domínio; afirmar que toda constante arbitrária gera solução válida; usar um modelo sem declarar o que foi desprezado.

**Evidência de saída:** classificar equações inéditas, verificar uma solução por substituição e montar um problema de valor inicial a partir de uma descrição verbal.

### ED2 - Métodos para EDOs de primeira ordem

**Fonte principal:** capítulo 2, seções 2.1-2.8.

**Pergunta orientadora:** como reconhecer a estrutura de uma EDO antes de escolher o método de solução?

**Objetivos:**

- compreender problema de valor inicial, existência e unicidade em nível operacional;
- resolver equações separáveis, homogêneas, exatas e lineares;
- usar fator integrante com interpretação e verificação;
- reconhecer equações de Bernoulli, Ricatti e Clairaut;
- escolher substituições que reduzam a estrutura da equação;
- entender o método de Picard como aproximação iterativa e como ideia de existência, não apenas como cálculo mecânico;
- controlar constantes, domínios, singularidades e condições iniciais;
- verificar a solução obtida na equação original.

**Protocolo de decisão:**

1. colocar a equação em uma forma que revele suas derivadas e variáveis;
2. testar separabilidade, linearidade, exatidão e homogeneidade;
3. identificar se uma substituição reduz o problema a um tipo conhecido;
4. aplicar a condição inicial no momento adequado;
5. verificar por derivação, substituição e domínio.

**Erros a vigiar:** separar termos sem separar corretamente as variáveis; esquecer soluções constantes ao dividir por uma expressão; usar fator integrante errado; aplicar fórmula de equação linear a uma equação não linear; perder valor absoluto no logaritmo; aceitar uma solução implícita sem discutir o intervalo.

**Evidência de saída:** receber uma EDO nova, justificar o método escolhido, resolver um PVI, verificar o resultado e explicar por que pelo menos dois métodos alternativos não são adequados.

### ED3 - Aplicações de EDOs de primeira ordem

**Fonte principal:** capítulo 3, seções 3.1-3.3 e ensaio de dinâmica populacional.

**Pergunta orientadora:** como uma mesma estrutura de primeira ordem muda de significado quando muda o sistema modelado?

**Objetivos:**

- obter trajetórias ortogonais e interpretar famílias de curvas;
- modelar crescimento e decaimento, resfriamento, mistura, movimento e circuitos;
- distinguir modelos lineares de modelos limitados ou não lineares;
- usar equilíbrio, escalas e comportamento assintótico antes do cálculo completo;
- interpretar parâmetros e dados iniciais;
- comparar solução do modelo com uma previsão qualitativa;
- reconhecer limites de hipóteses como população contínua, mistura instantânea ou resistência idealizada.

**Representações essenciais:** diagrama de fluxo, gráfico de solução, campo de direções, curva de equilíbrio, tabela de parâmetros e unidades.

**Erros a vigiar:** ajustar uma equação sem justificar a taxa; confundir crescimento exponencial com logístico; tratar equilíbrio como solução geral; usar condição inicial incompatível; não distinguir tempo de meia-vida, constante de tempo e taxa.

**Evidência de saída:** formular e resolver um modelo aplicado sem receber a equação pronta, comparar dois regimes de parâmetros e explicar quando a previsão deixa de ser confiável.

### ED4 - EDOs lineares de ordem superior

**Fonte principal:** capítulo 4, seções 4.1-4.7 e ensaio sobre caos.

**Pergunta orientadora:** como a estrutura linear permite decompor uma dinâmica complexa em modos de resposta?

**Objetivos:**

- formular problemas de valor inicial para ordem superior;
- usar dependência linear, independência linear, Wronskiano e conjunto fundamental;
- reduzir a ordem quando uma solução é conhecida;
- resolver equações homogêneas com coeficientes constantes pela equação característica;
- tratar raízes reais distintas, repetidas e complexas;
- encontrar soluções particulares por coeficientes indeterminados, superposição e anuladores;
- usar operadores diferenciais sem substituir entendimento por manipulação simbólica;
- aplicar variação dos parâmetros quando o forçamento não se encaixa em um ansatz simples;
- distinguir resposta complementar, particular, transitória e estacionária.

**Representações essenciais:** espaço de soluções, tabela de raízes, diagrama de modos, gráfico de resposta e decomposição homogênea + particular.

**Erros a vigiar:** contar incorretamente constantes independentes; esquecer fator de multiplicidade em coeficientes indeterminados; tratar raiz complexa como solução não real; usar anulador sem verificar o termo de ressonância; confundir solução particular com solução geral; não aplicar todas as condições iniciais.

**Evidência de saída:** resolver uma EDO linear sem método indicado, justificar a forma da solução, ajustar condições iniciais e interpretar quais termos desaparecem ou dominam no longo prazo.

### ED5 - Modelos vibratórios, amortecimento, forçamento e circuitos

**Fonte principal:** capítulo 5, seções 5.1-5.4 e ensaio sobre o colapso da ponte Tacoma Narrows.

**Pergunta orientadora:** como uma mesma EDO de segunda ordem descreve mola, oscilador amortecido, circuito elétrico e risco de ressonância?

**Objetivos:**

- derivar o modelo massa-mola a partir de força e equilíbrio;
- distinguir movimento harmônico simples, amortecido e forçado;
- interpretar frequência natural, amortecimento, frequência de excitação, fase e ressonância;
- classificar regimes subamortecido, criticamente amortecido e superamortecido;
- separar resposta transitória de resposta estacionária;
- modelar circuitos RLC e identificar a analogia entre grandezas mecânicas e elétricas;
- usar energia e gráfico para verificar a plausibilidade da solução;
- explicar por que grandes amplitudes dependem de frequência, amortecimento e condições iniciais.

**Representações essenciais:** diagrama de forças, circuito, gráfico de amplitude versus frequência, resposta no tempo, plano de fase introdutório e balanço de energia.

**Erros a vigiar:** chamar qualquer oscilação grande de ressonância; esquecer a posição de equilíbrio; misturar coeficiente de amortecimento com taxa de decaimento; confundir frequência natural com frequência aplicada; usar sinais de Kirchhoff sem orientação consistente; ignorar unidades.

**Evidência de saída:** construir um modelo vibratório ou RLC, classificar o regime, prever a resposta antes de resolver e explicar o efeito de alterar amortecimento ou frequência externa.

### ED6 - Coeficientes variáveis, séries e funções especiais

**Fonte principal:** capítulo 6, seções 6.1-6.5.

**Pergunta orientadora:** o que fazer quando a equação não possui uma solução elementar e o ponto de interesse altera a natureza do problema?

**Objetivos:**

- resolver equações de Cauchy-Euler e reconhecer a substituição adequada;
- revisar convergência, raio de convergência e operações com séries de potências;
- construir solução em torno de ponto ordinário por recorrência de coeficientes;
- distinguir ponto ordinário, ponto singular regular e ponto singular irregular;
- aplicar o método de Frobenius nos casos de raízes do índice;
- reconhecer quando surgem soluções independentes com logaritmos ou séries distintas;
- identificar as equações de Bessel e Legendre como modelos especiais;
- interpretar série como representação local com região de validade, não como igualdade sem condições.

**Representações essenciais:** série de potências, relação de recorrência, plano complexo local, tabela de raízes indiciais e gráfico de aproximação parcial.

**Erros a vigiar:** igualar potências sem alinhar índices; errar o raio de convergência; tratar ponto singular como ponto ordinário; esquecer a segunda raiz indicial; dividir por coeficiente que pode ser zero; usar poucas parcelas sem estimar a qualidade da aproximação.

**Evidência de saída:** classificar o ponto, escolher série ordinária ou Frobenius, obter uma relação de recorrência e verificar a aproximação substituindo parcelas na EDO.

### ED7 - Transformada de Laplace

**Fonte principal:** capítulo 7, seções 7.1-7.6; apêndices II e IV quando necessários.

**Pergunta orientadora:** como transformar derivadas e entradas descontínuas em uma equação algébrica que preserve as condições iniciais?

**Objetivos:**

- definir transformada de Laplace e reconhecer condições de existência;
- usar linearidade, tabelas e transformada inversa;
- aplicar teoremas de translação e deslocamento no tempo;
- transformar derivadas e integrais corretamente;
- lidar com frações parciais e raízes complexas;
- tratar funções periódicas, degrau unitário e convolução em nível adequado;
- modelar entradas descontínuas e impulso por função delta de Dirac;
- resolver PVIs e verificar a solução no domínio do tempo;
- entender que Laplace é uma mudança de representação, não um atalho que elimina hipóteses.

**Protocolo de decisão:**

1. definir a função e as condições iniciais;
2. transformar os dois lados com sinais e derivadas corretos;
3. isolar a transformada desconhecida;
4. decompor e inverter com o teorema apropriado;
5. conferir valores iniciais, descontinuidades, limites e a EDO original.

**Erros a vigiar:** esquecer termos de condições iniciais; confundir translação em `s` com translação em `t`; aplicar degrau sem deslocar o argumento; decompor frações parciais incorretamente; interpretar delta como função comum; não testar a solução em `t = 0` ou após a descontinuidade.

**Evidência de saída:** resolver um PVI com forçamento descontínuo, explicar cada propriedade usada e comparar a resposta obtida com uma solução por método clássico quando as duas abordagens forem possíveis.

### ED8 - Síntese, transferência e transição

**Pergunta orientadora:** como escolher, defender e verificar um método quando o enunciado não anuncia a técnica?

**Objetivos:**

- resolver problemas mistos de primeira e segunda ordem;
- escolher entre método clássico, séries e Laplace por estrutura e condições;
- modelar antes de calcular;
- analisar solução, domínio, estabilidade qualitativa, limite e unidade;
- comunicar uma solução com hipótese, método, cálculo, verificação e interpretação;
- identificar quais assuntos exigem o Volume 2.

**Composição recomendada:**

- um problema de modelagem de primeira ordem;
- um problema de classificação e escolha de método;
- um PVI linear de ordem superior;
- um modelo vibratório ou circuito;
- um problema local por série/Frobenius;
- um PVI com Laplace e entrada não suave;
- uma questão de transferência em que o método não seja indicado.

**Evidência de saída:** apresentar duas soluções completas, justificar a escolha do método, encontrar e corrigir um erro inserido em uma solução e explicar a validade do resultado sem depender da resposta final do livro.

## Gates de progressão

### Gate ED-Modelo

- variáveis, parâmetros e condições definidos;
- equação obtida a partir de hipótese explícita;
- comportamento qualitativo previsto antes da solução;
- unidades e sinais coerentes.

### Gate ED-Primeira ordem

- estrutura da equação classificada;
- método escolhido com justificativa;
- PVI resolvido e verificado;
- domínio e possíveis soluções perdidas discutidos;
- interpretação aplicada coerente.

### Gate ED-Ordem superior

- conjunto fundamental identificado;
- raízes reais, repetidas e complexas tratadas corretamente;
- solução particular escolhida pela forma do forçamento;
- condições iniciais e resposta transitória interpretadas.

### Gate ED-Séries e Laplace

- ponto ordinário/singular classificado;
- relação de recorrência ou raízes indiciais verificadas;
- transformada e condições iniciais manipuladas sem perda de termos;
- descontinuidades e domínio da solução interpretados.

### Gate ED-Transferência

- problema inédito resolvido sem método indicado;
- hipótese física/matemática defendida;
- resultado conferido por substituição, limite, unidade ou gráfico;
- método alternativo comparado quando apropriado;
- retenção confirmada em revisão espaçada.

## Avaliação recomendada

- diagnóstico: cálculo, classificação e modelagem;
- avaliação 1: linguagem, primeira ordem e aplicações;
- avaliação 2: ordem superior e modelos vibratórios;
- avaliação 3: coeficientes variáveis, séries e Frobenius;
- avaliação 4: transformada de Laplace e entradas não suaves;
- avaliação final cumulativa, com pelo menos 30% de modelagem, escolha de método e interpretação.

Toda avaliação deve conter ao menos uma questão em que o método não seja indicado, uma verificação de solução e uma explicação de por que determinado método não se aplica.

## Ritmo de referência

Em aproximadamente 16-18 semanas, um ritmo inicial possível é:

- 1 semana: ED0-ED1;
- 3 semanas: ED2;
- 2 semanas: ED3;
- 3 semanas: ED4;
- 2 semanas: ED5;
- 3 semanas: ED6;
- 2 semanas: ED7;
- 1-2 semanas: ED8, recuperação e síntese.

O tempo não é critério de domínio. Se cálculo, álgebra ou séries forem bloqueadores, ativar a recuperação correspondente e manter a prática de classificação e modelagem.

## Instruções específicas ao agente tutor

- Antes de resolver, perguntar qual é a variável dependente, a ordem e a estrutura da EDO.
- Em um modelo, pedir sistema, hipóteses, parâmetros, condição inicial e unidade.
- Não indicar “use separação” ou “use Laplace” sem registrar o capítulo/seção e a razão estrutural.
- Em primeira ordem, perguntar se alguma divisão pode eliminar uma solução constante.
- Em ordem superior, pedir a equação característica e a multiplicidade das raízes antes de escrever a solução.
- Em vibrações, começar pelo equilíbrio, forças e parâmetros, não pela fórmula pronta.
- Em séries, classificar o ponto antes de escolher a forma da expansão.
- Em Laplace, exigir a transformação explícita das condições iniciais e a verificação no tempo.
- Usar soluções do livro para comparação somente depois da tentativa independente, registrando o `material_id` e o problema.
- Não marcar um capítulo como dominado apenas porque o estudante reproduziu um exemplo; exigir transferência para um problema sem método indicado.

## Critério de conclusão e transição

O estudante conclui este plano quando consegue modelar, classificar, resolver e verificar EDOs de primeira ordem e de ordem superior, além de usar séries e Laplace com critérios de validade. A transição para o Volume 2 deve começar por sistemas lineares, métodos numéricos, estabilidade, séries de Fourier e problemas de valor de contorno. Esses conteúdos não estão cobertos pelo PDF catalogado como `ED-ZILL-CULLEN-V1-2001` e devem receber material e registro próprios quando forem adicionados.
