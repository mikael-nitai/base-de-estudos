# Cálculo B

## Missão da disciplina

Cálculo B desenvolve integração como acumulação e processo inverso da diferenciação, amplia o repertório de técnicas e aplicações e introduz sequências e séries. O foco é escolher representações e métodos, justificar convergência e interpretar resultados, evitando que integração se torne apenas reconhecimento de padrões. Equações diferenciais de primeira ordem formam uma trilha opcional, ativada quando a ementa institucional ou o objetivo do estudante exigir.

**Base principal:** Stewart, *Cálculo*, 7ª edição, volume 1, capítulos 5 a 8; volume 2, capítulo 11.

**Extensão opcional:** volume 2, capítulo 9, equações diferenciais de primeira ordem.

**Configuração vigente:** B7 e B8, sobre sequências, séries e Taylor, pertencem ao núcleo deste plano-base. Só podem ser reclassificadas como extensão depois que uma ementa institucional diferente for registrada no repositório; até lá, Cálculo B não deve ser marcado como concluído sem esses blocos.

**Plano compartilhado:** aplicar `fundamentos.md`. Habilidades de Cálculo A que reaparecem devem ser revisadas em contexto, especialmente funções, regra da cadeia, derivação implícita, primitivas, modelagem e unidades.

## Resultado esperado

Ao concluir Cálculo B, o estudante deve ser capaz de:

- interpretar integral definida como acumulação líquida, limite de somas e área orientada;
- usar o Teorema Fundamental do Cálculo em ambas as direções;
- modelar áreas, volumes, trabalho, valor médio e outras grandezas por integrais;
- selecionar e combinar técnicas de integração;
- decidir convergência de integrais impróprias e séries com justificativa;
- trabalhar com séries de potências e aproximações de Taylor, incluindo erro;
- verificar resultados por derivação, estimativa, unidades e comportamento qualitativo.

## Gate de entrada

Antes de B1, exigir nível operacional em:

- funções, composição, inversas, exponenciais, logaritmos e trigonometria;
- limites e continuidade;
- regras de derivação, sobretudo regra da cadeia;
- interpretação de taxa e unidades;
- primitivas elementares e condições iniciais;
- manipulação algébrica e identidades trigonométricas básicas.

Aplicar uma avaliação curta com quatro partes: derivação mista, primitiva, leitura de gráfico de taxa e problema de modelagem. Lacunas em derivação ou funções devem ser recuperadas antes de técnicas avançadas de integração.

## Arquitetura do curso

| Unidade | Conteúdo central | Referência Stewart |
|---|---|---|
| B0 | Recuperação de derivadas, primitivas e somatórios | Cap. 4; apêndice E |
| B1 | Área, soma de Riemann e integral definida | 5.1 e 5.2 |
| B2 | Teorema Fundamental e substituição | 5.3 a 5.5 |
| B3 | Áreas, volumes, trabalho e valor médio | 6.1 a 6.5 |
| B4 | Técnicas de integração | 7.1 a 7.5 |
| B5 | Integração numérica e integrais impróprias | 7.6 a 7.8 |
| B6 | Comprimento, superfícies e aplicações físicas | 8.1 a 8.5 |
| B+ | EDOs de primeira ordem, opcional | 9.1 a 9.6 |
| B7 | Sequências e séries numéricas | 11.1 a 11.7 |
| B8 | Séries de potências e Taylor | 11.8 a 11.11 |
| B9 | Síntese cumulativa e preparação para C | Revisões dos caps. 5 a 8 e 11 |

## Unidades detalhadas

### B0 - Ponte entre derivação e integração

**Objetivos:** recuperar regras de derivação, primitivas, composição, identidades trigonométricas, frações parciais básicas e notação sigma. Explorar a pergunta central: se conhecemos uma taxa em cada instante, como recuperar a variação total?

**Evidência de saída:** derivar e antiderivar funções elementares, interpretar uma taxa em gráfico e manipular um somatório simples.

### B1 - Integral definida e somas de Riemann

**Pergunta orientadora:** como uma soma de contribuições cada vez menores se transforma em uma grandeza exata?

**Objetivos:**

- aproximar área e acumulação por somas à esquerda, direita e ponto médio;
- construir a notação de soma de Riemann;
- interpretar limites de somas;
- compreender área orientada e propriedades da integral;
- estimar sinal e tamanho antes do cálculo;
- distinguir área geométrica de integral líquida.

**Erros a vigiar:** somar áreas quando o problema pede acumulação líquida; ignorar unidades; trocar largura e altura; aceitar integral negativa como “área negativa” sem interpretação.

**Evidência de saída:** escrever uma integral a partir de soma e uma soma a partir de contexto, além de interpretar integral usando gráfico sem encontrar primitiva.

### B2 - Teorema Fundamental do Cálculo e substituição

**Objetivos:**

- compreender diferenciação e integração como processos inversos sob hipóteses adequadas;
- calcular integrais definidas por primitivas;
- diferenciar funções definidas por integrais;
- interpretar função acumulação;
- aplicar substituição como reversão da regra da cadeia;
- transformar limites corretamente em integrais definidas.

**Erros a vigiar:** esquecer constante em integral indefinida; inserir constante em avaliação definida; omitir derivada interna; mudar variável sem mudar limites; aplicar o teorema sem continuidade quando isso for relevante.

**Evidência de saída:** resolver problemas mistos de FTC e substituição, explicar as duas partes do teorema e verificar integrais indefinidas por derivação.

### B3 - Modelagem por integrais

**Objetivos:**

- construir áreas entre curvas com escolha correta da variável;
- modelar volumes por discos, anéis e cascas;
- montar integrais de trabalho e força variável;
- interpretar valor médio de função;
- decidir partições quando curvas ou limites mudam.

**Protocolo de modelagem:** desenhar, escolher fatia representativa, escrever a contribuição elementar com unidades, definir limites, integrar e interpretar.

**Erros a vigiar:** decorar fórmula sem identificar a fatia; usar raio incorreto; misturar `dx` e `dy`; esquecer que curvas trocam de posição; calcular antes de montar o modelo.

**Evidência de saída:** formular, sem receber a fórmula pronta, um problema de volume e um de trabalho; comparar dois métodos possíveis para o mesmo sólido.

### B4 - Técnicas de integração

**Objetivos:**

- usar integração por partes como reversão da regra do produto;
- resolver integrais trigonométricas com análise de paridade;
- aplicar substituição trigonométrica com triângulo e retorno consistente;
- decompor funções racionais em frações parciais;
- combinar simplificação, substituição e técnicas;
- reconhecer quando uma antiderivada elementar não é provável.

**Estratégia obrigatória antes da conta:** simplificar, classificar a estrutura, procurar composição, verificar produtos, considerar identidades e somente então escolher técnica.

**Erros a vigiar:** escolher partes sem reduzir complexidade; usar identidade inadequada; perder restrições de sinal na volta da substituição; montar frações parciais sem fatoração completa; persistir em técnica que aumenta a complexidade.

**Evidência de saída:** conjunto intercalado sem rótulos, com justificativa breve da escolha e verificação por derivação de uma amostra.

### B5 - Aproximação e impropriedade

**Objetivos:**

- entender quando aproximação numérica é necessária;
- aplicar ponto médio, trapézios e Simpson;
- interpretar e controlar erro quando houver fórmula disponível;
- transformar integrais impróprias em limites;
- distinguir intervalo infinito de integrando não limitado;
- usar comparação para decidir convergência.

**Erros a vigiar:** substituir infinito como número; calcular integral antes de verificar convergência; concluir convergência porque uma calculadora retorna valor; aplicar Simpson com número inadequado de subintervalos.

**Evidência de saída:** justificar convergência ou divergência e comparar aproximação numérica com estimativa qualitativa.

### B6 - Aplicações avançadas

**Objetivos:**

- deduzir e aplicar comprimento de arco;
- modelar área de superfície de revolução;
- calcular pressão hidrostática, momentos e centro de massa em casos representativos;
- interpretar densidades e valores esperados em aplicações selecionadas;
- reconhecer como uma soma de pequenas contribuições gera cada integral.

**Evidência de saída:** derivar a estrutura de uma fórmula a partir de elemento diferencial e resolver uma aplicação com análise de unidades.

### B+ - Extensão opcional: equações diferenciais de primeira ordem

Ativar somente se a ementa institucional, uma aplicação ou o objetivo pessoal justificar. A conclusão do núcleo de Cálculo B não depende deste bloco.

**Pergunta orientadora:** como uma lei sobre taxa de mudança determina uma família de comportamentos?

**Objetivos:**

- distinguir equação diferencial, solução geral e problema de valor inicial;
- interpretar campos de direções;
- aplicar o método de Euler e avaliar erro qualitativamente;
- resolver equações separáveis e lineares de primeira ordem;
- modelar crescimento, decaimento, logística, mistura e aplicações selecionadas;
- interpretar equilíbrio e comportamento de longo prazo;
- compreender sistemas predador-presa qualitativamente quando incluídos.

**Erros a vigiar:** separar variáveis de forma inválida; perder soluções de equilíbrio ao dividir; esquecer constante; usar modelo sem validar hipóteses; confundir taxa com quantidade.

**Evidência de saída:** formular uma EDO a partir de descrição, resolver um problema de valor inicial e comparar solução analítica com campo de direções.

### B7 - Sequências e séries

**Objetivos:**

- compreender convergência de sequência e série;
- reconhecer séries geométricas e telescópicas;
- usar condição necessária sem tratá-la como suficiente;
- aplicar teste da integral, comparações, alternadas, razão e raiz;
- distinguir convergência absoluta e condicional;
- escolher teste eficiente e estimar erro ou resto quando possível.

**Árvore de decisão:** verificar termo geral e divergência imediata; procurar estrutura geométrica/telescópica; comparar com modelos conhecidos; analisar sinal; observar fatoriais e potências; escolher teste e justificar hipóteses.

**Erros a vigiar:** confundir sequência com série; concluir convergência porque termos vão a zero; escolher teste pelo nome da seção; usar comparação na direção errada; ignorar convergência absoluta.

**Evidência de saída:** classificar uma coleção mista, justificar a escolha do teste e estimar erro de uma aproximação.

### B8 - Séries de potências e Taylor

**Objetivos:**

- encontrar raio e intervalo de convergência, testando extremidades separadamente;
- representar funções por séries de potências;
- diferenciar e integrar séries dentro do intervalo apropriado;
- construir séries de Taylor e Maclaurin;
- usar polinômios de Taylor para aproximação;
- estimar ou limitar o erro;
- relacionar aproximação local à linearização estudada em A.

**Erros a vigiar:** esquecer extremidades; confundir série de Taylor com igualdade global; omitir domínio de convergência; apresentar aproximação sem controle de erro.

**Evidência de saída:** construir uma série, determinar seu intervalo e justificar a precisão de uma aproximação em ponto especificado.

### B9 - Síntese

Executar uma avaliação cumulativa que inclua:

- interpretação de integral sem antiderivada;
- montagem de aplicação;
- escolha de técnica;
- convergência de integral imprópria;
- seleção de teste de série;
- aproximação de Taylor com erro;
- análise de uma solução incorreta.

Se B+ tiver sido ativado, acrescentar uma modelagem por EDO e a comparação entre solução, campo de direções e contexto.

## Gates de progressão

Além dos itens específicos, cada gate de unidade exige pelo menos 85% em conjunto misto, nenhum erro conceitual crítico, dois problemas rotineiros e um de transferência resolvidos sem ajuda. Isso autoriza avanço provisório; os estados operacional e consolidado dependem das confirmações tardias de `fundamentos.md`.

### Gate B-FTC

- soma, integral e acumulação relacionadas conceitualmente;
- uso correto das duas partes do Teorema Fundamental;
- substituição reconhecida como regra da cadeia inversa;
- interpretação gráfica e unidades.

### Gate B-Modelagem

- construção de integral a partir de fatia ou contribuição;
- limites e variável escolhidos com justificativa;
- distinção entre integral líquida e grandeza positiva;
- solução interpretada no contexto.

### Gate B-Técnicas

- pelo menos 85% em conjunto misto;
- escolha de método justificada;
- verificação por derivação;
- convergência verificada antes de avaliar impróprias.

### Gate B-Convergência

- distinção entre sequência e série;
- seleção adequada de testes;
- hipóteses declaradas;
- tratamento correto de extremidades e erros de truncamento.

### Gate B+-Modelos diferenciais, somente se a extensão for ativada

- formulação de uma EDO;
- solução com condição inicial;
- interpretação de parâmetros, equilíbrio e longo prazo;
- comparação com representação gráfica ou campo de direções.

## Avaliação recomendada

- verificações curtas semanais com conteúdo acumulado;
- avaliação 1: integral definida, FTC e substituição;
- avaliação 2: aplicações e técnicas;
- avaliação 3: integração aproximada, impropriedade e aplicações avançadas;
- avaliação 4: sequências, séries e Taylor;
- final cumulativa com problemas sem rótulo e pelo menos 30% de interpretação/modelagem.

Se B+ for ativado, avaliá-lo separadamente ou integrá-lo à modelagem sem reduzir o tempo do núcleo.

Toda técnica nova deve reaparecer em avaliações posteriores misturada às anteriores. Exercícios refeitos devem vir acompanhados de explicação do erro original e de uma solução nova sem consulta.

## Ritmo de referência

Em 16 a 18 semanas, usar aproximadamente:

- 3 semanas para B0 a B2;
- 3 semanas para B3;
- 4 semanas para B4 a B6;
- 4 semanas para B7 e B8;
- 2 a 4 semanas distribuídas em revisão, recuperação e síntese.

Se B+ for necessário, acrescentar aproximadamente duas semanas ou redistribuir o calendário de acordo com a ementa real, sem comprimir o núcleo. Uma futura ementa institucional pode reclassificar B7 e B8, mas essa alteração deve ser explícita no repositório antes de mudar o critério de conclusão. Em prazo curto, priorizar FTC, modelagem, técnicas essenciais e convergência; não substituir compreensão por listas extensas de integrais semelhantes.

## Instruções específicas ao agente tutor

- Fazer o estudante montar a integral antes de calculá-la.
- Perguntar sempre “o que está sendo acumulado?” e “qual é a unidade do elemento?”.
- Em técnicas, usar listas intercaladas e exigir justificativa de método.
- Em séries, pedir primeiro uma previsão e só depois aplicar teste.
- Se B+ estiver ativo, comparar equação, campo de direções, solução e contexto.
- Usar software para visualizar somas, campos e aproximações, mas exigir argumento matemático independente.
- Reativar regra da cadeia e trigonometria sempre que elas forem a causa real do bloqueio.

## Critério de conclusão e transição para Cálculo C

O estudante está pronto para Cálculo C quando consegue:

- interpretar e calcular integrais definidas;
- montar integrais a partir de geometria ou aplicação;
- selecionar técnicas sem rótulo;
- usar trigonometria em radianos e geometria analítica com segurança suficiente para iniciar coordenadas e parametrizações em C;
- usar derivadas e integrais de funções trigonométricas com segurança;
- compreender vetores básicos ou concluir o módulo F6 antes do bloco vetorial de C;
- sustentar desempenho em uma avaliação cumulativa posterior.

Séries enriquecem a formação e B+ prepara aplicações diferenciais, mas as lacunas que bloqueiam imediatamente C são integração, trigonometria, geometria analítica, vetores e regra da cadeia.
